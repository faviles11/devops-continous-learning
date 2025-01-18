## What is the difference between terraform apply and terraform plan, and how do you use them together in a production environment?

| -> ->    | Terraform commands                                                                                                          |
| -------- | --------------------------------------------------------------------------------------------------------------------------- |
| tf apply | Indicates that the changes, previously reviewed in the terraform plan command, are going to be place in the infrastructure. |
| tf plan  | Creates a plan, that normally indicates changes in the infrastructure. Does not change anything.                            |

Differences in production:

Terraform plan is used to review the changes and terraform apply is used to execute them.
