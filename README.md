<p align="center">
    <img src="https://github.com/codegouvfr/keycloakify-starter/workflows/ci/badge.svg?branch=main">
</p>

A starter/demo project for [Keycloakify](https://keycloakify.dev)

> NOTE: If you are only looking to create a theme and don't care about integrating it into an React app there
> are a lot of things that you can remove from this starter. [Please read this](#standalone-keycloak-theme).

# Quick start

```bash
yarn
yarn build-keycloak-theme # Build the theme one time (some assets will be copied to 
              # public/keycloak_static, they are needed to dev your page outside of Keycloak)
yarn start # See the Hello World app
# Uncomment line 15 of src/keycloak-theme/kcContext, reload https://localhost:3000
# You can now develop your Login pages.

# Think your theme is ready? Run
yarn build-keycloak-theme
# Read the instruction printed on the console to see how to test
# your theme on a real Keycloak instance.
```
