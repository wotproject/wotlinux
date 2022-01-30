# wotlinux

![GitHub Repo stars](https://img.shields.io/github/stars/wotproject/wotlinux#8e0ac7)
![GitHub issues](https://img.shields.io/github/issues/wotproject/wotlinux?color=%238b20e3)
![GitHub commit activity](https://img.shields.io/github/commit-activity/w/wotproject/wotlinux?color=%238e0ac7)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/wotproject/wotlinux?color=%238b20e3)

A minimal, security hardened Linux OS

# Security when building

When building the programs, the following environment variables are set:

```bash
export LDFLAGS="-Wl,-z,now -Wl,-z,relro"
export CFLAGS="-fPIE -fstack-protector-all -D_FORTIFY_SOURCE=4"
```
