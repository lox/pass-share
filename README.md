# Share a Passphrase Securely with Shares

The approach uses [Shamir's threshold secret sharing scheme](http://en.wikipedia.org/wiki/Shamir's_Secret_Sharing) to split an intermediate key between several of my family members. There are 3 pieces generated and a consensus of at least 2 pieces is required. The intermediate key can then be used to decrypt the actual passphrase, which is located (encrypted) on a print-out in my desk.

Once you decrypt the passphrase, you can use that passphrase to access my 1password Vault.
