# errisy-session

## a simple session middleware for [errisy-server](https://www.npmjs.com/package/errisy-server)

This is an simple implementation to session data in cookie.

The session object is stringified in the server and kept in the session field of cookie via asymmetric encryption methed (aes-256-gcm).

For a light weight small website, this is an easier solution as it does not depend on server side database or in memory storage.

Please add this session middleware as the first middleware when used in domainmiddleware [errisy-server](https://www.npmjs.com/package/errisy-server).

## update 1.0.5
fixed up decryption bug. now working well.
