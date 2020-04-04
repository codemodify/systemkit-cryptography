# ![](https://fonts.gstatic.com/s/i/materialicons/bookmarks/v4/24px.svg) Cryptography
[![](https://img.shields.io/github/v/release/codemodify/systemkit-cryptography?style=flat-square)](https://github.com/codemodify/systemkit-cryptography/releases/latest)
![](https://img.shields.io/github/languages/code-size/codemodify/systemkit-cryptography?style=flat-square)
![](https://img.shields.io/github/last-commit/codemodify/systemkit-cryptography?style=flat-square)
[![](https://img.shields.io/badge/license-0--license-brightgreen?style=flat-square)](https://github.com/codemodify/TheFreeLicense)

![](https://img.shields.io/github/workflow/status/codemodify/systemkit-cryptography/qa?style=flat-square)
![](https://img.shields.io/github/issues/codemodify/systemkit-cryptography?style=flat-square)
[![](https://goreportcard.com/badge/github.com/codemodify/systemkit-cryptography?style=flat-square)](https://goreportcard.com/report/github.com/codemodify/systemkit-cryptography)

[![](https://img.shields.io/badge/godoc-reference-brightgreen?style=flat-square)](https://godoc.org/github.com/codemodify/systemkit-cryptography)
![](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)
![](https://img.shields.io/gitter/room/codemodify/systemkit-cryptography?style=flat-square)

![](https://img.shields.io/github/contributors/codemodify/systemkit-cryptography?style=flat-square)
![](https://img.shields.io/github/stars/codemodify/systemkit-cryptography?style=flat-square)
![](https://img.shields.io/github/watchers/codemodify/systemkit-cryptography?style=flat-square)
![](https://img.shields.io/github/forks/codemodify/systemkit-cryptography?style=flat-square)

#### Advanced fork of the Go/Cryptography
#### Supported: Linux, Raspberry Pi, FreeBSD, Mac OS, Windows, Solaris

# ![](https://fonts.gstatic.com/s/i/materialicons/bookmarks/v4/24px.svg) Install
```go
go get github.com/codemodify/systemkit-cryptography
```
# ![](https://fonts.gstatic.com/s/i/materialicons/bookmarks/v4/24px.svg) API

&nbsp;																| &nbsp;
---     															| ---
NewAES256Cryptor(`text` string) (*AES256Cryptor, error) | 
Decrypt(`cipherbytes` []byte, `aes256Cryptor` *AES256Cryptor) |
deriveKey(`aes256Cryptor` *AES256Cryptor) |
pkcs5Trimming(`encrypt` []byte) |
StringToMD5(`value` string) | 

# ![](https://fonts.gstatic.com/s/i/materialicons/bookmarks/v4/24px.svg) Usage
```go

```
> - ### for examples see `gocrypto/ssh/test`