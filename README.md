# gpg-guide

### Setup

##### Generate a new keypair

```
gpg --gen-key
```

##### Generate a revocation certificate

```
gpg --gen-revoke
```

### Key inspection

##### List keys

```
gpg --list-keys
```

##### List keys and signatures

```
gpg --list-sigs
```

##### List and check key signatures

```
gpg --check-sigs
```

##### List keys and fingerprints

```
gpg --fingerprint
```

##### List secret keys

```
gpg --list-secret-keys
```

### Signatures and verification

##### Make a signature

```
gpg --sign
```

##### Make a clear text signature

```
gpg --clearsign
```

##### Make a detached signature

```
gpg --detach-sign
```

##### Verify a signature

```
gpg --verify
```

### Encryption and decryption

##### Encrypt data

```
gpg --encrypt
```

##### Encryption only with symmetric cypher

```
gpg --symmetric
```

##### Decrypt data (default)

```
gpg --decrypt
```

### Key Signing

##### Sign a key

```
gpg --sign-key
```

##### Sign a key locally

```
gpg --lsign-key
```

##### Sign or edit a key

```
gpg --edit-key
```

### Key Servers

##### Export keys

```
gpg --export
```

##### Export keys to a key server

```
gpg --send-keys
```

##### Import keys from a key server

```
gpg --recv-keys
```

##### Search for all keys on a key server

```
gpg --search-keys
```

##### Update all keys from a key server

```
gpg --refresh-keys
```

##### Import/merge keys

```
gpg --import
```

### Cleanup

##### Remove keys from the public keyring

```
gpg --delete-keys
```

##### Remove keys from the secret keyring

```
gpg --delete-secret-keys
```
