# Getting Started

You can use this Yet Another Mail Merge(YAMM) add-on to create a personalized emails for each receiver automatically.
In this guide you will learn how to create emails with the receiver's name.

[Step 1. Install an add-on](#step-1-install-an-add-on)
[Step 2. Create an email template](#step-2-create-an-email-template)
[Step 3. Configurate a list recipients](#step-3-configurate-a-list-recipients)
[Step 4. Send emails](#step-4-send-emails)

## Step 1. Install an add-on

YAMM is an add-on for Google Sheets. Click the [following link](https://gsuite.google.com/marketplace/app/yet_another_mail_merge_yamm/52669349336?pann=cwsdp&hl=en-GB) to install YAMM. 
You need accept the authorizations to use YAMM.

Also watch video-tutorial "[How to install Yet Another Mail Merge on your Google account](https://youtu.be/o2Jh1ABd7XM)".

## Step 2. Create an email template

Open [Gmail](https://mail.google.com/) and click *+Compose*. Write the email that you want.
Replace a name with a marker in the format `{{First Name}}` in the text of the email. 

Example template:

```
Hello {{First Name}},

Thank you for starting using Yet Another Mail Merge. 
We want to help you make it easier to send emails. Read how to get started in Help.

Best,
Team YAMM

```
Gmail will save the email in the **Drafts** folder automatically. 

## Step 3. Configurate a list recipients

Create a [new spreadsheet](https://docs.google.com/spreadsheets/u/0/?tgif=c) for Google Sheets.
On row 1, type the name of each column for each item of information.
We want to add the receiver's first names and email addresses. We'll write these headers as follows:

image

Fill your spreadsheet with all the information you need, row by row.

You can import your contacts from [Google Contacts](https://support.yet-another-mail-merge.com/hc/en-us/articles/211751125-Import-your-contacts-from-Google-Contacts). 

## Step 4. Send emails

In your spreadsheet select **Add-ons** > **Yet Another Mail Merge(YAMM)** > **Start Mail Merge**.

Enter your name in the **Sender Name** field. Users will see this name in the from field in the received email. 
Select your template from the drop-down list **Email Template**.

Test email to yourself. Click **Receive a test email** and after click the blue banner. The test email will open in your Gmail.

Once you're ready to send your mail, click **Send emails**.

**What next**:

* More about [personalization emails](https://support.yet-another-mail-merge.com/hc/en-us/sections/202544725-Personalize-Your-Email)
* How to [analyze your tracking report emails](https://support.yet-another-mail-merge.com/hc/en-us/articles/115000786545-Analyze-your-tracking-report-emails-to-do-better-campaigns)



