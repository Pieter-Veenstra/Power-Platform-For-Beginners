# Task Create your first flow

## Story
Sarah, the Project Manager at XYZ Corp, is responsible for managing various projects and often receives project-related emails with attachments. She wants to automate the process of organizing these documents in a SharePoint folder and also wishes to be notified in a Microsoft Teams channel. Furthermore, she aims to acknowledge the sender by sending a thank-you email.

## Optional Supplemental Video
<!-- Insert content here -->

## Pre-lesson Warmup Quiz for Task 2
### 1. Question 1: What is a trigger in the context of Power Automate?
- A: A condition that must be met for an action to execute.
- B: An event that starts the flow.
- C: A type of loop.
- D: A premium feature in Power Automate.  
🌟 **Correct Answer: B**  
  _Optional Explanation:_ A trigger is an event that starts the flow in Power Automate.

### 2. Question 2: Which of the following is NOT a Microsoft 365 tool?
- A: SharePoint
- B: Outlook
- C: Slack
- D: Microsoft Teams  
🌟 **Correct Answer: C**  
  _Optional Explanation:_ Slack is not a Microsoft 365 tool.

### 3. Question 3: What is the purpose of a 'Thank-you email' in our flow?
- A: To acknowledge the sender.
- B: To start the flow.
- C: To store documents.
- D: To end the flow.  
🌟 **Correct Answer: A**  
  _Optional Explanation:_ The purpose of a 'Thank-you email' is to acknowledge the sender for sending the email with attachments.

## Written Lesson
### Introduction
In this lesson, you'll learn how to create an automated flow in Power Automate. The flow will trigger when a new email arrives in Outlook with an attachment. The flow will then save the attachment to a SharePoint folder, post a notification in a Microsoft Teams channel, and send a thank-you email back to the sender.

### Learning Objectives
By the end of this lesson, you should be able to:
1. Understand triggers and actions in Power Automate.
2. Use Outlook as a trigger.
3. Save email attachments to SharePoint.
4. Post messages in Microsoft Teams.
5. Send emails via Outlook.

### Steps

#### Step 1: Setting up the Trigger
1. Open Power Automate and create a new flow.
2. Select Outlook as the trigger and choose the 'When a new email arrives' option.

#### Step 2: Saving Attachment to SharePoint
1. Add a new action and select SharePoint.
2. Choose the 'Create file' option and specify the folder where you want to save the attachment.

#### Step 3: Posting a Message in Microsoft Teams
1. Add another action and select Microsoft Teams.
2. Choose the 'Post a message' option and specify the channel where you want to post the message.

#### Step 4: Sending a Thank-You Email
1. Add a final action and select Outlook.
2. Choose the 'Send an email' option and configure it to send a thank-you email to the sender.

### Summary
Congratulations! You've successfully created an automated flow in Power Automate that triggers with a new email, saves attachments to SharePoint, posts a message in Microsoft Teams, and sends a thank-you email.  
Don't forget to test your flow to make sure everything is working as expected.

## For Project-Based Lessons, Step-by-Step Guides on How to Build the Project
  In this step-by-step guide, you'll learn how to create an automated flow in Power Automate that performs several actions when a new email with an attachment arrives in Outlook.

### Steps
#### Step 1: Open Power Automate and Create a New Flow
  1. Open your web browser and go to the Power Automate website.
  2. Sign in with your Microsoft account.
  3. Click on 'Create' and then select 'Automated Flow'.

#### Step 2: Set up the Trigger
1. Search for 'Outlook' in the triggers section.
2. Select the trigger called 'When a new email arrives'.
3. Configure the trigger by specifying the folder you want to monitor for new emails.

#### Step 3: Save Email Attachment to SharePoint
1. Add a new action by clicking on '+ New step'.
2. Search for 'SharePoint' and select the action called 'Create file'.
3. Configure the action by specifying the SharePoint site and folder where you want to save the email attachment.

#### Step 4: Post a Message in Microsoft Teams
1. Add another action by clicking on '+ New step'.
2. Search for 'Microsoft Teams' and select the action called 'Post a message'.
3. Configure the action by specifying the team and channel where you want to post the message.

