# How to Setup Stellar


## install Stellar

https://github.com/stellar/stellar-core/blob/master/INSTALL.md

please install dependencies according to the above link. One can then go Stellar GitHub to install from source code. I did some small change of original installation guide to make it run on Ubuntu.


    git clone https://github.com/stellar/stellar-core.git
    cd stellar-core
    git submodule init
    git submodule update
    Type ./autogen.sh.
    Type ./configure (If configure complains about compiler versions, try CXX=clang-3.5 ./configure or CXX=g++-4.9 ./configure or similar, depending on your compiler.)
    Type sudo make 
    Type sudo make install to install.



## configure Stellar

https://github.com/stellar/stellar-core/blob/master/README.md

