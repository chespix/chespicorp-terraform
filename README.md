# Terraform SandBox environment

## Directory structure
```
.
├── environments
│   ├── dev
│   └── ...
└── modules
    ├── ...
    ├── ...
    └── ...
```

## Instructions.

1. Download and install latest version of Terraform.
2. Create an aws_credentials file with your credentials, and place it in the root of the repo. You can use the aws_credentials.template file as an example.
3. For now secrets are saved under terraform.tfvars.
4. Once you have the required secrets in place, move to the desired environment folder.
5. Execute terraform plan. The output should be clean of changes.
6. You are ready to work on infrastructure changes.

## Module documentation

* Each module has its own README.md file with its descriptions and parameters.
