This case study is focused on carrying out in-depth analysis of operations of a company. Metric spike investigation is also an important part of operation analytics.

Case Study 1 (Job Data) Below is the structure of the table with the definition of each column that you must work on: Table-1: job_data job_id: unique identifier of jobs actor_id: unique identifier of actor event: decision/skip/transfer language: language of the content time_spent: time spent to review the job in seconds org: organization of the actor ds: date in the yyyy/mm/dd format. It is stored in the form of text and we use presto to run. no need for date function

You are required to provide a detailed report for the below two operations mentioning the answers for the related questions:

1.Number of jobs reviewed: Amount of jobs reviewed over time. Task: Calculate the number of jobs reviewed per hour per day for November 2020? 2.Throughput: It is the no. of events happening per second. Task: Let’s say the above metric is called throughput. Calculate 7 day rolling average of throughput? For throughput, do you prefer daily metric or 7-day rolling and why? 3.Percentage share of each language: Share of each language for different contents. Task: Calculate the percentage share of each language in the last 30 days? 4.Duplicate rows: Rows that have the same value present in them. Your task: Let’s say you see some duplicate rows in the data. How will you display duplicates from the table?

Case Study 2 (Investigating metric spike)

Table-1: users This table includes one row per user, with descriptive information about that user’s account.
Table-2: events This table includes one row per event, where an event is an action that a user has taken. These events include login events, messaging events, search events, events logged as users progress through a signup funnel, events around received emails. 
Table-3: email_events This table contains events specific to the sending of emails. It is similar in structure to the events table above.

You are required to provide a detailed report for the below two operations mentioning the answers for the related questions:

1.User Engagement: To measure the activeness of a user. Measuring if the user finds quality in a product/service.
Task: Calculate the weekly user engagement? 2.User Growth: Amount of users growing over time for a product.
Task: Calculate the user growth for product? 3.Weekly Retention: Users getting retained weekly after signing-up for a product. 
Task: Calculate the weekly retention of users-sign up cohort? 4.Weekly Engagement: To measure the activeness of a user. Measuring if the user finds quality in a product/service weekly. 
Task: Calculate the weekly engagement per device? 5.Email Engagement: Users engaging with the email service. Task: Calculate the email engagement metrics?
