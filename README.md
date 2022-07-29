# The OpenID Connect Handbook

This repository is a sample Node.js and Express web application that handles user sign in through OpenID Connect. This application was created to help the community learn about OpenID Connect and OAuth 2.0 and is part of The OpenID Connect Handbook.

You can find the handbook here: https://auth0.com/resources/ebooks/the-openid-connect-handbook

Have fun!


docker run -p 8080:8080 --name oidc-webapp-keycloack -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:19.0.0 start-dev
