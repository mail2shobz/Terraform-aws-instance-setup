Using this main.tf file you can setup an AWS account Along with VPC and subnet via Terraform !!!!
In this Tutorial i have  added how  we can setup an apache  webserver via terraform.


Step 1 : Install Terraform  (If it is not Installed)

          curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -

          sudo apt-add-repository "deb [arch=$(dpkg --print-architecture)] https://apt.releases.hashicorp.com $(lsb_release -cs) main"

          sudo apt install terraform

Step 2 : After Installling terraform run the below command to deploy the main.tf file for starting  the infra setup 
         
         Note : Before  deploying make sure you have added the ROOT Access Key and Secret key inside the main.tf file 
         Also make sure created the pemkey for the instance via AWS console and should be added  in the keypair section inside main.tf file
           
           terraform init
           
           terraform plan
           
           terraform apply
