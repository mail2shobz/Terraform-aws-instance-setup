Using this main.tf file you can setup an AWS account Along with VPC and subnet via Terraform !!!!
In this Tutorial i have  added how  we can setup an apache  webserver via terraform.


Step 1 : Install Terraform  (If it is not Installed)

          curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -

          sudo apt-add-repository "deb [arch=$(dpkg --print-architecture)] https://apt.releases.hashicorp.com $(lsb_release -cs) main"

          sudo apt install terraform

Step 2 : After Installling terraform run the below command to deploy the main.tf file for starting  the infra setup 
        Run the commands from the main.tf file location
        
         
         
           terraform init
           
           terraform plan
           
           terraform apply
           
       After running the "terraform apply" command it will ask to enter the Secret key,Access Key & Pemkey which you have created.   
