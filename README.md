# swiggy-delevery-rejection_CaseStudy
Swiggy has a bold vision to elevate the quality of life of urban consumers by offering unparalleled
convenience. At the heart of this vision is solving the hyperlocal delivery challenge of
**“ Assigning the right delivery partners to the right set of orders at the right time”**
This is one of those problems that is positioned at the cusp of marrying the state of the art
methods in Artificial Intelligence and Operations Research in large-scale near-real-time
applications. 

Swiggy delivery partners have the option to reject an order, if he/she wishes to. However, rejection
of an order increases the delivery time for the customer, hence we want to avoid rejects. 

There are two sample datasets:

**Assignment:** Each row corresponds to an order assignment to the delivery partner.

**Delivery Partners:** Each row corresponds to a delivery partner.

This Model does the following:

1. The first part of any data science problem is understanding the size, impact and cause of
the problem (DE rejection in this case). With that context, an exploratory data
analysis has been done.

2. This model predicts if a order assigned to delivery executive will get rejected or not. Furthermore we can calculate best DE to assign order using predict_proba() with best probability.

