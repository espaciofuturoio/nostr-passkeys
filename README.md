# Nostr and Passkey

Use NextJS and webauthn to sign nostr events.

## App

- You can create multiple wallets or accounts and send messages to nostr network.
- You can retrieve the private key and use any nostr client like https://iris.to/.
- Send a message and see the result. Example: for the public key npub1xqlnxhpg04m7hkplu6twugkzzmfqecg660fhnzvcx4d7l3hgyrzsfazk3c you can go to https://iris.to/npub1xqlnxhpg04m7hkplu6twugkzzmfqecg660fhnzvcx4d7l3hgyrzsfazk3c.

## References

1. [What Are Passkeys?](https://www.passkeys.com/what-are-passkeys#:~:text=Simply%20put%2C%20a%20passkey%20is,%2C%20remembered%2C%20or%20written%20down.)

Simply put, a passkey is a cryptographic key designed to replace passwords.

2. [pubKeyCredParams](https://w3c.github.io/webauthn/#dom-publickeycredentialcreationoptions-pubkeycredparams)

3. [Algorithms](https://www.iana.org/assignments/cose/cose.xhtml#algorithms)

4. [Available Algorithms](https://www.corbado.com/blog/webauthn-pubkeycredparams-credentialpublickey)
