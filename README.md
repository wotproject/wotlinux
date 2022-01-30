# wotlinux
A minimal, security hardened Linux OS

# Security when building

When building the programs, the following environment variables are set:

```bash
export LDFLAGS="-Wl,-z,now -Wl,-z,relro"
export CFLAGS="-fPIE -fstack-protector-all -D_FORTIFY_SOURCE=4"
```
