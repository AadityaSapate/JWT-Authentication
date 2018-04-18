# JWT-Authentication

1. client sends 'email' and 'password' ia POST request to server

2. server sends back {"token":"THETOKEN"} or status 401

3. client makes requests to protected endpoints with the header "Authorization: THE TOKEN"

4. server either accepts the token or sends status 401 (then start again from 1.)