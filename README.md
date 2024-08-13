## Generate 32 character master key

```bash
openssl rand -base64 24 | tr -d '\n' ; echo
```
