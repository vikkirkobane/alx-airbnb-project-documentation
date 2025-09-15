# Task 4: Design a Flowchart for System Processes

## Objective
The objective of this task is to create a flowchart that maps the workflow and processes of a key backend feature in the Airbnb Clone project. This will help visualize the steps involved in a specific process, such as user registration or property booking.

## Instructions

1. **Choose a Key Backend Process**:
      - For this example, we will choose **User Registration** as the backend process to visualize in the flowchart.

2. **Define the Steps in the User Registration Process**:
      - Here are the typical steps involved in the user registration process:
        - Start
        - User enters registration details (name, email, password)
        - Validate the input data
        - If valid, proceed to create user account
        - If invalid, show error message
        - Send verification email to the user
        - User verifies email
        - Account activation
        - End

3. **Create Flowchart Using Draw.io**:
      - Open Draw.io (Diagrams.net).
      - Create a new flowchart that includes:
        - **Start/End**: Represented as ovals.
        - **Processes**: Represented as rectangles (e.g., "Enter Registration Details", "Validate Input Data").
        - **Decision Points**: Represented as diamonds (e.g., "Is Input Valid?").
        - **Arrows**: Indicating the flow of the process.

4. **Export Your Flowchart**:
      - Once the flowchart is complete, export it as a PNG file.
      - Name the file `user_registration_flowchart.png`.

5. **Store the PNG File**:
      - Create a directory called `flowcharts/` within your GitHub repository `alx-airbnb-project-documentation`.
      - Upload the `user_registration_flowchart.png` file into this directory.

6. **Commit and Push Changes**:
      - Commit your changes with a relevant message, such as "Added user registration flowchart".
      - Push the changes to your GitHub repository.

## Example Git Commands
bash
# Navigate to your project directory
cd path/to/alx-airbnb-project-documentation

# Create the new directory
mkdir flowcharts

# Move the PNG file into the new directory
mv path/to/user_registration_flowchart.png flowcharts/

# Stage the changes
git add flowcharts/user_registration_flowchart.png

# Commit the changes
git commit -m "Added user registration flowchart"

# Push the changes to the repository
git push origin main
