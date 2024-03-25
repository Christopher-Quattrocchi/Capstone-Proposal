Project Proposal Template
Name of Student: Chris Quattrocchi

Name of Project: I can't think of a name yet. It's a crypto bot. Details being ironed out. 

Project's Purpose or Goal: This crypto bot will connect to the user's wallet (currently just metamask, will probably expand) and to the dydx crypto exchange. It will be able to open and close trades dynamically based on market conditions. It will have the option to be hosted in the cloud, and it will have the option to notify the user through text messages/telegram messages. It will use statistical arbitrage as its main trading strategy, though I would like to include more advanced features as well

List the absolute minimum features the project requires to meet this purpose or goal: Connect metamask wallet to dydx on the sepolia test network, and make trades based on a statistical arbitrage strategy. User can set paramenters. Front end functional.

What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? Made in python, using metamask wallet and the dydx v3 API. Here are the dependencies:
aiohttp==3.8.1
aiosignal==1.3.1
async-timeout==4.0.2
atomicwrites==1.4.1
attrs==22.1.0
base58==2.1.1
bitarray==2.6.0
certifi==2022.12.7
charset-normalizer==2.1.1
click==8.1.3
cytoolz==0.11.2
dateparser==1.0.0
distlib==0.3.6
dydx-v3-python== (CURRENT: Had to update this to get it to work with sepolia network)
ecdsa==0.16.0
eth-abi==2.2.0
eth-account==0.5.9
eth-hash==0.5.1
eth-keyfile==0.5.1
eth-keys==0.3.4
eth-rlp==0.2.1
eth-typing==2.3.0
eth-utils==1.9.5
filelock==3.8.2
frozenlist==1.3.3
hexbytes==0.3.0
idna==3.4
importlib-metadata==0.23
ipfshttpclient==0.8.0a2
jsonschema==4.17.3
lru-dict==1.1.8
more-itertools==9.0.0
mpmath==1.0.0
multiaddr==0.0.9
multidict==6.0.3
mypy-extensions==0.4.3
netaddr==0.8.0
numpy==1.23.5
packaging==22.0
pandas==1.5.2
parsimonious==0.8.1
pathspec==0.10.3
patsy==0.5.3
platformdirs==2.6.0
pluggy==0.13.1
protobuf==3.19.5
py==1.11.0
pycodestyle==2.10.0
pycryptodome==3.16.0
PyJWT==2.6.0
pyrsistent==0.19.2
pytest==4.6.11
python-dateutil==2.8.2
python-decouple==3.6
pytz==2022.6
pytz-deprecation-shim==0.1.0.post0
regex==2022.10.31
requests==2.28.1
requests-mock==1.6.0
rlp==2.0.1
scipy==1.9.3
six==1.16.0
statsmodels==0.13.5
sympy==1.6
toml==0.10.2
tomli==2.0.1
toolz==0.12.0
tox==3.13.2
tzdata==2022.7
tzlocal==4.2
urllib3==1.26.13
varint==1.0.2
virtualenv==20.17.1
wcwidth==0.2.5
web3==5.31.3
websockets==9.1
yarl==1.8.2
zipp==3.11.0


If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.  

I want it to be able to interact with a variety of wallets, including hardware/privacy oriented wallets. I want it to be able to connect to a variety of real and test networks, and I want it to be able to connect to multiple exchanges. I want it to use statistical arbitrage but other trading methods as well, to the extent that this is realistic. Something like a beginner and advanced mode, in beginner mode only statistical arbitrage is available and you can't use much leverage, but for advanced users, they can click a button and access more advanced but risky options. I want the UI to be slick, and to display graphs showing the performance of the user's trades and coins over the last x hours, days, whatever. The app should be able to be hosted on a cloud, but not required. Should be able to interact with the user's phone, AND ALSO take orders from the phone.

What additional tools, frameworks, libraries, APIs, or other resources will these additional features require? I'm not sure

Is there anything else you'd like your instructor to know?  NA
