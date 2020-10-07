# Getting Started

You can use this Yet Another Mail Merge(YAMM) add-on to create personalized emails for each recipient automatically.
In this guide you will learn how to create emails with the recipient's name.

* [Before you start](#before-you-start)

* [Step 1. Create an email template](#step-1-create-an-email-template)

* [Step 2. Configure a list recipients](#step-2-configure-a-list-recipients)

* [Step 3. Send emails](#step-3-send-emails)

## Before you start

YAMM is an add-on for Google Sheets. Make sure that you have installed the add-on.


For more information about the install an add-on read the [article](https://support.yet-another-mail-merge.com/hc/en-us/sections/202481589-Install-YAMM) or watch the [video tutorial](https://youtu.be/o2Jh1ABd7XM).

## Step 1. Create an email template

Open [Gmail](https://mail.google.com/) and click **+Compose**. 

Compose the email template. We want to create an email in which the recipient's name will be inserted automatically. Therefore, replace a name with a marker in the format `{{First Name}}` in the text of the email. 

Example template:

```
Hello {{First Name}},

Thank you for starting using Yet Another Mail Merge. 
We want to help you make it easier to send emails. Read how to get started in Help.

Best,
Team YAMM

```

Gmail will save the email in the **Drafts** folder automatically. 

## Step 2. Configure a list recipients

Create a [new spreadsheet](https://docs.google.com/spreadsheets/u/0/?tgif=c) for Google Sheets.

We need to automatically add two parameters: the names of recipients and their email addresses. In line 1, enter a name for the column for each parameter. The name of the column with recipient names must match the marker from the email template — **First Name**. The name of the column with email addresses — **Email**.

Fill your spreadsheet with all the information. Example:

![](/images/yamm-step3.png)

You can also import your contacts from [Google Contacts](https://support.yet-another-mail-merge.com/hc/en-us/articles/211751125-Import-your-contacts-from-Google-Contacts). 

## Step 3. Send emails

In your spreadsheet select **Add-ons** > **Yet Another Mail Merge(YAMM)** > **Start Mail Merge**.

Fill in the fields:

* **Sender Name** — enter your name, users will see this name in the **From** field in the received email.
* **Email Template** — select your template from the drop-down list.

Click **Receive a test email** if you want to send a test email to yourself. Now that you have tested that everything is fine, click **Send emails**.

### What next:

* More about [personalization emails](https://support.yet-another-mail-merge.com/hc/en-us/sections/202544725-Personalize-Your-Email)
* How to [analyze your tracking report emails](https://support.yet-another-mail-merge.com/hc/en-us/articles/115000786545-Analyze-your-tracking-report-emails-to-do-better-campaigns)



