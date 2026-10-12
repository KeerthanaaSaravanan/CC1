 # CREATE AN  ACCOUNT IN AWS SET UP A ROOT USER AND AN IAM USER 
  ## AIM
       To create an Amazon Web Services (AWS) account, configure the AWS Root User, create an Identity and Access Management (IAM) User, assign appropriate permissions, generate login credentials, and verify the IAM User's access to AWS services.
## PROBLEM STATEMENT
    AWS Identity and Access Management (IAM) is a service that allows administrators to securely manage access to AWS resources. This experiment demonstrates how to create a Root User, create IAM Users, assign permissions using IAM policies, and verify user access by signing in with different accounts.

## ALGORITHM
 ### Steps 1: Create an AWS account and sign in as the Root User.
 ### Steps 2: Open the IAM Console and create an IAM User.
 ### Steps 3: Assign the required permissions or add the IAM User to an IAM Group.
 ### Steps 4: Generate login credentials for the IAM User.
 ### Steps 5: Log in using the IAM User and verify the assigned permissions.
 Start the experiment.



Open a web browser and navigate to the official AWS website at https://aws.amazon.com/.



Select the option to create an AWS account.



Enter a valid email address, account name, and other requested registration details.



Verify the email address and provide the required contact information.



Enter the requested billing and payment information and complete any identity verification required by AWS.



Select an appropriate support plan and complete the account registration process.



Sign in to the AWS Management Console using the registered email address and Root User password.



Complete any required multi-factor authentication (MFA) registration and verify that the account dashboard is accessible.



Search for IAM (Identity and Access Management) in the AWS Management Console and open the IAM service.



Navigate to the Users section in the IAM console.



Select Create user and enter a suitable IAM User name, such as LabUser.



Configure console access if the available workflow supports IAM User console credentials and console access is required for the experiment.



Create the IAM User and configure its password or other required sign-in credentials.



Navigate to User groups and create an IAM Group named LabReadOnlyGroup, if the group does not already exist.



Attach an appropriate permissions policy to the group. For this experiment, use the AWS-managed ReadOnlyAccess policy to demonstrate read-only access across supported AWS services.



Add LabUser to LabReadOnlyGroup and verify the group membership.



If the console workflow does not create the credentials automatically, configure the required sign-in credentials using the available IAM options.



Record the AWS account ID or account alias and the IAM sign-in URL required to access the account.



Sign out of the Root User session.



Open a fresh private or incognito browser window to avoid confusion between existing AWS sessions.



Navigate to the IAM sign-in URL and enter the account ID or alias, IAM User name, and password.



Complete any required password change or MFA verification.



Verify that the IAM User can access the AWS Management Console.



Open an AWS service permitted by the attached policy and verify that its resources can be viewed.



If a suitable test resource is available, attempt an operation that requires write permissions and verify that the operation is denied.



Review the assigned IAM policies and group membership to confirm that the permissions behave as expected.



Sign out of the IAM User session and secure all credentials.



Record the observed output and conclude that the experiment is successful if login and permission checks behave as expected.


Open a browser and visit the official AWS website.



Click Create an AWS Account or the equivalent sign-up option displayed on the page.



Enter your email address and an AWS account name.



Verify your email address using the verification code sent by AWS.



Create a strong password for the Root User.



Enter the required contact information, including country, address, and phone number.



Complete the payment and identity-verification steps requested during registration.



Select a support plan and submit the registration.



Wait for AWS to complete account activation. Some accounts may require additional verification.



Open the AWS Management Console and select Root user on the sign-in page.



Enter the registered email address, password, and MFA code if prompted.



Confirm that the AWS Management Console home page opens successfully.
## COMMANDS
Include the commands used in the Experiment.

### REG NUMBER: 212223240070
### NAME: KEERTHANA S
 
## OUTPUT
<img width="1919" height="881" alt="image" src="https://github.com/user-attachments/assets/128195ea-50b5-48ba-91eb-5ba1503ba0dd" />
<img width="1919" height="870" alt="image" src="https://github.com/user-attachments/assets/2fb56d46-771d-4adf-89c1-3db639896421" />
<img width="1917" height="981" alt="Screenshot 2026-07-30 081256" src="https://github.com/user-attachments/assets/4a0a70ca-d410-49f4-a862-343b71841d36" />
<img width="1916" height="976" alt="Screenshot 2026-07-30 081527" src="https://github.com/user-attachments/assets/adf5f42c-b855-47f3-93a9-7894d9c5db93" />
<img width="1917" height="988" alt="Screenshot 2026-07-30 081709" src="https://github.com/user-attachments/assets/ab9f1892-842f-4a01-b742-232ca402831e" />
<img width="1917" height="975" alt="Screenshot 2026-07-30 081933" src="https://github.com/user-attachments/assets/df85edf1-b30b-437e-9fa9-f36d82c0f4f2" />
<img width="1917" height="971" alt="Screenshot 2026-07-30 082109" src="https://github.com/user-attachments/assets/f0870e1b-5a32-4188-b23b-d3667c1c36a2" />
<img width="1917" height="978" alt="Screenshot 2026-07-30 082618" src="https://github.com/user-attachments/assets/28f45323-5ac7-4cd9-b647-59344a9bfba6" />

## RESULT
 
The AWS account was successfully created. The Root User and IAM User were configured successfully, appropriate permissions were assigned, and the IAM User was able to log in and access AWS services according to the assigned IAM policies.
