# [FinTech_Module_19_Challenge](https://github.com/toniahurst/FinTech_Module_19_Challenge)

# Background

In this challenge, we developed a disrutpive platform called Fintech Finder whose purpose was to locate, hire, and pay candidates them through an app integrated with the Ethereum block chain and using cryptocurrency for payment. We used two python files: fintech_finder.py (which is Streamlit compatible and provides the web interface for our app) and crypto_wallet.py (which conatins the Ethereum functions to process the transaction and is imported in fintech_finder.py). 

For the purpose of this simulation, we assumed the role of a customer who generates an Ethereum account instance using a menmonic seed phrase. We fetched and displayed ther account balance associated with our Ethereum account, calculated the value of the Etheruem transaction including the gas estimate for the work to be done, and digitally signed a transaction which we reviewd at the Kovan website. We validated the transaction by checking the hash code associated with the block chain transaction.

# Images
### Figure 1

![Fig 1 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-1.png)

### Figure 2
Fig. 2: The validated chain produces a "true" result
![Fig 2 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-2.png)

### Figure 3
![Fig 3 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-3.jpeg)

### Figure 4
![Fig 4 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-4.jpeg)

### Figure 5
Transaction Details - Sender to Receiver
![Fig 5 - ](https://github.com/toniahurst/FinTech_Module_19_Challenge/blob/main/images/Figure-5.jpeg)


# Technologies

This program uses Python 3.7.10, Anaconda version 4.10.3, Visual Studio Code 1.61.0 and Streamlit, version 0.84.2. It was written on macOS Catalina 10.15.7.

### Other Imports
##### import streamlit as st
##### from dataclasses import dataclass
##### from typing import Any, List
##### import os
##### import requests
##### from dotenv import load_dotenv
##### load_dotenv()
##### from bip44 import Wallet
##### from web3 import Account
##### from web3.auto.infura.kovan import w3
##### from web3 import middleware
##### from web3.gas_strategies.time_based import medium_gas_price_strategy

# Usage
To use this app, you will need to download to a computer running Streamlit. 

# Contributors

Antonia Hurst

# License
Copyright (c) 2015-2021 Project Jupyter https://github.com/jupyterlab/jupyterlab/blob/master/LICENSE



