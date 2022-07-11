PRW -  Lotuscoin Core integration/staging tree (yes tree)
=====================================

This repo is WOODCORE without the SSL1.1 additions, for older systems with OPENSSL 1.0

This project is a fully armed and operational bitcoin-core ported to the lotuscoin network.  

Dedicated to Sipa, Nullc, and Coblee.  Props and Kudos.  

Three tasks have made this port complete:

1) Skein hash function for Proof Of Work inserted
2) prime256r1 for ECDSA signatures (including backport to OpenSSL and removal of libsecp256k1)
3) Logarithmic supply curve for long-term economics

Voila - we now have a segwit-enabled lotuscoin client in place for those who would like to use it.

If you are looking for the Funkenstein-1.0.1 client which has been the backbone of the network for years:

https://github.com/funkshelper/lotuscoin.git

Other clients including Lotuscoin-minimal and Fo-Realz-Lotuscoin are also available.  





https://Lotuscoin.org

What is Lotuscoin?
----------------


Lotuscoin is a digital currency that enables instant payments to
anyone, anywhere in the world. Lotuscoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Lotuscoin Core is the name of ONE open source
software which enables the use of this currency, built from the code made by the 
wizards of the bitcoin-core team. 

Lotuscoin differs from its predecessors bitcoin, dogecoin, ethereum, et al.
in that it is designed to have a money supply curve which remains tenable over many decades.
Litecoin and Bitcoin employ an exponentially decreasing reward drop which means that miners 
are likely to flee, unless fees grow exponentially, in which case users will flee.  
Ethereum and Dogecoin include a non-decreasing subsidy which means no cap on the money supply.  
Lotuscoin has a capped money supply but a slowly decreasing supply in which half the supply will
not be released for 200 years, and the full supply would take more than 200 million years to be released.

For more information, as well as an immediately useable, binary version of
the Lotuscoin Core software, see [https://Lotuscoin.org](https://Lotuscoin.org).

Development Process
-------------------

Developer IRC can be found on Freenode at #Lotuscoin-dev and #Lotuscoin.

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



