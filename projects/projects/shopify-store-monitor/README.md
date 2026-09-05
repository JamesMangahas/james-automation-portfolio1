# Shopify Store Monitor

This is one of the more advanced n8n workflows I've built.

I made this workflow to monitor products from Shopify stores and keep track of changes in their product information.

## How it works

The workflow starts with a list of stores and goes through them one by one.

It then:

- Gets the list of stores
- Loops through each store
- Fetches the products
- Processes and organizes the product data
- Detects changes
- Logs the product information to Google Sheets
- Separates actual changes into another sheet

### Workflow

Manual Test Trigger
→ Store List
→ Loop Over Stores
→ Fetch All Products
→ Flatten & Detect Changes
→ Log All Rows to Sheet
→ Only Real Changes
→ Log Changes Only Sheet

## Tools I used

- n8n
- Shopify
- JavaScript
- Google Sheets

## Why I made this

I wanted to build something more advanced than a simple automation.

This project gave me a chance to work with loops, product data, JavaScript, and detecting changes between data.

## What I learned

While working on this project, I learned more about:

- Looping through multiple items
- Working with Shopify store data
- Using JavaScript inside n8n
- Processing JSON data
- Detecting changes in data
- Working with Google Sheets
- Building more complex workflows
- Testing and troubleshooting automations

## Workflow Screenshot

![Shopify Store Monitor Workflow](workflow.png)<img width="1528" height="773" alt="234" src="https://github.com/user-attachments/assets/392b5d45-51ba-43b9-9a23-1ffd4632ca59" />


## Status

Completed.

I'm continuing to learn n8n and build more automation projects.
