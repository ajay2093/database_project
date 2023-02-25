# Exercise for project 2:

## Users Profile and their Roles:
For the user profile, we can define the following attributes:

* User ID: A unique identifier for each user
* First Name: The first name of the user
* Last Name: The last name of the user
* Email: The email address of the user
* Password: The password of the user
* Role: The role of the user in the system, such as admin, manager, or employee

## Documents Analysis:
For documents analysis, we can define the following attributes:

* Document ID: A unique identifier for each document
* Document Name: The name of the document
* Upload Date: The date the document was uploaded
* Last Modified: The date the document was last modified
* Owner ID: The user ID of the owner of the document
* Tags: Tags assigned to the document to categorize it

## Topics:
For topics, we can define the following attributes:

* Topic ID: A unique identifier for each topic
* Topic Name: The name of the topic
* Description: A brief description of the topic

## Schema (Tables):

### Users Table:

* User ID
* First Name
* Last Name
* Email
* Password
* Role

### Documents Table:
* Document ID
* Document Name
* Upload Date
* Last Modified
* Owner ID
* Tags

### Topics Table:

* Topic ID
* Topic Name
* Description

## Initial Design:

We can design the following modules based on the above schema:

### User Management Module:
This module will be used to manage user accounts. The module will allow admins to add, modify, and delete user accounts. Users will be able to view and update their profiles.

### Document Management Module:
This module will be used to manage documents. Users will be able to upload, modify, and delete documents. The module will also allow users to add tags to documents to categorize them.

### Topic Management Module:
This module will be used to manage topics. Admins will be able to add, modify, and delete topics. Users will be able to view and search for topics.
