This repo is a copy of golang std crypto on tag go1.13.6, hash 14b79df428fd. 

## modified

- elliptic/elliptic.go
- elliptic/elliptic_test.go
- elliptic/p224.go
- elliptic/p256.go
- elliptic/p256_asm.go
- elliptic/p256_asm_amd64.s
- x509/x509.go
- x509/root_cgo_darwin.go
- tls/common.go
- tls/key_schedule.go
- copy go/internal to internal

## added
- elliptic/secp256k1_test.go
- elliptic/secp256k1.go
- elliptic/sm2p256v1.go

## Reference

- [crypto/elliptic: generalize elliptic.Curve to allow A != -3](https://github.com/golang/go/pull/26873/files)