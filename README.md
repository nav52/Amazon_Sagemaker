# Amazon_Sagemaker
Deploy the ML model on Amazon Sagemaker

## Steps
1. Login to AWS Console
2. Create a Notebook instance in the Sagemaker with this git repository.
3. Run the Notebook instance to
    - Create a s3 bucket
    - Download the data and save in the s3 bucket
    - train_test split to preprocess for the xGBoost
    - Implement xGBoost on the data
    - Create endpoint to expose the ML model
    - Delete the resources to save on billing
