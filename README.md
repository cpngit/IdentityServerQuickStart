Using IdentityServer4 to represent its works.

To check how IdentityServer works do it:
-> try to connect to IdentityServer when it is not running (unavailable)
-> try to use an invalid client id or secret to request the token
-> try to ask for an invalid scope during the token request
-> try to call the API when it is not running (unavailable)
-> don’t send the token to the API
-> configure the API to require a different scope than the one in the token

Refernece:
https://identityserver4.readthedocs.io/en/latest/quickstarts/1_client_credentials.html
