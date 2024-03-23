# sops
A repo test out the encryption of a K8s Secret manifest such that the sensitive values can be written to SCM (in an encrypted manner.

```bash
$ sops --encrypt -i ./secret2.yaml
$ sops --decrypt secret2.yaml > secret2-decrypted.yaml
$ sops <sops_encrypted_file> 
```
