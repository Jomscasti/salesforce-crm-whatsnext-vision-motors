# Salesforce CRM Implementation for WhatsNext Vision Motors

## Project Overview

This project implements a comprehensive Salesforce Customer Relationship Management (CRM) system for **WhatsNext Vision Motors**, aimed at streamlining vehicle inventory management, customer interactions, dealer assignments, order processing, test drives, and service requests. The solution leverages Salesforce custom objects, fields, relationships, Lightning apps, flows, and Apex automation to improve operational efficiency and automation.

## Demo

[View Live Demo](YOUR_DEMO_LINK_HERE)

## Features

* **Custom Objects:** Vehicle, Dealer, Customer, Order, Test Drive, Service Request
* **Lightning App:** WhatsNext Vision Motors with navigation tabs for all objects
* **Automation:**

  * Record-triggered flows for auto-assigning dealers and test drive reminders
  * Apex triggers to validate stock and update inventory
  * Batch jobs for processing pending orders
* **Comprehensive Data Model:** Proper relationships, picklist fields, and lookups

## Installation / Deployment

1. Clone this repository:

   ```bash
   git clone https://github.com/username/salesforce-crm-whatsnext-vision-motors.git
   ```
2. Deploy metadata to Salesforce using **Salesforce CLI (SFDX)**:

   ```bash
   sfdx force:source:deploy -p apex/
   sfdx force:source:deploy -p flows/
   sfdx force:source:deploy -p lightning-apps/
   sfdx force:source:deploy -p objects/
   ```
3. Verify objects, fields, apps, flows, and triggers in your Salesforce org.


## Contributors

* **Jomari Castillo** – Project Lead / Apex Development / Flow Implementation
