# IAM policies of use to DevOps at Berico

Listed here are IAM policies that DevOps teams can use to enable users access to parts of AWS without the fear of large accidential expenditures. 

The EMR policy restricts the specific instances a user can spin up within EMR.

Billing allows the users all access to the aws-portal for billing.

Change-password was created because when a user is given readall access it does not allow them to change password even if change password is set in the accounts password policy.
