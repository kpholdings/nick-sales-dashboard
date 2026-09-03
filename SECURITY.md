# Security

This is a public GitHub Pages repository. Never commit plaintext sales, customer, email, order, financial, credential, or access-password data.

`data.enc.json` must remain authenticated ciphertext generated outside this repository. Encryption is not permission to use a weak password: public ciphertext can be attacked offline. Rotate the encryption password and payload periodically and retire the public deployment when it is no longer needed.

Report suspected exposure privately to the repository owner; do not open an issue containing sensitive data.
