# customer-feedback-topic-modelling
My company gets a large amount of customer feedback in the form of text. This text data is also unlabelled. So unsupervised natural language processing technique - topic modelling is applied to this text data to extract information out of it.

Here the topics for each of the customer feedback is detected using topic modelling technique that employs LDA (Latent Dirichlet Allocation). Probability is set to a condition of greater than 0.3, so that feedback with multiple topics are captured. 

The resultant dataframe is transferred back to the database and from there to BI tool - Qlik Sense. So that topics share could be analyzed over time and it is also possible for business users to reflect on the specific topic by filtering and looking into relevant customer feedback. 

Please note: Data, results and other confidential information aren't shared explicitly due to privacy reasons. This is only to showcase the approach towards analysis.  
