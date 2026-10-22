Place the current ACME HTTP-01 challenge file in this directory.

The filename must be the token supplied by the ACME client, with no extension.
The file contents must be the exact key authorization supplied by the client.

Remove the challenge file after certificate issuance. Do not commit private keys,
ACME account credentials, or certificate private material to this repository.
