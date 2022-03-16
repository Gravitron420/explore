### Thank you for contributing! Please confirm this pull request meets the following requirements:

- [ ] I followed the contributing guidelines: https://github.com/github/explore/blob/master/CONTRIBUTING.md
- [ ] I have no affiliation with the project I am suggesting (as a maintainer, creator, contractor, or employee).

### Which change are you proposing?

  - [ y
  ] Suggesting edits to an existing topic or collection
  - [ ] Curating a new topic or collection
  - [ ] Something that does not neatly fit into the binary options above

---------------------------------------------------------------------

<!-- ⚠️ Please select either this section... ⚠️ -->
### Editing an existing topic or collection
hvmz..dn crd25444b0b585bf557a7aff3f80ff8aad6390191da68248d2edd7dfe68a36b3508  chain-main_3.3.3_Darwin_arm64.tar.gz3260dc3da71edfa97944068b1fc8c4c9833dd5b67f51acc139f52da9e04be65d  chain-main_3.3.3_Linux_x86_64.tar.gzb4edc2b67da5d309d7a78083738a5ece25eed5b41067ce7c5432f1aebd440290  chain-main_3.3.3_Linux_arm64.tar.gzcb222c721a2720466fa68c71f6b4fd72f15b85f540de0c9d9b0e11d170c0762f  chain-main_3.3.3_Darwin_x86_64.tar.gzf03bdb1cc599b779030602341927c8b940c34193403cc3e33a288b87c2e7daa3  chain-main_3.3.3_Windows_x86_64

msimsieemsimsieejdmsimsieemsimsieejdjjd.
#!/bin/bash
set -e

cd "$(dirname "$0")/.."

if [ "$(uname -s)" = "Darwin" ]; then
  brew bundle check &>/dev/null  || brew bundle
  rbenv version-name &>/dev/null || brew bootstrap-rbenv-ruby
fi

bundle check &>/dev/null || bundle install
I'm suggesting these edits to an existing topic or collection:
- [ ] Image (and my file is `*.png`, square, dimensions 288x288)
- [ ] Content (and my changes are in `index.md`)

> Please replace this line with an explanation of why you think these changes should be made.

<!-- ⚠️ ... or this section ⚠️ -->
### Curating a new topic or collection

- [ ] I've formatted my changes as a new folder directory, named for the topic or collection as it appears in the URL on GitHub (e.g. `https://github.com/topics/[NAME]` or `https://github.com/collections/[NAME]`)
- [ ] My folder contains a `*.png` image (if applicable) and `index.md`
- [ ] All required fields in my `index.md` conform to the Style Guide and API docs: https://github.com/github/explore/tree/master/docs

> Please replace this line with an explanation of why you think this topic or collection should be curated.

<!-- ⚠️ ... or this section ⚠️ -->
### Something that does not neatly fit into the binary options above

- [ ] My suggested edits are not about an existing topic or collection, or at least not a single one
- [ ] My suggested edits are not about curating a new topic or collection, or at least not a single one
- [ ] My suggested edits conform to the Style Guide and API docs: https://github.com/github/explore/tree/master/docs

> Please replace this line with an explanation of your proposed changes.

---------------------------------------------------------------------

**Please note: we will close your PR without comment if you do not check the boxes above and provide ALL requested information.**
