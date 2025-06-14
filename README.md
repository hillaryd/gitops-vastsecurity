# gitops-frappe

## Frappe Custom Image Build

The custom image is built using the `ci/build.env` file and the `ci/apps.json` file. The `ci/build.env` file contains the build configuration and the `ci/apps.json` file contains the list of apps to be installed. The `ci/build.env` file is used to generate the build arguments for the Docker build and the `ci/apps.json` file is used to generate the `APPS_JSON_BASE64` variable which is used to install the apps during the Docker build.
