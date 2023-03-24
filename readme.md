## Type of Provisioners
  - Officials
  - Partners
  - Community

## Variables
  - variable.tf file
  - TF_VARS_filename
  - .tfvars 
  - .auto.tfvars
  
## Variable Precedence
  - Environment Variables
  - .tfvars file
  - .auto.tfvars
  - -var commandline

## output

show on cmd after apply
export to other system
terraform output  cmd

## reference expression

${resource_type.lable.varname}

### Implicite Dependancy
${resource_type.lable.varname}

### explicite dependancy
- depends_on = [] inside config file
-

## Terraform State File .tfstate
  - order in which resources to be delete / depends on 
  - performance
  - reconcilation -- configuration drift
  - sensitive info
  - 
## 
