# Bank Telemarketing

## Context
This is the dataset that is used for the paper " A data-driven approach to predict the success of bank telemarketing ".
IMHO it's a good dataset for training oneself in M.L. by building one classifier. We are going to use this data to explore the
processes involved in a typical data mining and exploration task based on what you've learnt so far. 

A financial institution is launching a new marketing campaign and In order to minimize cost and optimize strategy, management
has decided to employ data scientists to leverage on their past data and target only the customers who would subscribe to
their offer.

Looking at historical data on customers who have been targeted with similar products, we shall build a model to estimate how 
likely a customer would respond to this new offer. Our goal for this mini-project is to do data mining and exploration on the 
data which is done before building a prediction model. We’re basically making the data ready to be fit into a model.


## Content
### Input variables:
**bank client data**:
1. age (numeric) job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','
self-employed','services','student','technician','unemployed','unknown')
2. marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
3. education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree',
'unknown')
4. default: has credit in default? (categorical: 'no','yes','unknown')
5. housing: has housing loan? (categorical: 'no','yes','unknown') loan:
6. has personal loan? (categorical: 'no','yes','unknown')

**Related with the last contact of the current campaign:**

1. contact: contact communication type (categorical: 'cellular','telephone')
2. month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec') 
3. day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
4. duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target 
(e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call
y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention 
is to have a realistic predictive model.

**other attributes:**
1. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
2. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client 
was not previously contacted)
3. previous: number of contacts performed before this campaign and for this client (numeric)
4. poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

**social and economic context attributes:**
1. emp.var.rate: employment variation rate - quarterly indicator (numeric)
2. cons.price.idx: consumer price index - monthly indicator (numeric) 
3. cons.conf.idx: consumer confidence index - monthly indicator (numeric)
4. euribor3m: euribor 3 month rate - daily indicator (numeric)
5. nr.employed: number of employees - quarterly indicator (numeric)

**Output variable (desired target):**
1. y - has the client subscribed a term deposit? (binary: 'yes','no')

# Citation Request (Acknowledgements)
This dataset is public available for research. The details are described in [Moro et al., 2014]. Please include this citation if you plan to use this database:

[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. 
Decision Support Systems, Elsevier, 62:22-31, June 2014
