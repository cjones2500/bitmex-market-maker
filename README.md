Getting Started

Bitmex Market Maker with a simple strategy that uses the TestNet testing suite. This strategy is a simple one to layer the book on both sides. The pip requirements file is included in the repo. 

A small number of Test bitcoins are already associated with a test account that is hardcoded (not good practice, but this account is only used for testing). Additional test bitcoins can be added by:
1. Creating a [Testnet BitMEX Account](https://testnet.bitmex.com) and [depositing some TBTC](https://testnet.bitmex.com/app/deposit).

The settings for this specific account are given in the _setttings_base.py file. In order to run this simple market making stategy on the test account, call the following in the command line:

> $ ./marketmaker 

