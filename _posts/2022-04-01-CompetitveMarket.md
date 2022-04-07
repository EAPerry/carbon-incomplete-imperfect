---
layout: post
title: A Model of Competitive Generation
published: true
---

The model of perfectly competitive generation follows closely from [Fowlie, Petersen, and Reguant (2021)](https://www.aeaweb.org/articles?id=10.1257/pandp.20211073). In a scenario with perfectly competitive generation, the resulting allocation uniquely maximizes welfare. Using this fact, we look for the generation that will maximize the sum of total welfare in each market. Let $$q_{ir}$$ be the power generation of plant $i$ for region $$r$$. Note here that plant $$i$$ is not necessarily located in region $$r$$, but that it generates this power to be sold in region $$r$$’s wholesale (day-ahead) market. 

## Setting up the objective function

We assume that demand for power in these wholesale markets is linear. Specifically, the inverse demand function for region $$r$$ at time $$t$$ is,

$$p_{rt} = \alpha_{rt} - \beta_{rt} Q_{rt},$$

where $$p_{rt}$$ and $$Q_{rt}$$ are the price and quantity demanded in the market. In equilibrium, the quantity demanded must equal the quantity supplied. That is, 

$$Q_{rt} = \sum_{i \in N} q_{ir}.$$

Total surplus in the markets is the sum of the area under the demand curves from each market minus the sum of all marginal costs. Then the sum of the area under the demand curves in each market is

$$\sum_{r \in R} \frac{1}{2}\left( 2\alpha_{rt} - \beta_{rt} \sum_{i \in N} q_{ir}\right) \sum_{i \in N} q_{ir}$$



## Setting up the constraints
