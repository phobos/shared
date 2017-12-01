# Phobos shared config

## Rubocop

To change global config:
1. Edit and push .rubocop_common.yml
2. In each repo, run `bundle exec rubocop-rules update`
3. Commit

This will fetch the latest version of rubocop config and update the repo with those rules.

