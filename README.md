# openssl-binaries
This repository provides openssl pre-compiled dynamic libraries (i.e. libssl.so and libcrypto.so)
for android architectures (i.e. armv7 and arm64) and linux desktop. 

## The compilation has been done for the following stable releases:

    Android:
        -openssl-1.0.2r
        -openssl-1.1.1c        
    
    Linux desktop:
        -openssl-1.1.1g

The source code of those releases can be found in the openssl website:

https://www.openssl.org/source/

# Note about Qt
If you intend to add these libraries to your Qt project, please take into
account that since the version 5.13 of Qt, you shouldn't use a previous version
of openssl-1.1.1.
