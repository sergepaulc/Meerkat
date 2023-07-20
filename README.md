# Meerkat Dev

## Introducing Meerkat

While there are a lot of tools for software engineers for tracking engineering stories, tasks, issues, and bugs, there are very few tools for product managers.

In many cases, product managers have to develop many documents and upload them on a wiki to share them accross an organization.

Meerkat intends to change that :)

Meerkat provides a complete tool for product managers to manage the product life cycle of their products.

Meerkat includes everything that a product manager needs to document, track, and share about his product with his team, and in particular:

- The product use cases
- The product requirements
- The product design and architecture
- The product features
- The road map and the key milestones
- The releases
- The Customer feedback
- The product bugs
- The beta testing of the product
- The team members

All those features are provided in an easy-to-use workflow through a Web interface.


## Meerkat Features

In Meerkat, product development starts with use cases and ends in a release.
Product development is made of teams, and involves risks that need to be assessed during the development process.
And, products have road maps.

Meerkat provides the following modules:

### Use cases:
+ Attributes:
  + Identification
  + Title
  + Category
  + Target market
  + Target user
  + Status
  + History

+ Is defined by: A description
+ Involves: A product manager

### Requirements:
+ Attributes:
  + Identification
  + Title
  + Origin
  + Category
  + Parent/Child
  + Priority
  + Status
  + History

+ Is defined by: A description
+ Implements: A use case
+ Is linked to: A release
+ Involves: A product manager

### Design:

+ Attributes:
  + Identification
  + Title
  + Category
  + Parent/Child
  + Status
  + History

+ Is defined by: A description, or a documentation, or an implementation
+ Implements: A requirement, or a use case
+ Involves: a designer or an architect

### Features:
+ Attributes:
  + Identification
  + Title
  + Category
  + Status
  + History
+ Is defined by: A description,a documentation, an implementation
+ Implements: A use case, a requirement
+ Involves: A development engineer
+ Is linked to: A test, a release

### Tests:
+ Attributes:
  + Identification
  + Title
  + Category
  + Pass/Fail Criteria
  + Status
  + History
+ Is defined by: A description,a documentation, an implementation
+ Implements: A feature
+ Involves: A test engineer
+ Is linked to: A release

### Beta:
+ Attributes:
  + Customer Identification
  + Release Deployed
  + Features Enabled
  + Bugs Reported
  + Feature Feedback
  + History

+ Customer attributes:
  + Name
  + Location

### Releases:
+ Attributes:
  + Release Date
  + Pass/Fail Criteria
  + List of Features
  + Risks
  + Bugs
  + Location/Market
  + Product Documentation (Attachment)
  + Marketing Materials (Attachment)
  + Press Releases (Attachment)

### Teams:
+ Product teams:
  + Product management (head/members)
  + Design/Architecture
  + Development
  + Testing
  + Beta
  + Release
  + Management
+ Team attributes:
  + Name
  + Description
  + Picture
  + Permissions 
+ Member attributes:
  + First/last name
  + Team
  + Position
  + Picture
  + Permissions
+ Team/Member responsibility:
  + Use Case
  + Requirements
  + Design
  + Features
  + Testing
  + Beta
  + Release
  + Risks
  + Road Map

### Road map:
+ Attributes:
  + Date
  + Goals
  + Release
  + Features
  + Markets
  + Customers  

### Risks:
+ Attributes:
  + Identification
  + Title
  + Category
  + Probability
  + Severity
  + Dependency
  + Status
  + History

+ Is defined by: A description
+ Is linked to: A feature, a release


## Running Meerkat
Meerkat is developed in Python and HTML using the Django Web development framework (www.django.com).

To run Meerkat:
+ Create a folder with the following files:
    + apps
    + __init__.py
    + __init__.pyc
    + settings.py
    + settings.pyc
    + templates
    + urls.py
    + urls/pyc
    + wsgi.py
    + wsgi.pyc

## Licensing Meerkat
This project is licensed under the terms of the MIT license.
