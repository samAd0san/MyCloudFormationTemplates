# MyCloudFormationTemplates
In this repository i will push all the cloudFormation templates which i work on

In order to create a CloudFormation Template and execute it 
1. we need to create a stack (Using AWS CLI)
- aws cloudformation create-stack --stack-name <stack_name> --template-body file://C:\Users\sohai\OneDrive\Desktop\Templates\template.yaml # specify the path of the file
2. to update the stack
- aws cloudformation update-stack --stack-name ec2-stack --template-body file://C:\Users\sohai\OneDrive\Desktop\Templates\template.yaml 
3. We can also Create the stack using aws dashboard or UI
