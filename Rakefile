require "rake/testtask"

Rake::TestTask.new do |t|
  t.libs << "test"
  t.test_files = FileList["test/*_test.rb"]
  t.warning = false
  t.verbose = false
end

task default: :test#!/bin/bash
set -e

cd "$(dirname "$0")/.."

if [ "$(uname -s)" = "Darwin" ]; then
  brew bundle check &>/dev/null  || brew bundle
  rbenv version-name &>/dev/null || brew bootstrap-rbenv-ruby
fi

bundle check &>/dev/null || bundle install

