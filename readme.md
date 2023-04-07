## Configuration Files
- variables.tf
- outputs.tf
- provider.tf
- xyz.ftvars
- xyz.auto.tfvars
- 
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
  - performance / --refresh=false
  - reconcilation -- configuration drift
  - sensitive info
  - 
## Terraform Basic Commands
- init
- plan
- apply
- destroy


## Configuration Drift

## terraform fmt
## terraform refresh
## terraform validate

## Mutable Infrastructure

## Topics
  - Infra as Code(IaC)

## lifecycle rules
- create before destroy
- prevent destroy
- ignore changes
- 
