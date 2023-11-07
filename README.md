The Aim of the implimentation is to enable smart case generation from Email in the Salesforce org. The implimentation uses Pulze.ai that provides efficient evaluation layer on popular LLMs.

Here is how to use the functionality.

1) First enable Email-to-Case service in the Salesforce services and email forwarding in your email settings.
2) Make sure to set field level security in Salesforce Case object.
3) Add Apex Trigger and Handler in the Salesforce org.
4) Create Pulze app from the Pulze dashboard and copy the key.
5) Host the Flask back-end in your preferable VM.
6) Do not forget to replace the key.txt and email_cred.json file with your own Key and Credentials.
7) Add your API to the Secure Site settigs of your Salesforce org.

Feel free to raise any issue you face in the issues section.
