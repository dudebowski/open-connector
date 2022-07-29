# The OpenID Connect Handbook

This repository is a sample Node.js and Express web application 

This application is a solution for the excellent [The OpenID Connect Handbook](https://auth0.com/resources/ebooks/the-openid-connect-handbook)
of auth0, but it uses keycloak i.o Auth0. 

Trying to use both platforms will give you a better understanding of openID connect

## Run keycloack
 For setting up keycloack io Auth0 you can run keycloak in a docker container.
 Just run 

```bash
docker run -p 8080:8080 --name oidc-webapp-keycloack -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:19.0.0 start-dev
```

The [getting started documentation](https://www.keycloak.org/getting-started/getting-started-docker) will explain how to set up keycloak.

## Environment

You need a .env file with these entries

``` environment
OIDC_PROVIDER=localhost:8080/realms/<your_realm_name>
CLIENT_ID=<your_client_id>
```

## 

Enter `npm start` to run the application.