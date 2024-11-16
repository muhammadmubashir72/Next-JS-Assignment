# Assignment: Building a Next.js Application with Dynamic Routes

## Task: Assignments

### Assignment 1: Building a Next.js Application with Dynamic Routes

#### Requirements:

1. **Create a Dynamic Routing System:**
   - Set up dynamic routes for country names using the app router in Next.js.
   - Each route will dynamically display details for a specific country based on the URL.

2. **Create a Country Listing Page:**
   - Build a static page that lists five countries of your choice.
   - Each country name should be clickable, linking to its respective dynamic route (e.g., `/country/[country_name]`).

3. **Display Country Details:**
   - On the dynamic route page, display the following details for the selected country:
     - Name
     - Population
     - Capital

#### Implementation Details:

- Use a JavaScript object to store the details of the countries you want to display.
  - Each object should include:
    - `name`
    - `population`
    - `capital`
- When a user visits the dynamic route for a specific country (e.g., `/country/canada`), the application should:
  1. Search for that country in the object.
  2. If the country is found, display its details.
  3. If the country is not found, display a message: 
     - **"Country not found."**

#### Example:

For the dynamic route `/country/canada`, if "Canada" is in the object, it will display:
- Country Name: Canada
- Population: 3,800,000
- Capital: Ottawa

If the country does not exist in the object, it will display:
- **"Country not found."**
