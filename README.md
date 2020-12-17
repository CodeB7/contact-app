# contact-app
An application to store all the contact information

---

## Purpose
### The main objective of this project is to learn Web App and ReST API developement and get indepth information using Django Framework of Python.
---

## Features
* The application supports CRUD operations to:
    * Create a new contact.
    * See contact information.
    * Update existing contact.
    * Delete existing contact.
* The contact information should include:
    * Photograph of the person.
    * First, middle and last name.
    * Phone number with country code.
    * Email Address.
    * Home adress seggregated as Door No, street, city, State and Country.
* There is a facility to add any number of phone numbers as needed.
* There phone number can be categorised as:
    * Home
    * Work
    * Mobile
    * Custom
* Contact will have a field for Company information.
* There will also be fields for:
    * Nickname
    * Birthday
    * Website
    * Relationship
    * Notes/Description
---


## Tech Stack
### Programming Languages
* HTML 5
* CSS 3
* JavaScript (ES7)
* Python

### API Framework
* Django

### Databases
#### RDBMS
* Postgres SQL
#### No SQL
* Mongo DB

### Webserver
* Gunicorn

### Deployment Server
* Heroku
---

### Implementation details
#### 1. There will be an admin login so as to access the contact information.
#### 2. There will be 4 ReST APIs:
* get_contact_info - Get Contact Details
* update_contact_info - Update existing Contact details
* delete_contact_info - Delete existing contact details
* create_new_contact - Creating new contact.

#### 3. The contact information will be stored in Postgres SQL database and also in MongoDB for quick reference.
