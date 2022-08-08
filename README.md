# terraform-task
 A Terraform code that produces the following AWS resources: VPC, 2 Subnet(a Private and the second one is public), Internet Gateway, NAT Gateway, Route Tables, Route Tables Associations. And run WORDPRESS(public subnet) and MYSQL(private subnet) using docker.
## Code
Create an AWS access key:
* Create an IAM user.
* Create the access key under that IAM user.
* After creating AWS access key and secret, add them to the code in main.tf under provider "aws" .

## Run Terraform:

clone the code:
```bash
   clone https://github.com/mohamadassi173/terraform-task
```
Go to the project directory
```bash
  cd terraform-task
```  

Replace access key and secret key in main.tf and terraform init:
```bash
   terraform init
```
<img width="446" alt="image" src="https://user-images.githubusercontent.com/57872327/183361929-96414e7e-5eb7-4267-980b-36fe5db0c67b.png">

preview code results:
```bash
    terraform plan
```
run:
```bash
   terraform apply
```
<img width="490" alt="image" src="https://user-images.githubusercontent.com/57872327/183362015-2e593e56-660c-4f19-9a78-0fec72e86110.png">

Screenshot of 2 created instances:  
<img width="638" alt="image" src="https://user-images.githubusercontent.com/57872327/183363158-89671f39-cd49-4270-9a3d-278aaa7a9de7.png">
