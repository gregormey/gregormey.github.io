---
title: Outsourcing of product development
tags:
- DDD
- product management
- aglie
---
I think outsourcing is a valid option to compensate missing inhouse abilities, but the decision for outsourcing always comes with a certain risk. In my career i have seen companies that deal with outsourcing quite differently. 
<!-- more -->

Sometimes companies try to outsource as much product development as possible for cost reasons. Others suffered from the [not invented here syndrome](https://en.wikipedia.org/wiki/Not_invented_here). For some time i even worked for a company whose core business was to do development as a service for other companies. I like to share my experiences with that here in detail.    

## Know your core domain
The most important lesson i have learned so far is that outsourcing always means to give up control. I think the question companies should be able to answer, when they consider to outsource product development, is for which area of their business they can afford to give up control.
 
I think it is a good idea to always keep control of the [drivers of the business model](http://www.startuplessonslearned.com/2008/09/three-drivers-of-growth-for-your.html), because here it is crucial to be stay flexible and to align as fast as possible when it is needed. In that area the entrepreneurial risk is very high. 

But today companies need to deal with lots of different domains beside their core business. In a product development company that could be also:

- Marketing
- HR
- Public Relations
- Community Management

Domain Driven Design differs between three different types of [domains](http://blog.zenmodeler.com/enterprise-design/2012/05/29/domain-driven-design-distillation-support-generic-and-core-domain.html):  

#### Generic Domain
 A generic domain is one that is universally well-known, without any need for specialization in the core domain.

#### Supporting Doamin 
A support domain is a part of the domain that indirectly supports the core domain without actually belonging to it.

#### Core Domain 
The core domain is the part of the domain most closely associated with the strategy of the company.

It is not a big deal to outsource issues in a generic domain. It is a common practise to use third party software for topics like payroll or accounting. [Datev](https://www.datev.com) is one widespread example. While outsourcing in a core domain is not advisable, it can make sense in a supporting domain. Here a company should consider, if it is worth to take a risk to get one or more of the following advantages from a external partner:

- Availability
- Additional competences
- Reduced entrepreneurial risk, because permanently hiring of new employees is not required    

## Keep control
As already mentioned the risk of outsourcing is about the loss of control. Agile product management offers several methods to reduce that loss of control. That means it is important that an external partner is willing to establish an agile process with you. Of course this usually means that you shift some risk to the partners side, but in the end it is just about dividing the risk as fair as possible.  

Boris Gloger describes in his book ["Der agile Festpreis"](https://www.amazon.de/agile-Festpreis-Leitfaden-erfolgreiche-Projekt-Verträge/dp/3446432264) how to set up an agile contract with an external partner. In my opinion it does not matter if you choose this or a less official way, the important points are as follow:

- An iterative process including regular reviews (e.g. Scrum).
- After every iteration the customer has the opportunity to stop the project or to give the job for the next iteration instead of just paying for time and material. 
- The whole process has to aim for delivering something valuable at the end of every iteration, which is usually working software.
- There is the possibility to adjust the requirements at least after every iteration to benefit from the learned during the work.
- The partner commits to reach a goal with you and not to just implement requirements.
- Direct communication is always possible.

## How to choose an external partner
It is literally impossible to choose a good external partner just by the price. The price is a factor, but i think it should be the last attribute to look at. Hence there must be a different way to objectively evaluate a partner. In one of my last projects we did it with a value benefit analysis.

### Value benefit analysis
In the first step we had to find criteria were we could benefit from an external partner or which are required to lower the risk for us beside the price. In our case it were the following: 

- Availability
- Competence
- Process control
- Risk share
- Quality

Then we assembled a questionnaire with questions we considered as important for every criteria. Download the full document [here](./questionnaire.xlsx).

For every question we also formulated an ideal answer. We weighted every question on a scale from 1 (not important) to 10 (very important) for us. To be able to transform the weighting to a score we calculated the ratio in percent of every question from the total amount of weighting points.

{% asset_img weighting.png calculate weighting in percent %}

A side effect was that with the accumulated points per criteria, we were able to see which criteria was the most important for us. 
 
The questionnaire was send to the candidates, so that they could answer. After we got all the answers we ranked them on a scale from 1 (not what we expect) to 10 (very close to the ideal answer). In combination with the weighting in percent we were now able to generate a score per partner from 1 to 10.

{% asset_img value.png calculate value score %}

In the last step we were able to find the best partner by the ratio between the price and the achieved score.

{% asset_img ratio.png find partner by ratio %}

## Conclusion 
