# ISO CRM - New Lead Automation

This is one of the n8n projects I built while learning workflow automation.

The idea was pretty simple: when a new lead comes in, I wanted n8n to handle the repetitive parts instead of doing everything manually.

## How it works

The workflow starts when a lead is received through a webhook.

It then:

- Checks the information using an IF node
- Organizes the lead information
- Adds the lead to Google Sheets
- Sends a message automatically

### Workflow

Webhook → IF → Edit Fields → Google Sheets → Gmail

## Example

I tested the workflow using a sample lead:

**Name:** John Smith  
**Company:** ABC Manufacturing  
**Employees:** 80  
**Interest:** ISO 45001

The lead information is processed by n8n and then added to the Google Sheets CRM.

## Tools I used

- n8n
- Webhook
- IF
- Edit Fields
- Google Sheets
- Gmail

## Why I made this

I wanted to learn how different tools can work together in one automation.

I also wanted to build something that could be useful for a real business, especially for handling new leads and reducing manual data entry.

## What I learned

While making this project, I learned more about:

- Webhooks
- Connecting different services in n8n
- Working with data between nodes
- IF conditions
- Google Sheets integration
- Sending automated emails
- Testing and fixing workflow problems

## Status

Completed.

I'm still learning n8n and plan to add more projects as I build them.<img width="1919" height="1015" alt="porfolio" src="https://github.com/user-attachments/assets/4e42ccd9-02f0-4203-a038-f9f5cccf1991" />
