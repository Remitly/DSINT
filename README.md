Exposition is included below, but please contact us with any questions you may have.

This data is related to direct marketing campaigns of a Portuguese banking institution.  Each row represents the outcome of a single campaign with respect to a single customer.  Each campaign may consist of multiple phone calls, and frequently, more than one contact to the same client was required in order to determine if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

A single customer may be represented in multiple rows in this data set, but there is no such explicit link (there are a few features that factor this in).

Your objective is to construct a predictive model that can be used to classify whether a particular client will ('yes') or will not ('no') subscribe to the product.

Input variables:

# bank client data:

```
1 - age (numeric)
2 - job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
4 - education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
5 - default: has credit in default? (categorical: 'no','yes','unknown')
6 - housing: has housing loan? (categorical: 'no','yes','unknown')
7 - loan: has personal loan? (categorical: 'no','yes','unknown')
```

# attributes about the final call of the current campaign:

```
8 - contact: contact communication type (categorical: 'cellular','telephone')
9 - date: YYYY-MM-DD format (categorical)
10 - duration: duration of final call in campaign, in seconds (numeric).
```

# other attributes:

```
11 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
12 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
13 - previous: number of contacts performed before this campaign and for this client (numeric)
14 - frequency: relative frequency of contact, between 0 and 1 (numeric)
15 - poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
```

# social and economic context attributes

```
16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)
17 - cons.price.idx: consumer price index - monthly indicator (numeric)
18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)
19 - euribor3m: euribor 3 month rate - daily indicator (numeric)
20 - euro.growth: point in time estimate of annual eurozone growth rate (numeric)
21 - nr.employed: number of employees - quarterly indicator (numeric)
```

Output variable (desired target):

```
22 - y - has the client subscribed a term deposit? (binary: 'yes','no')
```
