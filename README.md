# terraform-aws-ecs
Provision an aws ecs cluster in a vpc having both public and private subnet with a hello world app and expose it via alb using terraform <br>

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


