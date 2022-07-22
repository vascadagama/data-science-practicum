# Определение перспективного тарифа для телеком-компании

The federal operator "Megaline" offers customers two tariff plans: "Smart" and "Ultra". To adjust the advertising budget, the commercial department wants to understand which tariff brings in more money.
We have a small sample of 500 subscribers for 2018: who they are, where they are from, what tariff they use, how many calls and messages each user sent. It is necessary to analyze the behavior of customers and draw conclusions about the costs of subscribers at different tariffs, determine how the average revenue per subscriber differs depending on the tariff, as well as the region.

Tables:
- users (information about users)
- calls (information about calls)
- messages (information about SMS)
- internet (information about internet sessions)
- tariffs (information about tariffs)

Tariff note:
Megaline always rounds seconds to minutes, and megabytes to gigabytes. Each call is rounded up separately: even if it lasted only 1 second, it will be counted as 1 minute.
For web traffic, individual sessions are not counted. Instead, the monthly total is rounded up. If a subscriber uses 1025 megabytes this month, they will be charged for 2 gigabytes.

Plan:
1. Data preparation:
    - correction of types and other errors, data cleaning;
    - calculation for each user per month: the number and duration of calls, the number of messages, traffic volume, revenue.
2. Data analysis: how many minutes of conversation, how many messages and how much Internet traffic do users of each tariff need per month? Construction of distributions, calculation of the mean, variance and standard deviation.
3. Hypothesis testing:
    - the average revenue of users of the "Ultra" and "Smart" tariffs differ;
    - the average revenue of users from Moscow differs from the revenue of users from other regions.
