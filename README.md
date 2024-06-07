# Diet Tracking Mini Project

## Objective
Build a basic diet tracking system similar to MyFitnessPal where users can log their daily food intake and monitor their diet.

## Features to Implement
1. **User Registration and Login:**
   - Create user accounts with registration and authentication.
2. **Food Diary Entry:**
   - Allow users to log food items they consume throughout the day.
3. **Calorie and Macronutrient Tracking:**
   - Track calories, proteins, fats, and carbohydrates.
4. **Reports:**
   - Generate daily, weekly, and monthly reports of food intake.

## Description
This project aims to build a diet-tracking system similar to MyFitnessPal. The primary objective is to allow users to log their daily food intake, track calories and macronutrients, and view reports of their diet over time.

**Aspects to Consider:**

- **Schema Design:**
  - Think about how you will structure your database tables to store user information, food entries, and daily reports.
  - Consider how to efficiently link food entries to users and aggregate data for daily, weekly, and monthly reports.

- **React App Design:**
  - Plan the component structure for handling user registration, login, food diary entry, and report viewing.
  - Ensure state management is handled effectively, perhaps using a state management library like Redux.

- **Best Practices:**
  - Implement authentication and authorisation securely.
  - Ensure input validation and error handling.
  - Consider how to make the app responsive and user-friendly.
  - Plan for scalability if you intend to add more features later.

## Technical Requirements
- **Backend:** Node.js with Express
- **Database:** Supabase
- **Frontend:** React
- **Authentication:** Supabase Auth

## Steps to Build
1. **Set up the project:**
   - Initialise a new Node.js project.
   - Set up Supabase and connect it to the project.
2. **Authentication:**
   - Implement user registration and login with Supabase Auth.
3. **Food Diary API:**
   - Create endpoints to add, update, delete, and fetch food diary entries.
4. **Frontend:**
   - Build React components for registration, login, and food diary entry.
   - Display daily, weekly, and monthly reports.

## Future Enhancements
- Integrate external API for food data.
- Add barcode scanning for food items.
