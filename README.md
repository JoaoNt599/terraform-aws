# Terraform AWS


## 🛠️ Technologies Used

- WSL
- AWS CLI
- Terraform
- Docker

## Resources

- VPC
- Subnet
- Route Table
- Internet Gateway
- Intances: EC2

## Struct:

    .
    ├── README.md
    ├── docker
    │   ├── compose.yaml
    │   └── dockerfile
    ├── struct.txt
    └── terraform
        ├── main.tf
        ├── terraform.tfstate
        └── terraform.tfstate.backup

## Run the Container:

    docker compose up --build -d

## Container Access:

    docker exec -it terraform-container sh

## Validate credentials:

    ls -la /root/.ssh
    ls -la /root/.aws

## Terraform Commands:

    terraform init
    terraform plan
    terraform apply
    terraform output
    terraform destroy
    
