# Micro Exchange
## Description
As part of my master thesis I want to include a simple token micro-economy. I like to do a simple simulation where value is transferred between token owners to buy or sell a set of 5 different products. Basically what I want is to make an example with 5 to 10 different "agents" where each of them initiate with different amounts of tokens, something between 100 and 100000 tokens, after this I like to randomly set them lose to transact these values from one to another for a period of one day making transfers every minute for example. After the day is complete, I like to see statistics on a graph, then run it again for a following day and compare results. These are some of the parameters:

Number of agents 10 (each agent should have a name)
Number of products 5 (each product should have a name and price for agents to buy -and sell-)
For case 1 the Number of random transactions 1440 ( this is a random transaction for each minute in one day)
For case 2 the Number of random transactions 288 ( this is a random transaction for every five minutes in one day)
For case 3 the Number of random transactions 24 ( this is a random transaction for each hour in one day)

Token price = 1cent
Finally if possible, I like to simulate a behavior where a consumer is likely to spend more tokens or not based on the amount he or she has in the wallet. For someone who holds more tokens it is possible to spend more and viceversa. 

To start this I am using a tutorial from MESA which is very close to what I need to do. Part of the code is here and can be used. It just needs to be modified a little.
## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
### Prerequisites
Mesa program runs on python so make sure your computer has the following dependencies. 
```
- jupyter (Ipython interactive notebook)
- matplotlib (Python’s visualization library)
- mesa (this ABM library – if not installed)
- numpy (Python’s numerical python library)
```
### Installing required components and mesa
If you are not sure, mesa tutorial also provides a link where these can be downloaded
```
$ pip install -r https://raw.githubusercontent.com/projectmesa/mesa/master/examples/boltzmann_wealth_model/requirements.txt
```
Also make sure to install mesa with this line of code
```
$ pip install mesa
```
This can be done directly from a terminal screen or python. However, for my exercise I am using Jupyter notebook. This allows to include graphs and other functions that can be presented into an easy to read document. 
This can be done directly from a terminal screen or Python. However, for my exercise I am using Jupyter notebook. This allows to include graphs and other functions that can be presented into an easy to read document. 

###  Installing additional software for cloning 

Follow the steps below to have development environment running:
Clone the repository:
Clone the repository:
```
$ git clone https://github.com/olisystems/micro_exchange.git
```
After this you should be able to work on the project and modify the program as needed. 

Now we are on testing mode