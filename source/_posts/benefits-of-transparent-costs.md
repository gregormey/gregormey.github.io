---
title: Benefits of transparent costs
tags:
  - planning
  - product management
  - agile
date: 2016-09-14 11:14:25
---


In my last project I experienced the advantages of making development costs transparent, and I would like to share that here.
<!-- more -->
When a product is developed, the intention is to generate a specific result (outcome) with it. Development requires effort. Effort is the input to gain the outcome. It is essential knowing the actual investment for this in order to decide which direction to take.

Hence it is required to measure the input. This leads to the question of how is it actually possible to measure input properly?

Measuring input in [Story Points](https://www.mountaingoatsoftware.com/blog/what-are-story-points) or in men days are a widely known practice, but in the end these measurements are just an abstraction for what really matters for a company, which is the costs defined in money.

## Why not Story Points ?
Story points are an abstraction of time that is needed to deliver something, as described by Mike Cohn [Story Points Are Still About Effort](https://www.mountaingoatsoftware.com/blog/story-points-are-still-about-effort). 

But in my opinion, the question about how long it takes to deliver something is in the end more a question about how high the investment is for the delivery. It is hard to transform story points into money.

*Examples:*
- A team of 5 developers costs 25.000 € per sprint 
- The team has a velocity of 60 story points
- The smallest possible unit that can be estimated is 1 story point. E.g. a task of 1 hour effort is estimated as 1.
1 story point costs  416 € (25.000 € / 60)
- But the normal cost per development hour is just 62,5 € (25.000 € / 5 Developer / 10 working days / 8 working hours )

The example shows that Story points do not equal time and therefore they are not suitable to calculate investments.

## Why not just use time?
Development time is just one of several factors that needs to be taken into account for cost calculations. Others are:
- [Cost of delay](http://blackswanfarming.com/cost-of-delay/)
- Team Size, how many people are working in the team for a product
- Cost of operation

Besides that, time is usually conversely proportional to money. Getting something faster usually means it becomes more expensive. In very rare cases the development can be done faster with larger teams, larger teams are more expensive.  In most cases teams try to speed up the process by lowering the quality, but this will lead to follow up costs due to technical debts.

> "Greg Young on the other hand, has talked on several occasions about how technical debt is not necessarily bad. Businesses take loans all the time. They are a powerful tool to make an investment now, and pay for it later. It’s a fundamental aspect of our economy."
http://verraes.net/2013/07/managed-technical-debt/

## How to calculate costs
Beside the cost of delay it is important to know the general team costs, which are cost of operation plus personnel costs. For the final calculation, hardware costs comes on top. For different reasons it is true, that salaries of team members should not be transparent.

In my current team we use an average per team member which is calculated over the salaries of the whole department including leads. That means that the team costs are calculated by Number of Team Members * Average Department Salary.

The costs are calculated on a monthly basis but are reported on product cost centers. This is beneficial because the outcome for a company comes from the products and not from the teams, so we want to know the investment we have to take for a dedicated product.

We split the team costs based on a monthly effort ratio in percent per product. When a team has to handle more than one product like it is in my case, we track the time spend on a product with [Lego Time Tracking](http://www.filamentpd.com/lego-time-tracking/).
{% asset_img lego.jpg Lego Time Tracking %}

## How to forecast costs
It is not possible to forecast costs. You can only estimate costs, but estimates have the problem, that they are always wrong.
- http://noestimates.org/blog/

## How to estimate costs
As a Product Owner I design my roadmap around [goals](https://scrumburg.wordpress.com/2016/06/30/business-value-poker-and-more-po-tools-nr-3/) that bring valuable outcome. We also estimate the costs for the goals, so that I can see the ratio between input and outcome.

Before the question “How long does it take?” I prefer the question: “How much time do we want to give us to reach that goal?”
{% asset_img roadmap.png Roadmap with costs assigned to goals %}

## Conclusion
I think it is valuable for the process of product development to make costs transparent to everybody involved. With the knowledge of the cost everybody in a company can take important decisions or can better understand the motivation behind them.

It also prevents a team from wasting development time, because it makes everybody aware of the investment. In my experience this also helps to increase the commitment of everybody to their product.

With the above mentioned methods, product owners are able to define the relation between input and outcome and get a powerful tool to measure the return of investment for certain deliveries.

