# Supply-chain-Atliq-Mart

## Problem Statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. 
It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.
AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. 
It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, 
which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team 
to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ 
and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

## TASK
1. Create the metrics according to the metrics list.
2. Create a dashboard according to the requirements provided by stakeholders in the business review meeting. 
    You will be provided with the transcript of this business review meeting in the form of a comic.
3. Create relevant insights that are not provided in the metric list/stakeholder meeting.

## Key Metrics build using dax functions

![S1](https://user-images.githubusercontent.com/110016087/202967986-db902176-161b-4037-9b70-b4f0decac289.png)

## Data Model

![Data Model](https://user-images.githubusercontent.com/110016087/202968192-051bbf43-8019-4ab3-8414-a5d89d195fa3.png)

## Report Visual

![P1](https://user-images.githubusercontent.com/110016087/202968619-53be4caa-265f-45c2-add9-39006d2feb5f.png)

![P2](https://user-images.githubusercontent.com/110016087/202968781-8f38da2c-b40b-401d-9121-7f0051607f1c.png)

## Key Insights 

### Reference Page 1
1. We are now meeting the target of respect key delivery metric such as OT% (On Time), IF% (In Full) and OTIF% (On time In full)
2. Total Order Qty - 13.43M, Total Delivery Qty-12.97M, Undelivered Qty- 458K
3. We have better result in term of Volume fill rate-96.59 % overall
4. Acclaimed Store, Coolbue, Lotus Marts are some customers were our OTIF% is Lowest Reference from split by customer visual
5. In term of Customer-id- 789103, 789121, 789122, 789421, 789503, 789601, 789702 are those customers where our service is mostly lacking
6. Through Split by cities in all three cities our delivery service performance nearly same were as service in Surat is worst.

### Reference Page 2
7. From Metric Performance overtime graph the OTIF, OT, IF values are approx. similar throughout services months (March to August)
8. From Product Insite we come to known that our service mainly affects in term of LIFR% (Line fill rate)
were as many lines orders we shipped out of the total line order is approx. 35% less
