# Task 2

## Story
Sarah, the CEO, wants to streamline the approval process for customer contracts. When a new contract is uploaded to SharePoint, an automatic notification is sent to the employee responsible for that customer. The employee can either approve the contract or make comments.

## Optional Supplemental Video
<!-- Insert content here -->

## Pre-lesson Warmup Quiz
This pre-lesson warmup quiz is designed to gauge your initial understanding of implementing business logic with conditions, loops, and expressions in Power Automate. This will help set the stage for the lesson.

### Questions
#### Question 1: What is a loop in the context of Power Automate?
- A: A feature that enables repeating actions
- B: A feature that sends emails
- C: A feature that triggers flows
- D: A feature that saves files  
🌟 **Correct Answer: A**  
📝 _Optional Explanation:_ In Power Automate, a loop enables you to repeat actions for each item in a list or until a condition is met.

#### Question 2: What are conditions used for in Power Automate?
- A: To initiate a flow
- B: To direct the flow based on certain criteria
- C: To end the flow
- D: To loop the flow  
🌟 **Correct Answer: B**  
📝 _Optional Explanation:_ Conditions in Power Automate are used to direct the flow based on certain criteria or conditions.

#### Question 3: What are expressions used for in Power Automate?
- A: To send emails
- B: To calculate and manipulate data
- C: To save files
- D: To initiate a flow  
🌟 **Correct Answer: B**  
📝 _Optional Explanation:_ Expressions in Power Automate are used to calculate and manipulate data within the flow.

## Written Lesson
### Introduction

In this lesson, you'll learn how to streamline the approval process for customer contracts using Power Automate. You will set up an automated system that sends approval requests to the responsible employee when a new contract is uploaded to SharePoint.

### Learning Objectives

By the end of this lesson, you should be able to:
1. Set up triggers in SharePoint for new document uploads.
2. Send automated approval requests via Teams or Outlook.
3. Use conditions to check and update approval status.
4. (Optional) Generate a list of previous contracts for review.

### Steps

#### Step 1: Setting up the SharePoint Trigger

1. Log in to Power Automate and create a new flow.
2. Set up the trigger using SharePoint's 'When a new item is created' action.

#### Step 2: Sending an Approval Request

1. Add a new action to send an approval request.
2. Choose whether to send the request via Teams or Outlook.

#### Step 3: Implementing Conditions for Approval

1. Use a condition to check the 'Approval Status' in SharePoint.
2. Update the 'Approval Status' column based on the condition.

#### Step 4: (Optional) Reviewing Previous Contracts

1. Add a loop to generate a list of all previous contracts for that customer for review.

### Summary

Congratulations! You have successfully set up an automated approval process for customer contracts in SharePoint using Power Automate. You should now be comfortable with setting up triggers, sending automated requests, and using conditions for approval.

## For Project-Based Lessons, Step-by-Step Guides on How to Build the Project
### Overview

This guide will walk you through the steps to set up an automated contract approval process in SharePoint using Power Automate.

### Prerequisites

Before you begin, make sure you have:
- A Microsoft 365 account
- Basic understanding of Power Automate
- Access to SharePoint and either Teams or Outlook

### Steps

#### Step 1: Set Up the SharePoint Trigger

1. Log in to Power Automate.
2. Create a new flow.
3. Add the SharePoint 'When a new item is created' action as the trigger.
4. Configure the trigger by specifying the SharePoint List: 'Customer Contracts'.

#### Step 2: Send the Approval Request

1. Add a new action to send an approval request.
2. Configure the action by specifying the employee responsible for that customer.
3. Choose to send the request via Teams or Outlook.

#### Step 3: Check Approval Status with Conditions

1. Add a condition to check the 'Approval Status' in SharePoint.
2. If approved, update the 'Approval Status' column to 'Approved'.
3. If not approved, update the 'Approval Status' to 'Pending' and add comments.

#### Step 4: (Optional) Review Previous Contracts

1. Add a loop to generate a list of all previous contracts for that customer.
2. Display the list in Teams or Outlook for review by the employee responsible.

### Summary

You have now successfully set up an automated contract approval process. The responsible employee will receive an approval request when a new contract is uploaded to SharePoint, and the system will track the approval status based on the employee's response.


## Knowledge Checks
In this section, you'll find knowledge checks designed to test your understanding of the concepts and steps involved in setting up an automated contract approval process in Power Automate.

### Knowledge Checks

