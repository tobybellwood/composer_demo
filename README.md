# composer_demo

A project to test https://github.com/renovatebot/config-help/issues/883

There are two required packages 
`"cweagans/composer-patches": "^1.6"` , in require and
`"pyrech/composer-changelogs": "^1.6"`, in require-dev

Neither of these packages are installed at their latest versions intentionally.

It is my expectation that RenovateBot will submit an initial PR to:
* pin composer-patches at 1.6.0 (as installed),
* pin composer-changelogs at 1.7.1 (latest available version, not 1.6.0 as installed)

The correct behaviour would be to pin to 1.6.0 for both packages


