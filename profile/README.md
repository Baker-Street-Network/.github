## Welcome to Baker Street 👋
This is the central location for managing our Odoo projects. You can see our installations and available modules below.

Our status page is hosted by UptimeRobot and is [available here](https://status.bakerstreet.network).

### Odoo Installations
| Instance                                               | Edition      | Version | Build Status     |
| ------------------------------------------------------ | ------------ | ------- | ---------------- |
| [crop-doc.com](https://crop-doc.com)                   | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/crop-doc/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/crop-doc/actions/workflows/build_and_deploy.yml)
| [keilycattle.com](https://keilycattle.com)             | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/keily-cattle/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/keily-cattle/actions/workflows/build_and_deploy.yml)
| [olivetree.software](https://olivetree.software)       | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/stauffer-enterprises/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/stauffer-enterprises/actions/workflows/build_and_deploy.yml)
| [ncautomation.com](https://odootest.ncautomation.com)  | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/neil-co/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/neil-co/actions/workflows/build_and_deploy.yml)
| [dayset.memorial](https://dayset.memorial)             | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/dayset-memorials/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/dayset-memorials/actions/workflows/build_and_deploy.yml)
| [erp18.steelgrade.ca](https://erp18.steelgrade.ca)     | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/steelgrade/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/steelgrade/actions/workflows/build_and_deploy.yml)
| [ws.cropdoc.report](https://ws.cropdoc.report)         | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/washington-street/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/washington-street/actions/workflows/build_and_deploy.yml)
| [sidney.cropdoc.report](https://sidney.cropdoc.report) | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/sidney-rudolph/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/sidney-rudolph/actions/workflows/build_and_deploy.yml)
| [shepherdspathway.org](https://shepherdspathway.org)   | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/shepherds-pathway/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/shepherds-pathway/actions/workflows/build_and_deploy.yml)
| [mtntrails.org](https://mtntrails.org)                 | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/mtn-trails/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/mtn-trails/actions/workflows/build_and_deploy.yml)
| [kent.cropdoc.report](https://kent.cropdoc.report)     | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/kent-martin/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/kent-martin/actions/workflows/build_and_deploy.yml)
| [nathan.cropdoc.report](https://nathan.cropdoc.report) | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/nathan-martin/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/nathan-martin/actions/workflows/build_and_deploy.yml)
| [kevin.cropdoc.report](kevin.cropdoc.report)           | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/kevin-martin/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/kevin-martin/actions/workflows/build_and_deploy.yml)
| [cf.cropdoc.report](cf.cropdoc.report)                 | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/cf/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/cf/actions/workflows/build_and_deploy.yml)
| [erp.anabaptist...](erp.anabaptistcodeblocks.com)      | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/codeblocks/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/codeblocks/actions/workflows/build_and_deploy.yml)

## Accessing Backups
If you are routinely downloading and testing backups, check out our utilities repository: [Baker-Street-Network/utilities](https://github.com/Baker-Street-Network/utilities) <br />
To simply browse backups and see availability, access the backup browser: https://backups.bakerstreet.network/backups (or, locally, http://192.168.55.135/backups, without auth)
For development backups, check out: https://dev-backups.bakerstreet.network, or, locally: http://192.168.55.251/backups.

Steelgrade is the in-house utility for running backups on our production systems. It is comprised of four parts:
- Steelgrade Backup: [Baker-Street-Network/steelgrade-backup](https://github.com/Baker-Street-Network/steelgrade-backup)
- Steelgrade Cleaner: [Baker-Street-Network/steelgrade-cleaner](https://github.com/Baker-Street-Network/steelgrade-cleaner)
- Steelgrade Mover: [Baker-Street-Network/steelgrade-mover](https://github.com/Baker-Street-Network/steelgrade-mover)
- Steelgrade Staging: [Baker-Street-Network/steelgrade-staging](https://github.com/Baker-Street-Network/steelgrade-staging)

## Initializing an Instance
To create a new instance, follow the instructions in the [odoo-template repository](https://github.com/Baker-Street-Network/odoo-template).

## Module Groups
We have several collection of modules that we typically install on our hosted instances. Run all checkout scripts at the root the repository.

**Odoo Themes** This is the default Odoo theme:
```
git submodule add -b 18.0 https://github.com/odoo/design-themes addons/odoo/design-themes
```
**Essentials** This is a collection of modules that we developed internally that are used heavily. To add these to your instance:
```
git submodule add -b 18.0 https://github.com/Baker-Street-Network/essentials addons/baker-street/essentials
```
**Open Essentials** These are modules that we find useful in Community installs. To checkout these:
```
git submodule add -b 18.0 https://github.com/Baker-Street-Network/open-essentials addons/baker-street/open-essentials
```
**MuK Web Theme** This is a nice theme for community installs:
```
git submodule add -b 18.0 https://github.com/muk-it/odoo-modules addons/muk/odoo-modules
```
**Cybrosis Addons** Each night, we sync a small list of Cybrosis modules to our own clone:
```
git submodule add -b 18.0 https://github.com/Baker-Street-Network/cybrosis addons/baker-street/cybrosys
```
**OCA (e.g. web)** We also use many of modules from OCA:
```
git submodule add -b 18.0 https://github.com/oca/web addons/oca/web
```
**Odoomates Accounting** Odoomates offers a great accounting module. This is a nightly clone from their repository with only the applicable modules available:
```
git submodule add -b 18.0 https://github.com/odoomates/odooapps addons/odoomates/odooapps
```

If you are moving a module from a repository to a Git submodule, you'll have to clean the index first:
`git rm -r --cached addons/module_name`
