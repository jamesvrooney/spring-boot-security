# Simple example: OAuth2 Resource Server with Keycloak

## Contents
1. [Run keycloak locally in docker container](#run-keycloak-locally-in-docker-container)
2. [Keycloak running in docker](#keycloak-running-in-docker)
3. [Keycloak Setup: Create Realm](#keycloak-setup-create-realm)
4. [Keycloak Setup: Create Realm Role](#keycloak-setup-create-realm-role)
5. [Keycloak Setup: Create User](#keycloak-setup-create-user)
6. [Keycloak Setup: Assign Role to User](#keycloak-setup-assign-role-to-user)
7. [Keycloak Setup: Create Client](#keycloak-setup-create-client)
8. [Postman: Config Setup](#postman-config-setup)
9. [Postman: Get Access Token](#postman-get-access-token)
10. [Postman: Request and Response](#postman-request-and-response)
11. [Keycloak OAuth2 Endpoints](#keycloak-oauth2-endpoints)

### Run keycloak locally in docker container
```
docker compose up -d

```
### Keycloak running in docker
![Keycloak running in docker](images/01_keycloak_in_docker.png)
![Keycloak in browser](images/02_keycloak_browser.png)
![Keycloak Admin login](images/03_keycloak_admin_login.png)
![Keycloak Master Realm](images/04_keycloak_master_realm.png)

### Keycloak Setup: Create Realm
![](images/05_keycloak_create_realm_01.png)
![](images/06_keycloak_create_realm_02.png)
![](images/07_keycloak_realm_created.png)

### Keycloak Setup: Create Realm Role
![](images/08_keycloak_create_realm_role_01.png)
![](images/09_keycloak_create_realm_role_02.png)

### Keycloak Setup: Create User
![](images/10_keycloak_create_user_01.png)
![](images/11_keycloak_create_user_02.png)
![](images/12_keycloak_create_user_03.png)
![](images/13_keycloak_create_user_04.png)
![](images/14_keycloak_create_user_05.png)

### Keycloak Setup: Assign Role to User
![](images/15_keycloak_user_assign_role_01.png)
![](images/16_keycloak_user_assign_role_02.png)

### Keycloak Setup: Create Client
![](images/17_keycloak_create_client_01.png)
![](images/18_keycloak_create_client_02.png)
![](images/19_keycloak_create_client_03.png)
![](images/20_keycloak_create_client_04.png)
![](images/21_keycloak_create_client_05.png)

### Postman: Config Setup
![postman OAuth2 setup 01](images/22_postman_OAuth2_setup_01.png)
![postman OAuth2 setup 02](images/23_postman_OAuth2_setup_02.png)
![postman OAuth2 setup 03](images/24_postman_OAuth2_setup_03.png)
![postman OAuth2 setup 04](images/25_postman_OAuth2_setup_04.png)

### Postman: Get Access Token
![postman get access token 01](images/26_postman_get_access_token_01.png)
![postman get access token 02](images/27_postman_get_access_token_02.png)
![postman get access token 03](images/28_postman_get_access_token_03.png)
![postman get access token 04](images/29_postman_use_access_token_01.png)

### Postman: Request and Response
![postman make request to secure resource](images/30_postman_make_request_to_secure_resource_01.png)
![postman get response](images/31_postman_get_response.png)

### Keycloak OAuth2 Endpoints
[Online Docs: Keycloak OAuth2 Endpoints](https://www.keycloak.org/docs/latest/securing_apps/#available-endpoints)
[Local Docker Container: Keycloak OAuth2 Endpoints](http://localhost:8180/realms/JamesOAuth2HelloExample/.well-known/openid-configuration)