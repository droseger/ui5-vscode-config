# Config files for SAPUI5 development using VSCode

This configuration is intended mainly for use with versions of the SAPUI5 SDK prior to 1.76.

Simply extract the `resource` folder to `../ui5/<version>/` (relative to your ui5 project),
change the `<strings>` accordingly, install NodeJS and execute `npm install` in this folder.

For details on how to use this repo, see the [ui5-tooling documentation](https://sap.github.io/ui5-tooling/).

Starting with SAPUI5 1.76, you might also [consume SAPUI5 libraries directly via npm](https://sap.github.io/ui5-tooling/pages/SAPUI5/). In this case, the package `ui5-middleware-servestatic` isn't needed anymore.
