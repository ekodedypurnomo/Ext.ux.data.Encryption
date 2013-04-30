### Ext.ux.data.Encryption

### Ext.ux.data.proxy.EncryptedLocalStorage

This demo showcases ExtJS using client-side JavaScript AES encryption and SHA3 hashes.

The Encryption class stores a SHA3 hash in a private in-memory var.
The EncryptedLocalStorage proxy class has an api we augment in from the Encryption class.

The demo stores an encrypted string to localStorage for password comparison during login.
The demo uses the proxy extension to store encrypted data to localStorage.

[Overview](http://davepatten.net/example/Ext.ux.data.Encryption)

[Live Demo](http://davepatten.net/example/Ext.ux.data.Encryption/demo)