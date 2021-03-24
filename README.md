# Adding IAM Admin User

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

Copy Sign-in URL into clipboard & sign out of your account \
Go to that URL & enter Username & PW info \
Assign MFA to this account for additional Security
