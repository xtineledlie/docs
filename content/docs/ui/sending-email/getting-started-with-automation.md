---
layout: page
weight: 0
group: marketing-campaigns
title: Getting Started with Automation
seo:
  title: Getting Started with Automation
  description: Use Automation to create an automated email series or drip campaign targeted towards a specific audience.
  keywords: automation, triggered email, automated email, welcome series
navigation:
  show: true
---

<call-out>

Automation is available as part of the Advanced Marketing Campaigns package. To access this feature, please upgrade to Advanced Marketing Campaigns from [Your Products](https://app.sendgrid.com/account/billing).

</call-out>

Automation allows you to send a recurring email or drip series to contacts automatically at a cadence you define. Once you create an Automation, you can trigger them to send automatically by adding new recipients to a chosen list, saving you time.


With Automation, you could build email campaigns to:

* Welcome new contacts when they join your list with a warm message and introductory tips.
* Engage contacts who’ve downloaded an asset from you with follow-up content.
* Promote an upcoming event to a list of invitees with a series of reasons to attend.

## Getting Started with Automation

If you haven’t done so already, you’ll need to complete the following before building your first automation:

* Add a [notification]({{root_url}}/ui/account-and-settings/notifications/) email
* Create [Unsubscribe Groups]({{root_url}}/ui/manage-contacts/create-and-manage-unsubscribe-groups)
* Add a [sender]({{root_url}}/ui/sending-email/senders/) (optional)

## Create an Automation

Once you've completed the prerequisites, you’re ready to start building your first automation. You can start with a pre-built Welcome Series and make it your own, or start from scratch by selecting **Custom Automation**.

### Create a Custom Automation

*To create a Custom Automation:*

1. Navigate to **Automations** and then click **Create an Automation**.
1. Under Custom, click **Select**.
1. Give the series a name. This is for your reference and will not be visible to your contacts.
1. Select the entry criteria. Today, your entry criteria will be the first time a [contact is added to a list]({{root_url}}/ui/manage-contacts/create-and-manage-contacts/#adding-contacts). You can choose an existing list, or you can create a new one here.

<call-out>

Contacts will only receive your automation if you add them to the list you select for entry criteria *after* you set the automation live.

</call-out>

5. Select the exit criteria for this series. You can choose from "Contacts will leave the series one they've received all the emails" or "Contacts will leave the series if they no longer meet the entry criteria". 

<call-out>

If you select “no longer meet entry criteria”, before each email in your series sends, Automation will check to make sure each recipient is still on the entry criteria list. If they aren’t, they won’t get the email. For more information on deleting contacts or removing them from lists, see [link text]({{root_url}}ui/manage-contacts/create-and-edit-contacts/#edit-or-remove-contacts-from-a-list).

</call-out>

6. Select an [Unsubscribe Group]({{root_url}}/ui/sending-email/create-and-manage-unsubscribe-groups/#create-an-unsubscribe-group). This Unsubscribe Group will apply to all emails in your Automation.
7. Add a [category]({{root_url}}/glossary/categories/) to the automation (optional). Categories are useful for [comparing performance]({{root_url}}/ui/analytics-and-reporting/category-comparison/) across different types of email you send.
8. Select the send time for the first email. You can choose to send the first email instantly, or you can set a delay of days or hours from the time meet the entry criteria.
9. Build your email(s) by clicking **Add Email Content**.
10. Choose a template, then use your preferred [editor]({{root_url}}/ui/sending-email/editor/) to craft your content.
11. If you did not do so within the editor, you can add a subject line and select a sender from the Edit Automation page.
12. To add more emails to this automated series, click **Add an Email**.
13. Choose how long to wait before sending the next email. This time will be relative to the preceding email.

14. Once you have created all of your emails for the automation, click **Set Live**.

### Duplicate an Automation

*To duplicate an automation:*

1. Navigate to Automations.
1. Find the automation you want to duplicate.
1. Select the Action Menu to the right of the automation.
1. Click **Duplicate**.
1. Once you create the duplicate, the automation will open to the edit page. From here, you can change any or all of the settings within the automation.

### Use the Pre-Built Welcome Series

The pre-built Welcome Series automation provides a jumping off point to inspire you to create your own tailored welcome series.

*To create a Welcome Series:*

1. Navigate to **Automations** and then click **Create an Automation**.
1. Under Welcome, click **Select**.
1. Update the automation name (this is for your reference and will not be visible to your contacts).
1. Review the entry criteria to decide if you’d like to update it. The default entry criteria is “The first time a contact is added to All Contacts”.
1. Review the exit criteria to decide if you’d like to update it.
1. Select an [Unsubscribe Group]({{root_url}}/ui/sending-email/create-and-manage-unsubscribe-groups/#create-an-unsubscribe-group). This Unsubscribe Group will apply to all emails in your Automation.
1. Add a [category]({{root_url}}/glossary/categories/) to the automation (optional). Categories are useful for [comparing performance]({{root_url}}/ui/analytics-and-reporting/category-comparison/)  across different types of email you send.
1. The pre-built Welcome Series has three placeholder emails by default. You’ll need to edit the subject line and content of each email. You may decide to remove or add emails to the pre-built. 
1. If you did not do so within the editor, you can add a subject line and select a sender from the Edit Automation page.
1. To add more emails to this automated series, click **Add an Email**.
1. Choose how long to wait between each email in the series. This time will be relative to the preceding email.
1. Once you have created all of your emails for the automation, click **Set Live**.

<call-out type="warning">

If you keep the entry criteria as "All Contacts" it's important to remember that any recipient you add to your Automation contacts after you set the welcome series live will be entered into the automation. Use "All Contacts" with caution to avoid sending a welcome series to contacts that aren't actually new to you.

</call-out>

## Manage Automations

### Edit an Automation

You can edit the content, subject line, and sender for any emails in your automation.

*To edit an automation:*

1. Navigate to **Automations** and select the series you want to edit.
1. Click **Edit** on each email you’d like to modify. 
1. Make your changes in the editor, then click **Save**. 
1. Click the arrow in the upper left-hand corner. 
1. Below the email you’ve edited, you’ll see an alert that changes have not yet been applied to the live automation. When you’re ready to apply them, click **Save and Apply**.  

### Disable an Automation

*To disable an automation:*

When you disable an automation, all emails in your automation will stop sending unless you set it live again. No new contacts will be entered into your automation while it's disabled. If you set the automation live again, contacts who entered the automation before it was disabled will continue receiving emails again according to where they left off.

1. Navigate to **Automations** and select the series you want to stop.
1. Select the Action Menu to the right of the Automation.
1. Click **Disable Automation** in the upper right corner.


*To set a disabled automation live again:*

1. Navigate to **Automations** and select the series you want to re-enable.
1. Select the Action Menu to the right of the Automation.
1. Click **Set Live** in the upper right corner.

<call-out>

When you re-enable the automation, contacts who previously entered the series will continue receiving emails where they left off in the series. Contacts who met your entry criteria during the disabled period will not be added to the automation. For this reason, do not add users to lists that are used as the entry criteria for automations in a disabled state.

</call-out>

### Delete an Automation

*To delete an automation:*

1. On the automation dashboard, find the automation you want to delete.
1. Hover over the action menu and select the delete icon.
1. To delete the automation, click **Confirm**.
