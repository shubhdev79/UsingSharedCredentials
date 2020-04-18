# UsingSharedCredentials
Repo to look for AWS_COncepts

# 1.Create a Shared Credentials File

**The following procedure shows how to create a shared credentials file in your home directory. For the SDK sample code to function properly, you must create this file.**

In a text editor, create a new file. In the file, paste the following code:

**[default]
aws_access_key_id = YOUR_AWS_ACCESS_KEY_ID
aws_secret_access_key = YOUR_AWS_SECRET_ACCESS_KEY
In the text file you just created, replace YOUR_AWS_ACCESS_KEY with your unique AWS access key ID, and replace YOUR_AWS_SECRET_ACCESS_KEY with your unique AWS secret access key.**

Save the file. The following table shows the correct location and file name for your operating system.

If you're using...	Save the file as...
Windows	
**C:\Users\<yourUserName>\.aws\credentials**

- In My Case, File was already present. So Can go ahead and use the same credentials file.

Linux, macOS, or Unix	
~/.aws/credentials

# --------------------------------------------------------------------------------------

