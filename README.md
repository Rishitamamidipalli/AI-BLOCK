#AI BLOCK
AI BLOCK is a framework which combines Machine Learning, Serverless Computing, and Blockchain Technology

#About this project
This project is implementation of research paper "AIBLOCK_Blockchain_based_Lightweight_Framework_for_Serverless_Computing_using_AI" Initially, our project was deployed on the serverless platform GCP. However, due to cost considerations, we have switched to using non-serverless functions.

#Technologies used in this project
Initially when we get patients data and check whether that patient having covid or not . This is done by using ML model randomforests. This model is trained on the 'Covid Dataset.csv', available for download from Kaggle.

Now this data along with the results is stored in database using Blockchain technology to ensure data integrety.

During the COVID-19 pandemic, usage can vary significantly, with peak times and periods of lower activity. so we have opted for serverless platform Google Cloud platform as the provider dynamically manages the allocation of machine resources

#How Blockchain technology used in this project
In this project, we have created a blockchain where each block consists of data for five individuals.

We have used Python libraries to calculate required hash values and we have stored previous hash and current hash along with data in every block

We can also check whether the data inside our database is changed or not by comparing the currently calculated now and current hash in that block

This project IOT devices,ML algorithem is used to precisely detect COVID from patient data, secure patient data with blockchain, and optimize resources with serverless computing thus AIBLOCK ensured an effective and secure solution for managing patient data during the pandemic
