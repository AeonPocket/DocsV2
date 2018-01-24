---
layout: default
---


# [](#about)AEON Pocket
***

AEON Pocket is a secure web wallet for AEON Coin. The design of AEON Pocket is heavily inspired by [mymonero](http://mymonero.com/) much like AEON is from Monero.



# [](#techinical)Technical Design

***

AEON Pocket is an [Angular](https://angularjs.org/) based javascript app with a [Laravel](https://laravel.com/) based server implementation.

The [Web-Wallet Repository](https://github.com/AeonPocket/web-wallet) contains the source code and the documentation can be found [here](php-wallet).


AEON Pocket communicates to the AEON Daemon by a custom lightweight wallet implementation. This enables AEON Pocket to ensure that it can act as a wallet without ever allowing your _Private Spend Key_ to leave your browser.

The [RPC Repository](https://github.com/AeonPocket/rpc) contains the source code and the documentation can be found [here](rpc).


# [](#hosting)Hosting
*** 
AEON Pocket aims to be simple to host and hence we made a Docker image available.

More info on how to host can be read [here](docker-host)

At the moment of authoring this document all the hosting charges for AEON Pocket are incurred by the devs.


# [](#contact)Contact
*** 

Twitter : [@AEONPocket](http://twitter.com/aeonpocket)