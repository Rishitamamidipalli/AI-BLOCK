# AI BLOCK
AI BLOCK is a framework which combines Machine Learning, Serverless Computing, and Blockchain Technology
# Table of Contents 
-[About this project](#About-this-project)

-[Technologies used in this project](#Technologies-used-in-this-project)

-[How Blockchain technology used in this project](#How-Blockchain-technology-used-in-this-project)

### About this project
This project is implementation of research paper "AIBLOCK_Blockchain_based_Lightweight_Framework_for_Serverless_Computing_using_AI"
Initially, our project was deployed on the serverless platform GCP. However, due to cost considerations, we have switched to using non-serverless functions.

This is firestore database where patients data is collected and stored 
![Screenshot 2024-06-27 234321](https://github.com/Rishitamamidipalli/AI-BLOCK/assets/123208162/72d55285-9016-49e0-bfb6-a9d50f20c380)


### Technologies used in this project
Initially when we get patients data and check whether that patient having covid or not . This is done by using ML model randomforests. This model is trained on the 'Covid Dataset.csv', available for download from Kaggle. Out of the 20 columns of COVID characteristics, we have selected only the 10 columns that show a high correlation with COVID infection.Here they go
![Screenshot 2024-06-27 233413](https://github.com/Rishitamamidipalli/AI-BLOCK/assets/123208162/0d23f922-5b4f-4373-8b06-a534259efeae)


Now this data along with the results is stored in database using Blockchain technology to ensure data integrety.

During the COVID-19 pandemic, usage can vary significantly, with peak times and periods of lower activity. so we have opted for serverless platform Google Cloud platform as the provider dynamically manages the allocation of machine resources

### How Blockchain technology used in this project
In this project, we have created a blockchain where each block consists of data for five individuals.

We have used Python libraries to calculate required hash values and we have stored previous hash and current hash along with data in every block

We can also check whether the data inside our database is changed or not by comparing the currently calculated now and current hash in that block

This project IOT devices,ML algorithem is used to precisely detect COVID from patient data, secure patient data with blockchain, and optimize resources with serverless computing thus AIBLOCK ensured an effective and secure solution for managing patient data during the pandemic

According to paper data received by the sensor of the IoT layer are sent to the gateway node, and then the gateway node sends the data to the serverless data center. In Serverless Datacenter Layer our ML model is deployed .Using blockchain in a serverless Node, the results from the ML model and the data are recorded in blocks. These blocks are stored at both the server database and the user gateway to ensure data integrity
![Screenshot 2024-06-27 234920](https://github.com/Rishitamamidipalli/AI-BLOCK/assets/123208162/c0ab0de4-9950-4690-a4ab-7f807814d7a1)


