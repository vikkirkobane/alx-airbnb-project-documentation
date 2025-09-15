# Task 3: Design a Data Flow Diagram for Your Features and Functionalities

## Objective
The objective of this task is to create a Data Flow Diagram (DFD) that illustrates how data moves through the Airbnb Clone system, highlighting key entities such as users, properties, bookings, and payments.

## Instructions

1. **Identify Key Entities**:
      - Determine the core entities involved in the data flow:
        - **User**: Represents both guests and hosts.
        - **Properties**: Represents the listings available for booking.
        - **Bookings**: Represents the reservations made by users.
        - **Payments**: Represents the financial transactions involved in bookings.

2. **Define Data Inputs, Processes, and Outputs**:
      - Outline how data flows between these entities:
        - **User Registration**: Input user data (name, email, password) to create a new user account.
        - **Property Management**: Input property details to create, update, or delete listings.
        - **Booking Creation**: Input booking requests (user ID, property ID, dates) to create a new booking.
        - **Payment Processing**: Input payment details to process a transaction for a booking.
        - **Review Submission**: Input user reviews and ratings for properties.

3. **Create Diagram Using Draw.io**:
      - Open Draw.io (Diagrams.net).
      - Create a new Data Flow Diagram that includes:
        - **Entities**: Represented as rectangles (Users, Properties, Bookings, Payments).
        - **Processes**: Represented as circles or ovals (e.g., Register User, Manage Properties, Make Booking, Process Payment).
        - **Data Flows**: Arrows indicating the direction of data movement between entities and processes.

4. **Export Your Diagram**:
      - Once the diagram is complete, export it as a PNG file.
      - Name the file `data-flow.png`.

5. **Store the PNG File**:
      - Create a directory called `data-flow-diagram/` within your GitHub repository `alx-airbnb-project-documentation`.
      - Upload the `data-flow.png` file into this directory.

6. **Commit and Push Changes**:
      - Commit your changes with a relevant message, such as "Added data flow diagram for Airbnb Clone".
      - Push the changes to your GitHub repository.

## Example Git Commands
bash
# Navigate to your project directory
cd path/to/alx-airbnb-project-documentation

# Create the new directory
mkdir data-flow-diagram

# Move the PNG file into the new directory
mv path/to/data-flow.png data-flow-diagram/

# Stage the changes
git add data-flow-diagram/data-flow.png

# Commit the changes
git commit -m "Added data flow diagram for Airbnb Clone"

# Push the changes to the repository
git push origin main
