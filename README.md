# micro_exchange
As part of my master thesis I want to include a simple token micro-economy. I like to do a simple simulation where value is transferred between token owners to buy or sell a set of 5 different products. Basically what I want is to make an example with 5 to 10 different "agents" where each of them initiate with different amounts of tokens, something between 100 and 100000 tokens, after this I like to randomly set them lose to transact these values from one to another for a period of one day making transfers every minute for example. After the day is complete, I like to see statistics on a graph, then run it again for a following day and compare results. These are some of the parameters:

Number of agents 10 (each agent should have a name)

Number of products 5 (each product should have a name and price for agents to buy -and sell-)

Number of random transactions 1440 ( this is a random transaction for each minute in one day)

Token price = 1cent

To start this I am using a tutorial from MESA which is very close to what I need to do. Part of the code is here and can be used. It just needs to be modified a little.

