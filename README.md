# pkcs11-proxy

pkcs11 network proxy with macOS compatability (to enable code signing with an hardware token)

## Build

```sh
# One Time
brew install openssl@1.1 cmake
# Every build
rm -rf build; mkdir build; cmake ..
make
```

The `build/macOS.tar.gz` file will contain compiled binaries.
