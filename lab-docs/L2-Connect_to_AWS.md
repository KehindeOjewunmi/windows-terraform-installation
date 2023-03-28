## Connect to AWS Cloud

You must have an AWS account to proceed with the below steps.
  
1. Create an IAM programmatic user with administrator access.
   To create one, follow these steps from IAM dashboard
   ---> User --> Add users:provide user name ---> Next--->Attach policies directly:AdministratorAccess-->Next--->Create user
   ---> user name --->security credentials tab ---> create access key
   ---> Download csv
   keep the access key for future use as you will not be able to retrieve it once lost.
   
2. Configure credentials
   ```sh
   aws configure --profile <profile_name>
   ```
3. Test the connection
   ```sh
   aws s3 ls
   ```
   
