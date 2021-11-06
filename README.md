# [FinTech_Module_19_Challenge](https://github.com/toniahurst/FinTech_Module_19_Challenge)

# Background

In this challenge, we acted as a fintech engineer for a large, global banking interest. As lead developer for the decentralized finance team, we built a blockchain-based ledger system, complete with a user-friendly web interface to transfer money between senders and receivers (see Fig. 1). The app is also able to verify the integrity of the data in the ledger rendering an "output" true if the chain is valid (see Fig. 2).


## Figure 1
Fig. 1: The blockchain and ledger

![Fig 1 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-1.png)


Fig. 2: The validated chain produces a "true" result

![Fig 2 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-2.png)


![Fig 3 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-3.jpeg)


![Fig 4 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-4.jpeg)


![Fig 5 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-5.jpeg)


[To download a movie version of the blockchain exercise, click here:](https://github.com/toniahurst/FinTech_Module_18_Challenge/blob/main/Screen%20Recording%202021-11-01%20at%201.16.25%20PM.mov)

## Technologies

This program uses Python 3.7.10, Anaconda version 4.10.3, Visual Studio Code 1.61.0 and Streamlit, version 0.84.2. It was written on macOS Catalina 10.15.7.

# Other Imports
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3.auto.infura.kovan import w3
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy

## Usage
To use this app, you will need to download to a computer running Streamlit. 

## Contributors

Antonia Hurst

## License
Copyright (c) 2015-2021 Project Jupyter https://github.com/jupyterlab/jupyterlab/blob/master/LICENSE



