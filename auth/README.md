# Authentication

**WARNING: No authentication tokens or keys should be committed to source control!**

## Tokens

Tokens are stored in `TOKEN.env` and can be parsed with `dotenv`.

## Generate private-public key pairs

Generate the private key:

`openssl genrsa -out private.pem 2048`

Generate the public key:

`openssl rsa -pubout -in private.pem -out public.pem`
