# Terraform-AWS-ECS

1. VPC
2. Two subnets (public and private) in two availablity zones
3. ECS Cluster
4. Hello World app deployment
5. Expose the app via ALB

# How to Run
1. At first clone this repo 

  ```
  git clone https://github.com/shawon100/terraform-aws-ecs.git
  ```
2. Then go to terraform-aws-ecs folder. If you want to use access and secret key in providers.tf then provide the keys. <br>
3. Initialize working directory that contain terraform configuration files using below command
  ```
  terraform init
  ```
4. Execute plan and preview 

  ```
  terraform plan
  ```
  
5. Finally apply the plan

  ```
  terraform apply
  ```


