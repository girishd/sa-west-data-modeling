# Overview Test

# Entities

- User
- Payment
- Order
- Order Details
- Customer
- Rating
- Menu
- Menu Type

# Attributes

## User

- ID – primary key represented with underline
- Full name
- Contact
- Email address
- Username
- password

## Payment

- ID – primary key represented with underline
- Order ID – foreign key
- Amount
- Paid By
- Date
- Processed By – foreign key

## Order

- ID – primary key represented with underline
- Customer ID – foreign key
- Order Date
- Total Amount
- Order Status
- Processed By – foreign key

## Order Details

- ID – primary key represented with underline
- Order ID – foreign key
- Menu ID – foreign key
- Amount
- No of Serving
- Total Amount

## Customer

- ID – primary key represented with underline
- First name
- Last name
- Middle name
- Email
- Phone Number
- Landline
- Profile Image
- Username
- Password
- Account Status

## Rating

- ID – primary key represented with underline
- Menu ID – foreign key
- Score
- Remarks
- Date Recorded
- Customer ID – foreign key

## Menu

- ID – primary key represented with underline
- Name
- Price
- Type ID – foreign key
- Image
- Ingredients
- Status

## Restaurants

- ID
- Name
- Location
- 

# Common Queries
