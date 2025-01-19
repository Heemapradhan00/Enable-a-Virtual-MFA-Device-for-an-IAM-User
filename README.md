# Enable-a-Virtual-MFA-Device-for-an-IAM-User

Steps to Enable a Virtual MFA Device
Sign in to the AWS Management Console.
Navigate to the IAM Console and click Users.
Select the desired IAM user and go to the Security Credentials tab.
Under the Multi-factor authentication (MFA) section, click Assign MFA device.
Select Authenticator app, provide a Device name, and click Next.
Use your MFA app:
Scan the QR code displayed on the screen or
Enter the secret key manually if the app doesn't support QR codes.
The app will start generating one-time passwords.
Enter two consecutive one-time passwords into the fields labeled MFA code 1 and MFA code 2.
Click Add MFA to finalize the setup.

\Note: You can use popular authenticator apps like Google Authenticator, Authy, or Microsoft Authenticator for this setup.
