# Blockchain-Wallets

Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them by integrating the Ethereum blockchain network into the application in order to enable customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

---

## Technologies

This project leverages python 3.9 with the following package:

* [VSCode](https://code.visualstudio.com/) - Code editor redefined and optimized for building and debugging modern web and cloud applications.

* [Pandas](https://pandas.pydata.org/) - Entry point, open source data analysis and manipulation tool.

* [Streamlit](https://streamlit.io/) - Open-source app framework for Machine Learning and Data Science teams.

* [haslib](https://docs.python.org/3/library/hashlib.html) - Secure hash and message digest algorithm library.

* [Web3.py](https://web3py.readthedocs.io/en/stable/overview.html) - A Python library for connecting to and performing operations on Ethereum-based blockchains.

* [ethereum-tester](https://pypi.org/project/ethereum-tester/0.1.0a4/) - A Python library that provides access to the tools we’ll use to test Ethereum-based applications.

* [mnemonic](https://pypi.org/project/mnemonic/) A Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.

* [bip44](https://pypi.org/project/bip44/) - A Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

* [Ganache](https://trufflesuite.com/ganache/) - ​​A program that allows you to quickly set up a local blockchain, which you can use to test and develop smart contracts.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
pip install web3==5.17
pip install eth-tester==0.5.0b3
pip install mnemonic
pip install bip44
```

Next, import required libraries and dependencies.

```python
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
```

---

## Usage

To use this application simply clone the repository and run the **fintech_finder.py** with:

```python
  fintech_finder.py
```
### How to run it locally using following commands
```
pip install streamlit
```
from your local terminal clone the repo then type
```
streamlit run fintech_finder.py
```

---

## Contributors

This project brought to you by Agnes.

---

## License
[MIT](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)