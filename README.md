### Relevant Articles:

- [Using Custom User Providers with Keycloak](https://www.baeldung.com/java-keycloak-custom-user-providers)


docker run -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin -v "`pwd`/build/libs:/opt/jboss/keycloak/standalone/deployments" jboss/keycloak