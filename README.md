# Next.js Frontend Developer Assessment

This test is designed to evaluate your skills in building a functional, user-friendly application using Next.js, along with integration with public APIs and basic routing.

Please read through the instructions carefully, and ensure all requirements are met before submission.

## Task Overview
You will be building a simple application with the following features:

### Dashboard: 
A main dashboard page to display an overview or list of items fetched from a public API.

#### Login Page: 
A login page with basic form elements for a username and password (functionality doesn't need to be implemented).
Redirect users to the dashboard upon login.

#### Detailed View: 
Fetch details of a single item from the public API and display it on a separate page.

## Requirements

1. Project Setup

Use Next.js to create the application.
Structure your code with components and pages to ensure modularity.
Use any public API of your choice (e.g. [REST Countries](https://restcountries.com/v3.1/all) for the data fetching tasks.

2. Tasks

#### Login Page

Create a Login page (/login) with the following fields:
- Username: Text input
- Password: Password input
- Submit button: Console log the entered values on submit (no backend functionality is required).
- Basic validation for required fields is appreciated.

#### Dashboard Page

- Create a Dashboard page (/dashboard) where the main list of items will be displayed.
- Use the public API to fetch a list of items (e.g., posts, countries, users).
- Display essential information from each item (e.g., title, name, or summary).
- Include pagination or infinite scroll if the data set is large (optional).

#### Detailed View

- When an item on the dashboard is clicked, navigate to a detailed view page for that specific item.
- Create a dynamic route for this page (e.g., /dashboard/[id]).
- Fetch the item's details using the ID in the URL and display comprehensive information about that item.


3. Additional Instructions

- You can use CSS, Sass, or a CSS-in-JS solution like styled-components. 
- Feel free to use UI libraries like Tailwind CSS or Material UI if preferred.
- Data Fetching: Use Next.js’s built-in data fetching methods (getStaticProps, getServerSideProps, or getInitialProps) as appropriate.

#### Routing: 

- Use Next.js’s routing for page navigation.

## Evaluation Criteria

Your submission will be evaluated based on:

- Code readability and organization.
- Proper use of Next.js features (data fetching, routing, etc.).
- Clean and responsive UI/UX design.
- Handling of API responses and error handling.
- Attention to detail when implementing the requirements.

## Submission

- Ensure all code is committed to your repository.
- Submit a link to your repository and any additional notes or documentation if necessary.
