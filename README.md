***Consumer Complaints Issue Classification***

**Overview**:

Banks provide a number of services to their customers and as a result of this they face a variety of challenges on a daily basis. These challenges may range from issues related to, but not limited to, customer credit and debit, education loan, customer churning, mortgages, and daily transactions. Over the past few years’ banks have increased their social presence. This has led them to receive a large number of complaints from various sources such as Twitter, Facebook, and the Consumer Financial Protection Bureau. If The bank fails to solve or even address the complaints of its customers, they will be greatly disappointed by its services. This would lead to a diminished brand image and in-turn affect business. Manually responding to each and every complaint in time is not feasible and an extremely tedious task as every complaint has to be read and routed to the concerned department. Banks are looking at ways to reduce this manual effort and improve response time. In this project we have tried to leverage the large amount of unstructured data that banks receive to provide one such solution to this problem.

**Topic survey in brief**:

This database is a collection of complaints about consumer financial products and services that will be sent to companies for response by Consumer Financial Protection Bureau. Complaints are published after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first.
Existing Solutions have only emphasized on initial data processing and exploratory data analysis so we emphasis more on build models that can provide insights and add value.

**Selecting Data Attributes**:

For our final model we have chosen 'Bank account or service’ as our only financial service and two features ('consumer_complaint_narrative', ‘issue’) from the extracted dataset.
This sample of data is being utilized has unique issues like ‘Account opening, closing or management’, ‘Deposits and withdrawals’, ‘Problems caused by my funds being low’, ‘Using a debit or ATM card’, ‘Making/receiving payments sending money.


Our model predicts, The dependent feature "Issue"(Multi Class Classification) based on independent feature "consumer_complaint_narrative" for the financial service 'Bank account or service’. Different classes, being predicted are : ‘Account opening, closing or management’, ‘Deposits and withdrawals’, ‘Problems caused by my funds being low’.

**Conclusion**:

Our model predicts issue type based on consumer complaint narrative. With 95 percent confidence our models can predict the issue type with an accuracy anf f1-score of 77 and 76 percent respectively.

**Limitations**: 

In our model We used Count Vector and Tf-idf, both create vectors based upon the mere presence and occurrences of the word rather than the semantical aspect of the words. This may lead to inefficiency while reviewing issues which are more nuanced and subjective.

**Future Scope**:

As a future scope we can further expand it for all the other issue types as well.

**Closing Reflections**:

The finalized model is performing well as it is not overfitting and the accuracy, f1-score and roc_auc scores were good. 




