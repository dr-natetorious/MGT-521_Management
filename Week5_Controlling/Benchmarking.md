# Benchmarking

## What is benchmarking

Benchmarking is the process of taking various metrics and then comparing them against the results of other implementations. This is one of the many tools for management to see if their group is ahead or behind industry trends or other market competencies.

For instance the management might set the goal of being very profitable. They could then benchmark that by looking at their stock profits per earning (P/E) and comparing this with their competitors.

Next they would identify which of these competitors are doing better, and which of these components are missing from our strategy. Having this information allows the management's to course correct the organization.

## How can you create internal benchmarks to measure succcess

My product group has spent a lot of time looking at this question, and we are taking a hierarchical approach to our benchmarking. The model is defined as:

- Level 3- Business Scenario
- Level 2- Tasks of the Scenario
- Level 1- Steps of the Task

For each level we use a Quality of Service (QoS) model to define our benchmarks:

- Availability - How much down time
- Reliability - Did we get the desired result
- Response Time - How long did a transaction take
- Throughput - How many transactions did we complete

For level 1 and 2 we derive this information using internal counters and various auditing policies. Level 3 we compute from measurements collected from the real customer (app on their phone).

Next we evaluate the customer's perceived experience against our stated SLA/SLO. If it does not meet a threshold we drill down the hierarchy and discover which child tasks and activities are responsible.

Having this combination of internal and external benchmarks lets us find the issues that are most critical to the customer. Otherwise we could end up optimizing a step in the supply chain that has poor performance but is not important.

## How can you Benchmark with Competitiors

About a year ago my company started a massive reorganization, which shuffled around 130,000 people. Given the high cost to "shuffling the deck" they wanted to know that the results would be better than before.

To establish this a working group was established, consisting of several executives and high ranking individual contributors. They flew to various competitors headquarters and asked them to explain their approach to software development.

This enabled them to create industry baselines and compare our company to the benchmarked standard. They also provided us with examples of their internal benchmarks.

For instance the time for a developer to build project and run all the automated tests was typically 30 minutes. Comparatively our group was approximately 10 hours. Another standard was reliability in production with "Chaos monkeys" enabled. The service will randomly reboot servers at random intervals. 

Though understanding how the competitors measured success, it showed us the gaps in our processes. Many of these ideas are now being baked into design and our internal benchmarks required to test under similar conditions.

## Benchmarking against the worst company to work flow

> According to [BusinessWeek](http://www.businessweek.com/articles/2013-01-02/dish-network-the-meanest-company-in-america) the worst company to work for is Dish. Thoughts?

To be the worst company in America took 346 out of 19000 or 1.8% of the work force to be unsatisfied? Their complaints are long hours and lots of them, which is a standard corporate environment.  Compare this to Foxconn where 8 employees have committed suicide with poor working conditions being the primary suspect.

A better study needs to exist and look at the important dimensions of each company.

- Intra and cross group cultures
- Company scale and revenue
- Reserves and asset liquidity
- Efficiency and effectiveness of business
- Transparency of communication
- Accountability of management
- Compensation relative to skill level
- Compensation relative to risk
- Business and market sector grow/decline rates
- Stability versus volatility & Seasonality of labor

These metrics will better tell a perspective employee if they are going to be happy or miserable at their job.

## Provide an example where benchmarking is used within your organization

Scott, our EVP recently mandated that every team within his org onboard into Service Health Review web portal. It contains 22 weekly KPIs covering availability, customer satisfaction, supportability, security and compliance status, response time, and business continuity.

Each line item lists the target score and the one archived per product group. This provides Scott with the ability to compare status, and focus in on what areas need correction.

Without such a system it would be difficult to keep up with numerous projects that his 25,000+ engineers are working on. It would also be more complex to makes sure the right investments were being made, at the right time.

Having taken this course on boarding into his portal makes a lot more sense. We have had many similar requests in the past from business leaders, but didn't understand what value they got from these simple numbers. After reading this chapter its more clear how they enforced the control functions needed to run the business.
