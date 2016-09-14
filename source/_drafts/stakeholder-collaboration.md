---
title: Stakeholder collaboration
tags:
- DDD
- agile
---
The product owner is often meant to be the translator between the business language and the technical language of the developers. I think this is fundamental wrong. Instead of looking for a translator, teams should look for a [ubiquitous language](http://martinfowler.com/bliki/UbiquitousLanguage.html) that both sides can understand to enable direct communication.
<!-- more -->

Within the nearly 3 years working for Goodgame Studios i was responsible for a couple of different products. I would like to share my experience in terms of the collaboration with the stakeholders in two of these projects. Both were very different.

## The Marketing Backend
The marketing backend is a reporting tool for performance marketing KPI’s aggregated on monthly cohorts. The tool is used by marketing key account managers to steer marketing investments aligned on the life time value per customer.  

*Current status:*
Feature Freeze, the tool will be replaced by a self service solution.

*Stakeholder:*
Around 30 key account manager are using the tool on a daily basis. The requirements came from one key user per marketing team (SEA, Facebook, Display, RTA, TV).

*Development Team:*
- 7 Developers
- 1 QA 
- 1 Product Owner (me) 
- 1 Agile Coach  

## The Customer Relationship Management (CRM) System 
The task here is to provide customer data to third party systems that is required to communicate with our customers for marketing purposes. In  the first step the team focuses on email marketing.

*Current status:*
Implementation is still work in progress. Integration of further communication channels is planned.

*Stakeholder:*
Requirements are worked out together with two email marketing managers. Beside that developers who are integrating the data interface into their product are also considered as stakeholders.

*Development Team:*
- 3 Developers
- 1 Product Owner (me) 
- 1 Agile Coach

## Aspects of Collaboration

### Colocation

#### Marketing Backend
The development team was separated from the stakeholders. For some period of time the separation was even over different buildings. A casual exchange between them was only possible in official meetings. The stakeholder were always considered as disruptive and direct communication with them was avoided. 

#### CRM
Developers and stakeholder are sitting together on the same table. They consider themselves as one team. Issues related to the project are usually clearfield directly together in front of their computers. Both sides see what is their daily business which fosters a mutual understanding and the willing to work collaborative together.

#### Lessons learned
Direct communication between developers and stakeholders is essential for a successful product development.  The example show, that a locational separation of development team and stakeholders is a huge weakening of the communication flow.

### Integration of stakeholders into the scrum process

#### Marketing Backend
The requirements were brought to the team by [jira](https://www.atlassian.com/software/jira) tickets. Stakeholder and product owner met two times a week to refine the tickets. Beside that there was a bi-weekly prioritisation meeting also just between stakeholders and product owner. Information about requirements and prioritisation was communicated to the development team only by the product owner. There was no review meeting. Instead tickets were assigned back to the stakeholders after implementation for approval. Due to that developers got very delayed feedback and the backlog fastly growth to a size that was not manageable anymore.

#### CRM
Developers and stakeholders are doing their daily stand up together and share details about their daily work and potential problems. There is a review meeting after every stand up were the development team collects feedback about their current iteration from a extend circle of stakeholders. Stakeholders also participate to the sprint planning and developers ask them directly for advice. Priority and product strategy are discussed on a higher level with a goal oriented roadmap. The roadmap is also maintained by all involved people together on a regular basis.

#### Lessons learned
It is mandatory for the developers to get early feedback on what they are currently working on from their stakeholders. The product owner should never be a buffer between the team and the stakeholders, he should take care that both are connected and that they clarify issues on their own.

### Domain Knowledge sharing 

#### Marketing Backend
The domain “performance marketing” was for the development team a complete new topic. They had a lot of trouble to get into that. In some cases the developers even refused to learn something about their domain. They expected that the Product Owner will tell them what needs to be done. This lead to the fact that a lot of iterations were needed to come to a suitable solution.

#### CRM
Also in this case the domain was completely new for the team. But this time the team did not refused to learn. The developers had an interest in the work of the stakeholders. They often sit together and let the stakeholders explain their work. As a kick off we did a [story mapping](http://jpattonassociates.com/storymappingslides/) workshop. Here we worked out together the complete email marketing workflow. In that way basic question could be asked before we started the work.

{% asset_img story_mapping.png Story Mapping Workshop %}

#### Lessons learned
To solve the problems of the business it is required to understand the business needs. It is mandatory to inspire curiosity for the business side from the beginning on, so that developers are willing to learn what they needed to know for building their product. It is the task of a product owner to foster that process and again to connect both sides.

### Shared Commitment

#### Marketing Backend
The “big picture” and the value of the product for the company was not transparent for the development team. As a result of that the team withdraw to an area where they felt comfortable, in this case it was software architecture and design patterns. In the end this lead to over engineering. Stakeholder on the other side did not had  any appreciation for that, they were just wondering why implementation time was getting longer and longer. The amount of requested features was not adapted to the delivery time of the team and the backlog was growing and growing. Developers and stakeholders were not working on the same goal.

#### CRM
There is a clear communicated vision  for the team. Plannings on roadmap level or for the next sprint is always done in collaboration with the stakeholders. Necessary adjustments of the current sprint are always done in agreement with the whole team. The team always takes care that everybody is able to speak up when there are any doubts. Stakeholder and developers work together goal oriented.

#### Lessons learned
Every role in a product development team has its own intention to build a great product. Which means that the intentions might be different but the goal is the same. A successful product needs all aspects, therefore it is crucial to set a common goal and let everybody work in the same direction

{% asset_img intention.png Every role in a team has different intentions %}

## Conclusion
I am blaming the Marketing Backend here a bit to much. I also need  to mention that during my work on that product i was together with great people and the product is still a major part of the success of the performance marketing team. Beside that, everything written here is only from my perspective.  

All the examples mentioned here have one thing in common. In every case it went wrong when the direct communication between the development team and the stakeholders was not possible. It is important that both sides can learn from each other. It shows that transparency and trust are the key to a successful product.

{% asset_img collabo.png Event Stroming Workshop %}
Developer and Stakeholder are working together on a Domain Model
