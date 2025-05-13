## GPG Commit

1. List Secret Keys

```bash
gpg --list-secret-keys --keyid-format LONG
```

2. List Public Keys

```bash
gpg --list-keys --keyid-format LONG
```

3. Export Public Keys

```bash
gpg --armor --export <key id>
```

4. 上传公钥

```bash
gpg --send-keys <key id>
```