TASK: Perform a Text Classification on consumer complaint dataset.


In this post, I show how to classify consumer complaints text into these categories: Debt collection, Consumer Loan, Mortgage, Credit card, Credit reporting, Student loan, Bank account or service, Payday loan, Money transfers, Other financial service, Prepaid card.

This kind of model will be very useful for a customer service department that wants to classify the complaints they receive from their customers. The classification of the issues they have received into buckets will help the department to provide customized solutions to the customers in each group.

This model can also be expanded into a system, that can recommend automatic solutions to future complaints as they come in. In the past, performing these kinds of tasks were done manually by multiple employees and of course, take a long time to accomplish, delaying swift response to the complaints received.

Machine learning and AI are here to solve this caliber of problems. Imagine you can classify new complaints with 95% accuracy and route them to the right team to resolve the issue. That will be a win and time saving to any business. Your customers will be happy because the right expert from your business will talk to your customers in trying to resolving their complaints. This will translate into lowering churning rate which means more revenue.

I trained a text classifier with 3583117 of data on customers that have made a complaint to consumer financial protection bureau - CFPB about US financial institutions on the services they have rendered to these consumers. The dataset can be found in this link https://catalog.data.gov/dataset/consumer-complaint-database.

This dataset is relatively large and this kind of machine learning process requires more compute power so I chose to use Google’s colab, which gives the option to train a model with free GPU. 
I will walk through the steps and in the end, we will classify new complaints and see how the model performed.

STEPS TO BE FOLLOWED -
1. Explanatory Data Analysis and Feature Engineering
2. Text Pre-Processing
3. Selection of Multi Classification model
4. Comparison of model performance
5. Model Evaluation
6. Prediction

GENERAL APPROACH -
1. Convert the complaint text into its numerical representation using TF-IDF scores.
2. Convert the product classes into numbers using label encoding.
3. Create a conventional machine learning model to complete the task. Since this is NLP, hence we have chosen to work with truncated data.
