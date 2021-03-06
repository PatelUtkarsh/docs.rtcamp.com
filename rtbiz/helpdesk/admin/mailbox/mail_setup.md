# Mail Setup

It is required to configure a mailbox for the Helpdesk system for sending emails/ notifications to the users. Admins can set up multiple mailboxes.

You have the option to set up the mailbox during the Set up wizard (Ref [1.1 Setup Wizard. Point 5](http://docs.rtcamp.com/rtbiz/helpdesk/admin/setup.html#5-mailbox-setup)) or you could do the same  by going to **Helpdesk Settings -> Mail Setup**

![Mail_Setup](http://git.rtcamp.com/rtbiz/rtbiz/uploads/22db71ed9a5d9ce1f4479aeca9a09144/Mail_Setup.png)



### 1. Mailboxes Set Up


 **i. Email**

 Add here the email id you want to setup as a mailbox.

**ii. Password**

Enter the password for the above email id.

**iii. Provider**

Select any provider from the options.

**iv. Test Connection**

Click Test Connection to add the mailbox.

![Mailbox_Setup](http://git.rtcamp.com/rtbiz/rtbiz/uploads/a1d46c4c26b2e3d5fdcb43a10f5dee2b/Mailbox_Setup.png)

**v. Connected Mailbox**

If added successfully the connected mailbox  will show like this

![mb_setup1](https://cloud.githubusercontent.com/assets/8191145/8983819/e9c8f612-36ea-11e5-93fe-6c2ea37c1d92.png)

You have the option to configure folders to be parsed and select Products and Staff members connected with the mailbox(es).

![mb_setup](https://cloud.githubusercontent.com/assets/8191145/8983820/e9ef99de-36ea-11e5-9012-182ffd0077bf.png)

**vi. Another Mailbox**

Click Add Another Mailbox button and repeat the same steps as above in order to set up another mailbox account.

**vii. Send email to mailbox for creating tickets**

Once setup, the Ticket Authors or customers can send emails to the mailboxes and their tickets will be created in the Helpdesk.


### 2. Mailbox Reading


**i. Enable** : When enabled, ticket Authors can directly send mails to the mailboxes and their tickets will be created in the Helpdesk. Ticket authors and Staff can add followups via mail.

**ii. Disable** :When Disabled, tickets will not be created via mail and new followups by customer and Staff cannot be added via mail.

![enable_mailbox_reading](https://cloud.githubusercontent.com/assets/8191145/6487363/bee796b8-c2b6-11e4-8b84-0f761513cb48.png)

### 3. Reply Via Email

This is used to allow or block the email followups.

**i. Enable** : Ticket Authors and staff members connected to the ticket can create followups to the tickets when replying via email

**ii. Disable** : Ticket Authors and staff members connected to the ticket can not create followups to the tickets when replying via email

![Reply via Email](http://git.rtcamp.com/uploads/rtbiz/rtbiz-helpdesk/46a4d1e93f/Reply_via_Email.png)

### 4. Outgoing Emails' Mailbox

Select any of the configured Mailboxes which will be used to send outgoing emails/notifications.

![outgoing_emails_mailbox](https://cloud.githubusercontent.com/assets/8191145/6487585/1f68f206-c2b8-11e4-9ba1-c0d6d52a2612.png)


### 5. Outgoing Emails' FROM Name

Here Administrators can set any name to be used for outbound emails. This Name will be used as ```from: Name <email address>``` for all outgoing emails as shown in the screenshot below

![outgoing_sysname_helpdesk](https://cloud.githubusercontent.com/assets/8191145/6501154/efa7c12c-c33a-11e4-8b76-936fc21bd2a2.png)

![name](https://cloud.githubusercontent.com/assets/8191145/6501114/52b3b830-c33a-11e4-9dad-5f6f832b66a5.png)


### 5. Blacklist Emails

These are email addresses which are barred by the Administrator from creating any ticket.

Enter email id's to be blacklisted and blocked by Helpdesk as in screenshot below. Each  mail id should be in separate line and commas should** not** be used.

![blacklist_emails](https://cloud.githubusercontent.com/assets/8191145/6487587/1f9e311e-c2b8-11e4-82ab-00a51d017331.png)

