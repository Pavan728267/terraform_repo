# Terraform config file to spin-up "Single node ElasticSearch" in AWS.
<h2>
  Instructions to use
  </h2>
 
 <h2>
  Install and Configure Terraform
  </h2>
  Refer here <a href="https://www.terraform.io/downloads.html">for installing terraform</a><br>
  Add terraform executable path to ENV variables
  
 
 <h2>
  Steps to spin up the infra using Terraform
  </h2>
 1. Clone the repository terraform_repo<br>
 2. cd terraform_repo<br>
 3. Open the .tf file and edit/save the variable section to add the AWS access key, secret key and account id.<br>
 4. Run the below commands from the path where .tf is located to spin up Elastic search single node cluster,<br>
 i. terraform init<br>
 ii. terraform apply<br>
 iii. type "yes" when prompted<br>