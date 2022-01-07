# Rename Admin Paths

The purpose of this module is to secure the Backdrop backend by overriding admin
 paths.

This module allows you to:

- rename paths like '/admin/...' to '/something/...'
- rename paths like '/user/..' to '/something-else/..'

It can be effective against registration spam bots or malicious people.

Although this module only obfuscates the paths, this may already be a big
 help to get rid of those bots trying to probe passwords on /user/login or
 register spam accounts on /user/register. They get a "404 not found" then.

## Installation

Install this module using the official
 [Backdrop CMS instructions](https://docs.backdropcms.org/documentation/extend-with-modules)

## Issues

Bugs and Feature requests should be reported in the
 [Issue Queue](https://github.com/backdrop-contrib/rename_admin_paths/issues.)

## Current Maintainers

- [Indigoxela](https://github.com/indigoxela)

## Credits

- Ported to Backdrop CMS by [Indigoxela](https://github.com/indigoxela)
- Originally written for Drupal by [Raphael Apard](https://www.drupal.org/u/raphael-apard).
- Maintained for Drupal by [many wonderful people](https://www.drupal.org/node/1287470/committers).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
 complete text.
