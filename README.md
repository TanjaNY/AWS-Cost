# AWS-Cost
## AWS monthly cost
This Jupyter Notebook contains Python code that retrieves AWS cloud cost data for the current month by service using the AWS Cost Explorer API. It aims to help users keep track of their expenses and make informed decisions about their cloud infrastructure.
The notebook imports necessary libraries, initializes the Cost Explorer client, and retrieves the desired cost metrics grouped by AWS service. It then normalizes the JSON data into a Pandas DataFrame, providing a clear, tabular view of the cost breakdown. The notebook also calculates the total monthly charge and prints it for convenience.
To run the notebook successfully, follow these steps:
1.Set up your AWS credentials by running the "aws configure" command in your terminal or command line interface (CLI).
2.Ensure that your IAM user or role has the necessary permissions to access the Cost Explorer API.
3.Download and open the Jupyter Notebook in your local environment.
3.Execute the code cells one by one to retrieve and display your AWS cloud cost data.
4.Modify code, eg save the data frame in a csv file and save it in an S3 bucket
