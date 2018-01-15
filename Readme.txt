Running the code
*****************

1.Create the databricks account and activate the 14-day trial period.

2.Create an AWS account and link your AWS account to databricks by following the tutorial given below.
	https://accounts.cloud.databricks.com/#awsRoleInstructions

3. The images shoulded be loaded in an AWS S3 repository and mount to databricks by referring to the following tutorial.
	
	https://databricks.com/wp-content/uploads/2015/08/Databricks-how-to-data-import.pdf

4.For Approch 1 create the following directory structure for Approach 1.
		
		|
		|->benign
		|
		|
		|->malignant
		|
		|
	
	Then skip step 5 if you just want to execute the first approach only and follow the rest of the steps.
	
	
5.Make sure that the AWS S3 bucket that you create has the following directory structure for the second approach.
	data
	  |
	  |
	  |->train
	  |	  |
	  |	  |
	  |	  |->benign
	  |	  |
	  |	  |->malignant
	  |
	  |
	  |
	  |->validation
	  |   |
	  |   |
	  |   |->benign  
	  |   |
	  |   |->malignant
	  |   |
	  |
	  |
	  |->myimages
	  |
	  
6.Import the .pynb files to databricks and change access key and secret access key codes for your AWS S3 account.

7. Start executing the code in databricks