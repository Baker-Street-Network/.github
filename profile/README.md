## Welcome to Baker Street 👋
This is the central location for managing our Odoo projects. You can see our installations and available modules below.

### Odoo Installations
| Instance                                               | Edition      | Version | Build Status     |
| ------------------------------------------------------ | ------------ | ------- | ---------------- |
| [erp.crop-doc.com](https://erp.crop-doc.com)           | Enterprise   | 17.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/crop-doc/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/crop-doc/actions/workflows/build_and_deploy.yml)
| [erp.keilycattle.com](https://erp.keilycattle.com)     | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/keily-cattle/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/keily-cattle/actions/workflows/build_and_deploy.yml)
| [olivetree.software](https://olivetree.software)       | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/stauffer-enterprises/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/stauffer-enterprises/actions/workflows/build_and_deploy.yml)
| [ncautomation.com](https://odootest.ncautomation.com)  | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/neil-co/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/neil-co/actions/workflows/build_and_deploy.yml)
| [ws.cropdoc.report](https://ws.cropdoc.report)         | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/washington-street/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/washington-street/actions/workflows/build_and_deploy.yml)
| [sidney.cropdoc.report](https://sidney.cropdoc.report) | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/sidney-rudolph/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/sidney-rudolph/actions/workflows/build_and_deploy.yml)
| [shepherdspathway.org](https://shepherdspathway.org)   | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/shepherds-pathway/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/shepherds-pathway/actions/workflows/build_and_deploy.yml)
| [mtntrails.org](https://mtntrails.org)                 | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/mtn-trails/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/mtn-trails/actions/workflows/build_and_deploy.yml)
| [kent.cropdoc.report](https://kent.cropdoc.report)     | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/kent-martin/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/kent-martin/actions/workflows/build_and_deploy.yml)
| [nathan.cropdoc.report](https://nathan.cropdoc.report) | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/nathan-martin/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/nathan-martin/actions/workflows/build_and_deploy.yml)
| [accounting.nsinnovations.net](accounting.nsinnovations.net) | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/kings-tech/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/kings-tech/actions/workflows/build_and_deploy.yml)

### Local Modules
These are modules that are available to all installations.

| Module                   | Version(s)    | Notes             |
| ------------------------ | ------------- | ----------------- |
| [base-accounting-kit](https://github.com/Baker-Street-Network/base-accounting-kit)           | 18.0       | Adds advanced accounting features to the Community edition.              |
| [muk-web-theme](https://github.com/Baker-Street-Network/muk-web-theme)                       | 18.0       | Adds an Enterprise-like theme to the Community edition.                  |
| [telerik-reporting](https://github.com/Baker-Street-Network/telerik-reporting)               | 17.0, 18.0 | Requires the Telerik Reporting binary to be running.                     |
| [knowledge-scaffold](https://github.com/Baker-Street-Network/knowledge-scaffold)             | 17.0, 18.0 | Uses OpenAI to generate a list of questions from KB articles.            |
| [zip-fill](https://github.com/Baker-Street-Network/zip-fill)                                 | 17.0, 18.0 | Fills city and state from zip code. Add county and township from Mapbox. |
| [web-refresher](https://github.com/Baker-Street-Network/web-refresher)                       | 17.0       | Adds a refresh button to all views.                                      |
| [auto-upgrade](https://github.com/Baker-Street-Network/auto-upgrade)                         | 17.0       | Works with the GitHub Actions scripts to automatically upgrade.          |
| [advanced-keyboard...](https://github.com/Baker-Street-Network/advanced-keyboard-shortcuts)  | 17.0       | Adds more keyboard shortcuts.                                            |
| [auto-database-backup](https://github.com/Baker-Street-Network/auto-database-backup)         | 17.0       | Auto database backup module.                                             |
| [odoo-development-pack](https://github.com/Baker-Street-Network/odoo-development-pack)       | 17.0       | Mainly disables websockets for breakpoints.                              |
| [knowledge-full-text](https://github.com/Baker-Street-Network/knowledge-full-text)           | 17.0       | Allows full text searching of the Knowledge module.                      |
| [knowledge-camera](https://github.com/Baker-Street-Network/knowledge-camera)                 | 17.0       | Allows capturing images straight from the Odoo module.                   |
| [cd-styles](https://github.com/Baker-Street-Network/cd-styles)                               | 17.0       | Enlarges buttons and various other tweaks.                               |
| [itlibertas-timesheet](https://github.com/Baker-Street-Network/itlibertas-timesheet)         | 18.0       | Timesheet tracking for Odoo Community                                    |
| [bi-plaid-integration](https://github.com/Baker-Street-Network/bi-plaid-integration)         | 18.0       | A Plaid integration for Odoo Community                                   |
| [dev-login](https://github.com/Baker-Street-Network/dev-login)                               | 17.0       | Allows users to login as any user if they are running on localhost.      |

To install one of these modules, use the following command:
`git submodule add "https://github.com/Baker-Street-Network/telerik-reporting-module" .\addons\telerik-reporting

A note on the `muk-web-theme` and the `base-accounting-kit`. Both of these have sub-folders, so you may want to check these out in their own addons folders, then include this in the Dockerfile's run command manually.

### Initializing an Instance
To create a new instance, follow the instructions in the [odoo-template repository](https://github.com/Baker-Street-Network/odoo-template).
