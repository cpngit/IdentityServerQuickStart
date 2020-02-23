Using IdentityServer4 to represent its works.

To check how IdentityServer works do it:
</br>
try to connect to IdentityServer when it is not running (unavailable)</br>
try to use an invalid client id or secret to request the token</br>
try to ask for an invalid scope during the token request</br>
try to call the API when it is not running (unavailable)</br>
don’t send the token to the API</br>
configure the API to require a different scope than the one in the token</br>
</br>
Refernece:</br>
https://identityserver4.readthedocs.io/en/latest/quickstarts/1_client_credentials.html
