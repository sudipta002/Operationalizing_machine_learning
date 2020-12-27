
## Operationalizing Machine Learning

We create an Automated Machine Learning pipeline in Azure Machine Learning Studio. On successful execution of AutoML, we get to see the best model that provides the highest accuracy for the given dataset. However, the model has been deployed with authentication and application insights (logging)enabled which in turn provides an HTTP REST API endpoint. Swagger helps for API documentation, and Apache Benchmark helps in messuring performance of the deployed model. This project also extends to create, publish and consume a pipeline. 

The data contains different attribute of banking clients. The classification goal is to predict if the client will subscribe a term deposit (variable y).

Data Shape: 32,950 (row) x 20 (column)

The data is available at this [link](https://automlsamplenotebookdata.blob.core.windows.net/automl-sample-notebook-data/bankmarketing_train.csv).

## Architectural Diagram

The following diagram shows the architecture of the project. 

![](images/Architecture_Diagram.png)

## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps. 

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
