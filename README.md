# opportunity-analysis
Analyzed sales opportunities and revenue by region, by deal size, and by channel. And examined if there is asymmetric performance between selling directly or selling via partners

## Objective
To create a dashboard to analyze sales opportunities and revenue by region, by deal size, and by channel. To examine if there is asymmetric performance between selling directly or selling via partners. 

## Analysis
Interestingly, there is a specific concern among companies that compete in industries characterized competitive bidding. A competitive bid is a procurement process
in which bids from competing suppliers are solicited. More specifically, in business such as software or any other capital good there are numerous sequential stages
across which firms compete. There is often an initial RFP – Request for Proposal -stage, followed by a qualification stage where a company’s capabilities are 
examined, socred and approved for further negotiation, as the case might be. Then a solution is proposed by the vendor company. If accepted by the buyer, the
proposal is formally submitted into full blown competition for the contract to be awarded. This factoid regarding the stage can result in the wrong impression 
as to performance. Tracking revenue as a result of responding to an RSP may positively inflate your performance. This is the case because at every stage of the 
competitive bid process there is a probability of coming up short. Accordingly, it would be wise to avoid making decisions with biased numbers by recognizing the 
pitfall. Thus, you are going to create two “revenue” metrics. A caveat: it’scalled revenue although strictly speaking – per GAAP - you cannot book revenue until the 
sale iscompleted, finalized. Our exercise would be for planning, decision-making purposes.

First revenue metric. Revenue: A salesperson’s estimate of what the revenue will be.

Second. Factored Revenue: But salesperson’s estimate can be biased upwards. 

Thus, it is prudent to “adjust” the revenue estimate proffered by some likelihood, some assessment, of it actually occurring. The adjustment used here takes 
into account the fact that the sale of software products typically proceeds through 5 steps or stages before it succeeds. Here are the stages.
* Lead: 10%
* Qualify: 20%
* Solution: 40%
* Proposal: 60%
* Finalize: 80%

And associated with it are the “discount” factors applied to the initial salesperson’s original
estimate. Thus, an initial $10,000 “sale” which is a lead rather than a finalized sale is recognized
as Revenue. But it is acknowledged that ‘tis not a final sale and therefore adjusted, called
Factored Revenue, and recognized as $1,000 ( =10%*$10,000).


In Sum
There are several factor variables (i.e. categorical variables): Region, Sales Stage, Size ID that allow us to
(i) create additional categorical variables and 
(ii) examine continuous variables (primarily revenue) across
categories.

## Analytical Insights/ Insights from Dashboards
* Company revenue is $2 billion and factored revenue is $461 million.
* Opportunity count and revenue follow a familiar funnel pattern, with totals decreasing
with each subsequent stage.
* Most of our opportunities are in the East region.
* Large opportunities generate more revenue than medium or small opportunities.
* Large partner deals generate more revenue: $8 million on average versus $6 million for
direct sales.

Although some of these “conclusions” are obvious – they not only confirm my intuition but ascribe a quantitative result to it. This quantitative result is 
informative in the absolute sense and in the relative sense; i.e. Partners tally more opportunities than Direct Sales. And this larger count on the part of
Partners it is about 1 and 1 ½ times as much as Direct for accounts in the Lead stage. 

## Visualization Tool
Power BI
