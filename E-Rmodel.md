# Challenge_XALDIGITAL

Based on the provided data, we can design a simple Entity-Relationship (E-R) model with one main entity/table representing entities with attributes:

Person: This entity represents individuals with attributes such as first name, last name, contact information, etc.
Here's how the E-R model would look:

      Person
      ------
      - person_id (Primary Key)
      - first_name
      - last_name
      - company_name
      - address
      - city
      - state
      - zip
      - phone1
      - phone2
      - email
      - department

In this model:

person_id: A unique identifier for each person, serving as the primary key.
first_name: First name of the person.
last_name: Last name of the person.
company_name: Name of the company associated with the person.
address: Address of the person.
city: City of residence.
state: State of residence.
zip: ZIP code.
phone1, phone2: Contact phone numbers.
email: Email address.
department: Department within the company.
