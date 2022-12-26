PRW -  Lotuscoin Core integration/staging tree (yes tree)
=====================================

This repo is LotusCore without the SSL1.1 additions, for older systems with OPENSSL 1.0

This project is a fully armed and operational bitcoin-core ported to the lotuscoin network.  

Dedicated to Sipa, Nullc, and Coblee.  Props and Kudos.  

Three tasks have made this port complete:

1) Skein hash function for Proof Of Work inserted
2) prime256r1 for ECDSA signatures (including backport to OpenSSL and removal of libsecp256k1)
3) Logarithmic supply curve for long-term economics

Voila - we now have a segwit-enabled lotuscoin client in place for those who would like to use it.

If you are looking for the Paro-1.0.1 client which has been the backbone of the network for years:

https://github.com/pamenarti/lotuscoin.git

Other clients including Lotuscoin-minimal and Fo-Realz-Lotuscoin are also available.  

the Lotuscoin Core software,

Development Process
-------------------

Dependencies:   (listed w/ debian/ubuntu names)

build-essential
autoconf
libboost-all-dev libcurl4-openssl-dev libdb-dev qt-sdk libminiupnpc-dev
openssl
libzmq3-dev
libevent-dev
libssl-dev
libminiupnpc-dev
libtool
libdb++-dev
qttools5-dev-tools




