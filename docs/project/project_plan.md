# Analytics Project Plan

## Business background

* Who is the client, what business domain the client is in.
* What business problems are we trying to address?

## Scope
* **Overview**:
  * What data science solutions are we trying to build?
  * What will we do?
  * How is it going to be consumed by the customer?
  * Why is it important:
  * When is it needed: 
* **Deliverables**:
| #   | Item      | Definition                    | Outcome | Format | Cadence | Data Source & Elements | Notes |
| --- | --------- | ----------------------------- | ------- | ------ | ------- | ---------------------- | ----- |
| 1   | wait time | wt = room time - checkin time | <2 min | tableau | daily | epic - table? fields? | ----- |
| 2   | b         | ----------                    | ------- | excel | ------- | ---------------------- | ----- |

  * Metric or KPI:
  * Format: - tableau dashboard? excel report?
  * Cadence: - Daily, weekly, monthly
  * Limitations: 
* Target/Outcome
Metric/KPI Goal
  * Assumptions:
  * All video visit vendors track and report wait times with the same methodology
  * Exclusions:
  * 
* Project Size:
* Delivery Date:

### Requirements 
[requirements document provided by client](link to requirements document)

## Personnel
* Who are on this project:
	* Analytics:
		* Project lead -  
		* Data Analyst(s) - 
		* Data Engineer(s) - 
	* Client:
		* Customer contact(s) -
		* Operations contact(s) - 
	
## Metrics
* What are the qualitative objectives? (e.g. reduce user churn)
* What is a quantifiable metric  (e.g. reduce the fraction of users with 4-week inactivity)
* Quantify what improvement in the values of the metrics are useful for the customer scenario (e.g. reduce the  fraction of users with 4-week inactivity by 20%) 
* What is the baseline (current) value of the metric? (e.g. current fraction of users with 4-week inactivity = 60%)
* How will we measure the metric? (e.g. A/B test on a specified subset for a specified period; or comparison of performance after implementation to baseline)

### Definitions
* **Abstract Business Term**: Explanation that lends itself to being assigned a value or a data driven outcome.
* Only include this section if needed.

## Plan
- resource
- timeline
- validation

* Phases (milestones), timeline, short description of what we'll do in each phase.
  * Business Understanding - Define objectives; Identify data sources
  * Data Aquisition and Understanding - Ingest data; Explore data; Enrich data
  * Logic & Modeling - Identify key variables/features; Create logic/model; Conduct qa tests
  * Productionalize - Operationalize and deploy
  * Customer Signoff - Test and validate; Handoff

## Architecture
* Data
  * What data do we expect? Raw data in the customer data sources (e.g. excel files, SQL, on-prem Hadoop, Google Drive, etc.)
* Data pipeline to move either
  * all the data, 
  * after some pre-aggregation on-prem, or
  * sampled data for modeling.

* What tools and data storage/analytics resources will be used in the solution e.g.,
  * Dataiku for the data processing
  * SQL/Hive/R/Python for model construction, aggregation and sampling
  * Tableau, Dataiku, Excel reports for operationalization
* How will the operationalized product be consumed in the business workflow of the customer?
  * How will the customer use the results to make decisions
  * Data movement pipeline in production
  * Make a 1 slide diagram showing the end to end data flow and decision architecture
    * If there is a substantial change in the customer's business workflow, make a before/after diagram showing the data flow.


