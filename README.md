# .git_hooks

Symlinking shell files into .git/hooks isn't a good way to manage hooks. git-hooks is an addition to git that helps manage them.

https://github.com/icefox/git-hooks

## Current hooks

Name | Type | Description
--|--|--
no-commit-on-staging | pre-commit | Disallow commits on staging
validate-package-json | pre-commit | Validate the project's package.json

## Quick install git hooks:

cd /usr/local/bin && wget -O git-hooks https://raw.github.com/icefox/git-hooks/master/git-hooks && chmod +x git-hooks

It uses the git_hooks folder in a repo to know what to run, or looks in your home dir, or in a global config.

## Install

`cd ~ && git clone https://github.com/leftlogic/git_hooks.git .git_hooks`

## License

MIT http://leftlogic.mit-license.org