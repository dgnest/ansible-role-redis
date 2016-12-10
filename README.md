# Ansible Role Redis

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/dgnest/ansible-role-redis.svg)](https://travis-ci.org/dgnest/ansible-role-redis)
[![Stories in Ready](https://badge.waffle.io/dgnest/ansible-role-redis.svg?label=ready&title=Ready)](http://waffle.io/dgnest/ansible-role-redis)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-redis.svg)](https://github.com/dgnest/ansible-role-redis/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [redis][link-redis] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - [Homebrew][link-brew] must be installed.


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for redis


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - redis

To install a specific version:

    - hosts: servers
      roles:
         - { role: dgnest.redis }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.


## Credits

Made with :heart: ️:coffee:️ and :pizza: by [dgnest][link-company].

- [All Contributors][link-contributors]


<!-- Other -->

[link-redis]: https://redis.org/
[link-brew]: http://brew.sh/
[link-luis]: https://github.com/luismayta
[link-contributors]: AUTHORS
[link-company]: https://github.com/dgnest