#### Step 5: Send a Thank-You Email
1. Add a final action by clicking on '+ New step'.
2. Search for 'Outlook' and select the action called 'Send an email'.
3. Configure the action by specifying the recipient, subject, and body of the thank-you email.


## Knowledge Checks
In this section, you'll find knowledge checks designed to test your understanding of the concepts and steps involved in creating the automated flow for Task 2. These will be interspersed throughout the lesson to ensure ongoing comprehension.

#### Knowledge Check 1: After Setting up the Trigger
**Question:** What is the role of the trigger in your Power Automate flow?
- A: To end the flow
- B: To initiate the flow
- C: To loop the flow
- D: To store data  
🌟 **Correct Answer: B**

#### Knowledge Check 2: After Saving Email Attachment to SharePoint
**Question:** Where is the email attachment saved in this flow?
- A: OneDrive
- B: SharePoint
- C: Microsoft Teams
- D: Outlook  
🌟 **Correct Answer: B**

#### Knowledge Check 3: After Posting a Message in Microsoft Teams
**Question:** What does the Microsoft Teams action do in this flow?
- A: Sends an email
- B: Starts the flow
- C: Posts a message in a channel
- D: Saves a file  
🌟 **Correct Answer: C**

## A Challenge
Sarah, the Project Manager, wants to further optimize the workflow. She wants the saved email attachments in SharePoint to be automatically tagged with metadata like the sender's name and project name.

Your task is to extend the existing Power Automate workflow to make this happen.

1. **Objective:** Extend the existing Power Automate workflow to add metadata for the saved attachment in SharePoint.

2. **Requirements:**
  - Add a new column in the SharePoint folder for the "Sender" and "Project Name".
  - The workflow should automatically populate these columns when a new attachment is saved.

3. **Bonus:** Add error handling that posts a message in Microsoft Teams if the workflow fails.

4. **Submission:** Share a screenshot or video of your successfully running workflow.


## Supplemental Reading, Learn Modules
In this section, you'll find a list of additional resources and articles designed to deepen your understanding of Power Automate, especially in the context of creating automated flows with pre-built connectors and triggers. While these readings are optional, they provide valuable insights and advanced knowledge.

### Supplemental Reading

- **Understanding Triggers in Power Automate:** A comprehensive guide to understanding how triggers work in Power Automate and how to use them effectively. [Read more](https://docs.microsoft.com/en-us/power-automate/getting-started)
  
- **Advanced SharePoint Actions:** Delve deeper into SharePoint actions in Power Automate. This resource explains how to set conditions, loops, and more. [Read more](https://docs.microsoft.com/en-us/power-automate/sharepoint-connector-actions)
  
- **Microsoft Teams and Power Automate:** Learn how to integrate Microsoft Teams with Power Automate to automate your workflows. [Read more](https://docs.microsoft.com/en-us/power-automate/teams-connector)
  
- **Email Automation with Outlook:** This article focuses on automating email tasks using Outlook and Power Automate. [Read more](https://docs.microsoft.com/en-us/power-automate/outlook-connector)

## Post-lesson Quiz for Task 2

### 1. Question 1: Which Microsoft 365 tool is used as the trigger in this flow?
- A: Microsoft Teams
- B: SharePoint
- C: Outlook
- D: OneDrive  
🌟 **Correct Answer: C**  
  _Optional Explanation:_ Outlook is used as the trigger to start the flow when a new email arrives.

### 2. Question 2: What does the SharePoint action do in this flow?
- A: Sends an email
- B: Starts the flow
- C: Posts a message in Microsoft Teams
- D: Saves the email attachment  
🌟 **Correct Answer: D**  
  _Optional Explanation:_ The SharePoint action saves the email attachment to a specified folder.

### 3. Question 3: What is the final action in this flow?
- A: Send a thank-you email
- B: Save the email attachment
- C: Post a message in Microsoft Teams
- D: Start the flow  
🌟 **Correct Answer: A**  
  _Optional Explanation:_ The final action in this flow is to send a thank-you email to the sender.

