# ReachIn-Box_Assignment-Backend
**PROJECT OVERVIEW**

The objective of this initiative is to establish OAuth integration with Google and Microsoft platforms to obtain authorization for accessing user email accounts. Following email retrieval, the system will employ Python Model to analyze the content and classify emails into three distinct categories: 'Interested', 'Not Interested', and 'Requesting More Information'. Subsequently, automated email responses will be generated based on these classifications, by creating our own model using Python, than traning that model through dataset than further testing it.

**TECHNOLOGIES USED**

Python: Chosen as the primary programming language
OAuth: To facilitate secure authentication with Gmail and Outlook APIs
Gmail API: To access and interact with emails in Gmail accounts securely.
Outlook API: To access and interact with emails in Outlook accounts securely.
Bull MQ: For Task Scheduling

**Steps to Run the Code**

*Prerequisities*

Python Installed on your system.
Redis Installed on your system
A Google Cloud Platform (GCP) project with the Gmail API enabled and OAuth 2.0 credentials set up.
A Microsoft Azure account with the Outlook API enabled and OAuth 2.0 credentials set up.

*Setup*

Clone the repository
Download the 'Config.json' file provided
Retrieve the OAuth credentials and then upload them as 'client_secret'.
Execute the Python script - 'GmailReply.ipynb'

*Usage*

Once the application runs, it will parse and check emails from both Google and Outlook email IDs.
It will then use machine learning to understand the context of the emails and assign automatic labels.
Based on the context of the emails, automated replies will be sent.

**Result**
![image](https://github.com/PRATISTHASARSWAT/ReachIn-Box_Assignment-Backend--/assets/78549697/a42654a7-0665-4a47-8197-7d3e2ee22d8c)
![image](https://github.com/PRATISTHASARSWAT/ReachIn-Box_Assignment-Backend--/assets/78549697/41d8e253-5c40-4add-bc11-bc210850bda6)

