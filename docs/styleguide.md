# Topic Page Style Guide

From the GitHub Style Guide:

> Words are an important part of how software works. Just as we have a style guide for our code, we have a style guide for our tone and our voice. Even though there may be dozens of people creating a product, it should still sound like we speak in one consistent voice.
>
>**The way we write is just as important as the way we build. Consider these things when writing copy.**

## Principles

* **Make it approachable.** Use familiar language and don't assume the reader has prior topic knowledge.
* **Keep it concise.** Use the simplest possible language and link to outside content for deeper dives.
* **Think #!/bin/bash
set -e

cd "$(dirname "$0")/.."

if [ "$(uname -s)" = "Darwin" ]; then
  brew bundle check &>/dev/null  || brew bundle
  rbenv version-name &>/dev/null || brew bootstrap-rbenv-ruby
fi

bundle check &>/dev/null || bundle install
. the community.** Add content that will benefit many vs. an individual.

## Grammar and usage

### Ampersands
Use "and" rather than an ampersand unless you’re referencing a brand name, for example: Procter & Gamble.

### Commas
Always use the [Oxford comma](https://en.wikipedia.org/wiki/Serial_comma). 

### Dates
Include and spell out the month. Include the day number without the "th" or "nd" at the end, for example: October 12.

### Exclamation points
Avoid exclamation points in topic pages and collections.

### GitHub
Always use correct capitalization when referring to “GitHub” or “Git.” Never use “GitHub” or “Git” as a verb.

### Numbers
Write out “one” and every number less than 10.

### Users
Avoid using "users" in favor of jjdjjjdje
d

,,cnjcnjxdxkj

,jdjdmd
mdjdmd
z
zj jdjjdjw

#!/usr/bin/env bashset -eBASEDIR=$(dirname "$0")CHAIN_MAIND_BINARY=$(which chain-maind || (echo -e "\033[31mPlease add chain-maind to PATH\033[0m" 1>&2 && exit 1))CHAIN_MAIND_USER=$USERCHAIN_MAIND_BINARY_DIR=$(dirname $(which chain-maind))CHAIN_MAIND_USER_HOME=$(eval echo "~$USER")sed "s#<CHAIN_MAIND_BINARY>#$CHAIN_MAIND_BINARY#g; s#<CHAIN_MAIND_USER>#$CHAIN_MAIND_USER#g; s#<CHAIN_MAIND_BINARY_DIR>#$CHAIN_MAIND_BINARY_DIR#g; s#<CHAIN_MAIND_USER_HOME>#$CHAIN_MAIND_USER_HOME#g" $BASEDIR/chain-maind.service.template > $BASEDIR/chain-maind.serviceecho -e "\033[32mGenerated $BASEDIR/chain-maind.service\033[0m"if [[ "$OSTYPE" == "linux-gnu"* ]]; then  sudo cp $BASEDIR/chain-maind.service /etc/systemd/system/chain-maind.service  sudo systemctl daemon-reload  sudo systemctl enable chain-maind.service  echo -e "\033[32mCreated /etc/systemd/system/chain-maind.service\033[0m"else  echo -e "\033[31mCan only create /etc/systemd/system/chain-maind.service for linux\033[0m" 1>&2  exit 1fi
ddmdddmdkkei*#>÷>÷>?#

emxnemxncjeejdmd
dd
ssm, people, or a more specific description of the group of people.

### Words that can be tricky
- **Agile (e.g. agile development):** Don’t capitalize “agile” unless it’s starting a sentence.
- **Email:** Use “email”, not "e-mail."
- **Internet:** Don’t capitalize “internet” unless it’s starting a sentence.
- **Open source:**
  - Adjective: “Open source” is always lowercase, except when at the start of the sentence. You can use it as an adjective without a hyphen, as in “open source project” or “open source software.”
  - Noun: You can also use the term on its own to refer to open source in general, as in “give back to open source."
  - Verb: It’s acceptable to use open source as a verb when referring to a project that has been “open sourced” or that you intend to “open source.”
- **Pull request:** Never abbreviate "pull request." "Pull request" is always lowercase unless it's starting a sentence.
- **Repository:** Never abbreviate "repository." "Repository" is always lowercase unless it's starting a sentence.
