## Introduction

Customer churn is a problem that concerns arguably all customer-oriented
businesses. Gambling operators are not an exception. In the effort of improving
retention, it is needed to identify players who are likely to leave soon so that
the CRM team can try to keep them engaged by sending relevant offers. This
proactive approach can significantly reduce churn rates and improve customer
loyalty, leading to increased revenue and a more stable customer base.

## Task

No target variable so it neeeds to be defined.
Here I try to build a base model. 

## Data

The dataset at your disposal consists of 7k customers described along the following features:

* `user_id` unique identifier of a customer
* `date` date
* `vertical` breakdown of vertical for the other features, some features are
  vertical agnostic
* `turnover_cash_num` number of bets placed with real money
* `turnover_cash_sum` sum of bets placed with real money
* `deposit_approved_num` number of approved deposits
* `deposit_approved_sum` sum of approved deposits
* `withdrawal_approved_num` number of approved withdrawals
* `withdrawal_approved_sum` sum of approved withdrawals
* `NGR_sum` net gaming revenue, i.e. difference between turnover and winnings
* `session_num` number of sessions
* `session_sum` total length of sessions


