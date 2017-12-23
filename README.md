# MadCoin

MadCoin is a PoW + PoS-based cryptocurrency.

MadCoin uses libsecp256k1,
			  libgmp,
			  Boost1.55,
			  OR Boost1.57,  
			  Openssl1.01m,
			  Berkeley DB 4.8,
			  QT5 to compile


Block Spacing: 120 Seconds
Stake Minimum Age: 8 Hours

Port: 10882
RPC Port: 10883


BUILD LINUX (see the [Wiki](https://github.com/madcoin-project/madcoin/wiki/Unix-Build) for dependencies)
-----------
1) git clone https://github.com/madcoin-project/madcoin.git madcoin
2) cd madcoin/src

3) sudo make -f makefile.unix            # Headless madcoin

(optional)

4) strip madcoin

5) sudo cp madcoind /usr/local/bin



