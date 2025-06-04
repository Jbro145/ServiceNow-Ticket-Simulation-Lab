Below is the link to my Loom account where I demonstrate this lab. 
https://www.loom.com/share/2dd73b8b4da14836a2799ba1a2e3c875?sid=a3140f3f-b176-40f7-b873-7e9f6890dfc1

# ServiceNow-Ticket-Simulation-Lab
This project leverages a ServiceNow developer instance for hands-on exploration and ticket creation. Its purpose is to acquaint users with the functionalities of this widely-used ticketing platform and to build proficiency in navigating the ticket interface.
This document outlines the steps performed to create a new incident ticket in ServiceNow.

## Prerequisites

* Access to a ServiceNow instance (e.g., a Personal Developer Instance - PDI, or a company instance).
* Valid user credentials for logging into the ServiceNow instance.

## Lab Steps

The following steps were performed to create an incident ticket in ServiceNow:

### 1. Log in to ServiceNow

1.  **Open your web browser:** Navigate to your ServiceNow instance URL (e.g., `https://devXXXXX.service-now.com`).
2.  **Enter Credentials:** Input your **User name** and **Password** in the respective fields.
3.  **Click Log in:** Click the "Log in" button to access the ServiceNow platform.

### 2. Navigate to Incident Creation

1.  **Use the Navigator Filter:** In the left-hand navigation pane, locate the "Filter navigator" search bar.
2.  **Search for "Incident":** Type `incident` into the filter navigator.
3.  **Select "Create New":** Under the "Incident" application menu, click on **Create New**.

### 3. Fill in Incident Details

1.  **Caller:** In the "Caller" field, begin typing the name of an existing user (e.g., `Abel Tuter`). Select the appropriate user from the auto-suggested list.
    * *Note: In a real scenario, this would typically be the user reporting the issue.*
2.  **Short description:** Provide a concise summary of the issue (e.g., `Cannot access corporate email`).
3.  **Urgency:** Select the level of urgency (e.g., `1 - High`, `2 - Medium`, `3 - Low`). For this lab, `2 - Medium` was selected.

### 4. Submit the Incident

1.  **Click Submit:** Once all necessary fields are populated, click the **Submit** button located at the top or bottom of the form.

## Conclusion

This lab successfully demonstrated the process of creating a new incident ticket in ServiceNow, from logging in to submitting the complete incident record. This fundamental skill is essential for IT support and service management roles utilizing the ServiceNow platform.
