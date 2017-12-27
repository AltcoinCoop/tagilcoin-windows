TagilCoin 
================================

https://tagilcoin.org

Block explorer http://money.tagilcoin.org

Forum http://forum.tagilcoin.org

Windows and Linux binaries are available in the [Releases section](https://github.com/tagilcoin/tagilcoin-windows/releases/tag/latest).

To compile on Linux:

* install ubuntu 14 (highly recommended)
* apt-get install build-essential
* cd src/leveldb && make && make libleveldb.a libmemenv.a && chmod 755 *
* apt-get install libdb++-dev
* cd .. && make -f makefile.unix

![tank image](https://raw.githubusercontent.com/tagilcoin/tagilcoin-windows/master/tank.png)
