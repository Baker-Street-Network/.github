## Welcome to Baker Street 👋
This is the central location for managing our Odoo projects. You can see our installations and available modules below.

### Odoo Installations
| Instance                                               | Edition      | Version | Build Status     |
| ------------------------------------------------------ | ------------ | ------- | ---------------- |
| [erp.crop-doc.com](https://erp.crop-doc.com)           | Enterprise   | 17.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/crop-doc/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/crop-doc/actions/workflows/build_and_deploy.yml)
| [erp.keilycattle.com](https://erp.keilycattle.com)     | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/keily-cattle/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/keily-cattle/actions/workflows/build_and_deploy.yml)
| [olivetree.software](https://olivetree.software)       | Enterprise   | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/stauffer-enterprises/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/stauffer-enterprises/actions/workflows/build_and_deploy.yml)
| [ws.cropdoc.report](https://ws.cropdoc.report)         | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/washington-street/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/washington-street/actions/workflows/build_and_deploy.yml)
| [sidney.cropdoc.report](https://sidney.cropdoc.report) | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/sidney-rudolph/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/sidney-rudolph/actions/workflows/build_and_deploy.yml)
| [shepherdspathway.org](https://shepherdspathway.org)   | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/shepherds-pathway/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/shepherds-pathway/actions/workflows/build_and_deploy.yml)
| [mtntrails.org](https://mtntrails.org)                 | Community    | 18.0    | [![Build and Deploy](https://github.com/Baker-Street-Network/mtn-trails/actions/workflows/build_and_deploy.yml/badge.svg)](https://github.com/Baker-Street-Network/mtn-trails/actions/workflows/build_and_deploy.yml)

### Local Modules
These are modules that are available to all installations.

| Module                   | Version(s)    | Notes             |
| ------------------------ | ------------- | ----------------- |
| [base-accounting-kit](https://github.com/Baker-Street-Network/base-accounting-kit)           | 18.0       | Adds advanced accounting features to the Community edition.              |
| [muk-web-theme](https://github.com/Baker-Street-Network/muk-web-theme)                       | 18.0       | Adds an Enterprise-like theme to the Community edition.                  |
| [telerik-reporting-module](https://github.com/Baker-Street-Network/telerik-reporting-module) | 17.0, 18.0 | Requires the Telerik Reporting binary to be running.                     |
| [knowledge-scaffold](https://github.com/Baker-Street-Network/knowledge-scaffold)             | 17.0, 18.0 | Uses OpenAI to generate a list of questions from KB articles.            |
| [zip_fill](https://github.com/Baker-Street-Network/zip_fill)                                 | 17.0, 18.0 | Fills city and state from zip code. Add county and township from Mapbox. |

To install one of these modules, use the following command:
`git submodule add "https://github.com/Baker-Street-Network/telerik-reporting-module" .\addons\telerik-reporting-module`

A note on the `muk-web-theme` and the `base-accounting-kit`. Both of these have sub-folders, so you may want to check these out in their own addons folders, then include this in the Dockerfile's run command manually.

### Initializing an Instance
To create a new instance, follow the instructions in the [odoo-template repository](https://github.com/Baker-Street-Network/odoo-template).