#### Knowledge Check 1: After Setting Up the SharePoint Trigger
- Question: What is the role of the SharePoint trigger in this flow?
  - A: To end the flow
  - B: To initiate the flow
  - C: To loop the flow
  - D: To store data  
  🌟 **Correct Answer: B**  
  📝 _Optional Explanation:_ The SharePoint trigger initiates the flow when a new contract is uploaded.

#### Knowledge Check 2: After Sending the Approval Request
- Question: How is the approval request sent to the employee?
  - A: Via Teams
  - B: Via Outlook
  - C: Via either Teams or Outlook
  - D: Via SharePoint  
  🌟 **Correct Answer: C**  
  📝 _Optional Explanation:_ The approval request can be sent via either Teams or Outlook, based on configuration.

#### Knowledge Check 3: After Checking Approval Status
- Question: What happens if the contract is not approved?
  - A: The flow ends
  - B: The 'Approval Status' is updated to 'Pending'
  - C: A new contract is generated
  - D: The contract is deleted  
  🌟 **Correct Answer: B**  
  📝 _Optional Explanation:_ If the contract is not approved, the 'Approval Status' is updated to 'Pending' and comments can be added.


## A Challenge
### Challenge Overview

Now that you've learned how to set up an automated contract approval process, your challenge is to extend this flow to include a notification system that informs senior management whenever a contract is rejected.

### Objectives

1. Modify the existing flow to include a notification system.
2. Use conditions to check if a contract is rejected.
3. If rejected, send an automated notification to senior management via Teams or Outlook.

### Steps

#### Step 1: Update the Existing Flow

1. Open your existing flow in Power Automate.
2. Add a new condition to check if the 'Approval Status' is 'Rejected'.

#### Step 2: Add a Notification Action

1. If the condition is met (i.e., the contract is rejected), add an action to send a notification.
2. Configure the notification to be sent to senior management.

#### Step 3: Test the Notification System

1. Test your updated flow by uploading a contract and setting its 'Approval Status' to 'Rejected'.
2. Verify that the senior management receives a notification.

### Summary

By completing this challenge, you'll gain practical experience in extending an existing Power Automate flow to include additional features like a notification system for senior management.

## Supplemental Reading, Learn Modules
In this section, you'll find a list of additional resources and articles designed to deepen your understanding of implementing business logic in Power Automate, especially in the context of setting up an automated contract approval process.

### Supplemental Reading

- **Understanding Conditions in Power Automate**: A comprehensive guide to understanding how conditions work in Power Automate and how to use them effectively. [Read more](https://docs.microsoft.com/en-us/power-automate/add-condition)

- **Automating Business Processes with Power Automate**: Learn how to implement business logic using conditions, loops, and expressions in Power Automate. [Read more](https://docs.microsoft.com/en-us/power-automate/business-process-flows-overview)

### Learn Modules

- **Implementing Business Logic in Power Automate**: This Microsoft Learn module takes you through the steps of implementing complex business logic in your flows. [Start Learning](https://learn.microsoft.com/en-us/training/paths/automate-process-power-automate/)

- **Managing Approvals in Power Automate**: This module will teach you how to set up and manage approval workflows. [Start Learning](https://learn.microsoft.com/en-us/training/modules/approvals-power-automate/)

## Post-lesson Quiz
This quiz is designed to test your understanding of implementing business logic with conditions, loops, and expressions in Power Automate. It's a great way to check if you've grasped the key concepts from this lesson.

1. **Question 1**: What is the role of conditions in this Power Automate flow?
   - A: To initiate the flow
   - B: To direct the flow based on certain criteria
   - C: To end the flow
   - D: To loop the flow  
   🌟 **Correct Answer: B**  
   📝 _Optional Explanation:_ Conditions in Power Automate are used to direct the flow based on certain criteria or conditions.

2. **Question 2**: What does a loop enable you to do in Power Automate?
   - A: Send emails
   - B: Repeat actions for each item in a list or until a condition is met
   - C: Save files
   - D: Trigger the flow  
   🌟 **Correct Answer: B**  
   📝 _Optional Explanation:_ In Power Automate, a loop enables you to repeat actions for each item in a list or until a condition is met.

3. **Question 3**: What are expressions used for in Power Automate?
   - A: To send emails
   - B: To calculate and manipulate data
   - C: To save files
   - D: To initiate the flow  
   🌟 **Correct Answer: B**  
   📝 _Optional Explanation:_ Expressions in Power Automate are used to calculate and manipulate data within the flow.
