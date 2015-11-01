## vnstat

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![GitHub Tags](https://img.shields.io/github/tag/ypid/ansible-vnstat.svg)](https://github.com/ypid/ansible-vnstat)
[![GitHub Stars](https://img.shields.io/github/stars/ypid/ansible-vnstat.svg)](https://github.com/ypid/ansible-vnstat)





### Role variables

List of default variables available in the inventory:

```YAML
---

## Check `man vnstat.conf` for details.

## "Global" vnStat configuration variables.
vnstat_config_options:
  MaxBandwidth: 0
  # RXHourCharacter: R

## "Host group" vnStat configuration variables.
vnstat_group_config_options: {}

## "Host" vnStat configuration variables.
vnstat_host_config_options: {}


vnstat_packages:
  - 'vnstat'
  # - 'vnstati'
```

List of internal variables used by the role:

    vnstat_config_options


### Authors and license

`vnstat` role was written by:
- [Robin Schneider](https://github.com/ypid) | [e-mail](mailto:ypid@riseup.net)

License: [AGPLv3](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-%28agpl-3.0%29)

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
