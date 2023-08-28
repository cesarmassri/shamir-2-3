# shamir-2-3

Shamir 2-3

Splits your BIP39 secret phrase into 3 parts, of which any 2 are necessary to recover the secret.
Each part consists of a BIP39 secret phrase.

The x-coordinate required by the Shamir algorithm is stored within the checksum of each phrase.

The phrase is 12 (or 24) words long.
