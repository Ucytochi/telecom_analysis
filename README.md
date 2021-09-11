## Project Description
---

We carried out analysis on two datasets provided - Data and Clients dataset.

The virtual telephony service is developing a new function that will give supervisors information on the least effective operators. An operator is considered 
ineffective if they have 

- a high number of missed incoming calls
- a long waiting time for incoming calls
- a small number of outgoing calls

The **Data** dataset contains the following columns:

- `user_id` — client account ID
- `date` — date the statistics were retrieved
- `direction` — call direction (`out` for outgoing, `in` for incoming)
- `internal` — whether the call was internal (between a client's operators)
- `operator_id` — operator identifier
- `is_missed_call` — whether the call was missed
- `calls_count` — number of calls
- `call_duration` — call duration (excluding waiting time)
- `total_call_duration` — call duration (including waiting time)

 

The **Clients** dataset has the following columns:

- `user_id`
- `tariff_plan` — client's current plan
- `date_start` — client's registration date
---
Basically, we:
- Carried out exploratory data analysis
- Built an algorithm to identify ineffective operators
- Tested some statistical hypotheses

The libraries used in this analysis are pandas, numpy, datetime, matplotlib, seaborn, plotly, and scipy.

I do not have the rights to share the datasets used in this analysis.
