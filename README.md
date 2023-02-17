# Nixio

This Git repository is a light fork of the [Nixio](https://github.com/Neopallium/nixio) library by Neopallium. This code will build using GCC 10 and has TLS support disabled to ensure that it builds in the presence of the latest OpenSSL. 

## Building

On Linux

```
git clone https://github.com/jangala-dev/nixio
cd nixio
sudo luarocks make
```

Homebrew on Mac

```
git clone https://github.com/jangala-dev/nixio
cd nixio
sudo luarocks make OPENSSL_INCDIR=/opt/homebrew/opt/openssl@3/include
```
