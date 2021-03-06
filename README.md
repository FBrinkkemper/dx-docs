<p align="center">
  <img width="350px" src="http://dutchx.readthedocs.io/en/latest/_static/DutchX-logo_blue.svg" />
</p>

# DutchX Documentation
The Dutch Exchange (DutchX) is a fully decentralized exchange, which allows 
**everyone** to add any trading token pair.

It uses the **[Dutch auction](https://en.wikipedia.org/wiki/Dutch_auction)** 
principle, to prevent the problems that other exchanges are experiencing (such
as front running) getting a fairer ecosystem for everyone to use.

There is no restriction besides the fact that tokens must be 
[ERC20](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md) compliant.

## Documentation
Read the last documentation in:
* [http://dutchx.readthedocs.io/en/latest/](http://dutchx.readthedocs.io/en/latest/)

It's a work in progress, so comments, suggestions, and colaborations are really 
welocomed.

## Collaboration
The DutchX is made by and for the comunity, with the goal of having a fairer standard
to exchange any kind of token.

Meet the comunity in the gitter channel!
* https://gitter.im/gnosis/DutchX

# Generate the doc
```bash
pip3 install -r requirements.txt
make html
```