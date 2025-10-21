## Deployment Commands


# Clone or create your project directory
```bash
mkdir terraform-ec2-basic
cd terraform-ec2-basic
```

# Copy the files above into your directory

# Copy the example variables file
```bash
cp terraform.tfvars.example terraform.tfvars
```

# Edit terraform.tfvars with your values
# Make sure to update the key_name with your actual AWS key pair

# Initialize Terraform
```bash
terraform init
```

# Review the plan
```bash
terraform plan
```

# Apply the configuration
```bash
terraform apply
```

# After deployment, you can:
```bash

    SSH into your instance: ssh -i /path/to/your-key.pem ec2-user@<public-ip>
    View the web page: Open the web_url output in your browser
```

# Cleanup

# Destroy all resources when done
```bash
terraform destroy
```


