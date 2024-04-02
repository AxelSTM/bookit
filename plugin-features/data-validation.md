# Data Validation

While booking an appointment, users must fill the required fields correctly due to the data validation rules. Admin of website should also the data validation rules while creating a new service, a new category, a new customer, a new staff. Now, we will show examples for each data one by one and it will help to fill the booking forms correctly with valid data.

#### Full Name Validation

Name of Customer should be more than 3 characters & less than 25 characters when you want to create a new staff or register a new customer:

![](<../.gitbook/assets/image (21).png>)

#### Phone Number Validation

Phone numbers should not be less than 9 characters, it may include "+"/"-" signs. But the rejected symbols for the phone numbers are not considered a valid phone number:

![](<../.gitbook/assets/image (210).png>)

#### Email Validation

Email must contain "@" with a domain name. Any rejected symbols will throw invalid data message:

![](<../.gitbook/assets/image (108).png>)

#### Service Validation

When a new service is added, all required data should be filled with the proper information. Adding service requires the service price, category, correct title. Without a price, category, or valid service title, a new service will not be created:

![](<../.gitbook/assets/image (145).png>)

#### Category Validation

A new category or editing category should not be less than 3 characters:

![](<../.gitbook/assets/image (46).png>)

#### Customer Validation:

A new customer or editing customer should follow the above validation rules for full name, email and, phone number

![](<../.gitbook/assets/image (147).png>)
