# Adding IAM Admin User

### Introduction:



### Summary:
Create a user with Administrator Access via an attached Managed Policy.

\
\
**Customize Sign-in URL:** \
IAM → Dashboard \
Sign-in URL for IAM users in this account → Customize \
Preferred Alias: rmathisen-general \
https://rmathisen-general.signin.aws.amazon.com/console

**Create IAM Admin User:** \
IAM → Access Management → Users \
Add User \
User name: iamadmin ... Access Type: AWS Management Console access ... Console PW: create Custom PW \
Attach existing policies directly → Check "AdministratorAccess" \
No Tags \
Create User

**Sign-in to new User & assign MFA:** \
Copy Sign-in URL into clipboard & sign out of your account \
Go to that URL & enter Username & PW info \
Assign MFA to this user for additional Security ([Tutorial on assigning MFA](https://github.com/rmathisen-aws/Multi-Factor_Authentication/blob/main/README.md)) \
Sign out & sign back in to test for MFA
