# Task 1: Design the Use Case Diagram of the Features and Functionalities

## Objective
The objective of this task is to visualize system interactions using a use case diagram, capturing the interactions between users and the system for key functionalities such as user registration, property booking, and payments.

## Instructions

1. **Identify Key Actors**:
      - Determine the primary actors that will interact with the system:
        - **Guest**: A user who can register, search for properties, make bookings, and leave reviews.
        - **Host**: A user who can manage property listings, view bookings, and respond to reviews.
        - **Admin**: A user who can monitor users, manage listings, and oversee bookings and payments.

2. **Define Use Cases**:
      - Outline the main use cases for each actor:
        - **Guest**:
        - User Registration
        - User Login
        - Search Properties
        - Make Booking
        - Cancel Booking
        - Leave Review
        - **Host**:
        - Create Listing
        - Edit Listing
        - Delete Listing
        - View Bookings
        - Respond to Review
        - **Admin**:
        - Monitor Users
        - Manage Listings
        - Track Bookings
        - Oversee Payments

3. **Create Diagram Using Draw.io**:
      - Open Draw.io (Diagrams.net).
      - Create a new use case diagram that includes:
        - Actors represented as stick figures.
        - Use cases represented as ovals.
        - Lines connecting actors to their corresponding use cases to signify interactions.

4. **Export Your Diagram**:
      - Once the diagram is complete, export it as a PNG file.
      - Name the file something descriptive, such as `airbnb_clone_use_case_diagram.png`.

5. **Store the PNG File**:
      - Create a directory called `use-case-diagram/` within your GitHub repository `alx-airbnb-project-documentation`.
      - Upload the PNG file into this directory.

6. **Commit and Push Changes**:
      - Commit your changes with a relevant message, such as "Added use case diagram for Airbnb Clone".
      - Push the changes to your GitHub repository.

## Example Git Commands
bash
# Navigate to your project directory
cd path/to/alx-airbnb-project-documentation

# Create the new directory
mkdir use-case-diagram

# Move the PNG file into the new directory
mv path/to/airbnb_clone_use_case_diagram.png use-case-diagram/

# Stage the changes
git add use-case-diagram/airbnb_clone_use_case_diagram.png

# Commit the changes
git commit -m "Added use case diagram for Airbnb Clone"

# Push the changes to the repository
git push origin main
