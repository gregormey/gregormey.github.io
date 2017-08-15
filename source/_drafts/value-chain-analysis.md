---
title: Optimization along the Value Stream
tags:
- Value Chain
- Process Optimization
- Agile Methods
- Lean Systems
- Kanban
---

The first important step is to understand your value stream.
<!-- more -->

## Value Stream Mapping
Value Stream mapping is a team exercise which must involve representatives of all areas of the process being mapped. I would highly recommend to use pen and paper because you will need to make frequent changes and corrections during the creation.

There are some commonly used value stream mapping symbols which apply for manufacturing workflows.
{% asset_img vsm-symbols.gif VSM Symbols %}

Most of them do not apply for digital product development. In my experience it is important to symbolize the following items within larger organisations.

- Teams
- Stakeholder
- Departments
- Products/Tools
- Data Communication Path
- Lead Times

If you are not creative enough to find suitable symbols for the different items, they can also be visualized with sticky note colors, arrows and circles on a whiteboard.

As a first step i usually define the boundaries for the process we want to map. Most value stream maps go from customer to supplier. For digital products this transfers to customer to the development team. I start with placing them as the first items on the map. 

Now i like to continue with placing other items on the map which are in the process in between. I prefer here to focus on teams and stakeholders first, because it is usually easier to start on a detailed level and aggregate them later. For me it works better by starting by the customer and going from the left to the right.

When all relevant teams and people are identified and placed along the process it makes sense to map them to departments and tools or products, because this could be important for the next step to identify the communication paths.

To fully understand the process it is crucial to know how information and data is communicated within the process. It is possible to visualize that with connections between the items on the map. An arrow can indicate the direction of the communication. It is furthermore important to document which kind of information is provided to whom.     

After the exercise probably everyone involved should have a pretty good impression on how the value stream for the product looks like.    

## Lead Times
A lead time is the latency between the initiation and execution of a process. The sum of the lead times of all process steps of our value stream is the time needed to deliver. When you know how long it takes to produce one delivery, you can calculate what is your capacity over time.

After the creation of the value stream map it is time to get those lead times for each step. I find it interesting to evaluate lead time estimations and compare them with the actual lead times. In this way you can already identify some potential problems.

There are different ways to measure lead times and it depends on the work that needs to be done. What is important is that you do not only measure the execution time but also the waiting time per deliverable.     

You can try to use tools like jira or measure with time tracking tools. I have the best experience with creating a kanban board that represents the value stream and all items in progress. It is very efficient to bring representative together on a daily basis to update the board together. Every item that does not moved gets +1 day on its lead time counter. 

With this informations you can easily measure the average lead time per process step and compare that with the estimated values. This enables you to update your planning forecast on a regular basis.   

## Optimization
I think it is required to have a dedicated goal to be able to optimize your process into the right direction. If your goal is to deliver a certain amount of items in a given time span you need to find out how far you are away from your goal and how much faster the process has to be.

A first indicator to find initiatives to get faster is the process steps were you have the highest gab between the expected lead time and the actual one. What is very important is that it is required to optimize the flow. That means that you need to keep waiting time as low as possible. Every process step where the waiting time is much higher then the execution time is a good candidate for optimization. 

As a product owner you are usually responsible for a development team. But this is usually just one step in the process chain. But from my point of view there are ways to also support other teams.

- Are there any tools that could be build to speed up communication and knowledge sharing ?
- Can manual steps be automated ?
- Does it help to spend time in other teams to foster collaboration and shorten feedback loops ?

What never helps is the blame game. The product will be only successful if the whole value chain works.

Whatever you do, it is crucial to measure the success of you initiatives by their impact on the lead time and the overall process time. If you are optimizing along the value chain this will be your success factor.   

## Conclusion

