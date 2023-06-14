# Attendance management application
This is an application for managing an attendance list. It allows users to mark their attendance by submitting their name, surname, and GitHub nickname. The application utilizes two APIs that are based on the same database.

## Instructions
1. Clone the repository and navigate to the project folder.
2. Launch the application by opening the index.html file in any web browser.
3. Fill out the form provided on the webpage. The form consists of three fields: name, surname, and GitHub nickname. The fields must adhere to the following validation criteria:
    - The name and surname should only contain letters.
    - Each field must contain at least 3 characters but no more than 50 characters.
4. After filling out the form, click the "Submit" button or press Enter to send the data to the API.
5. Upon successfully submitting the data to the API, the attendance status in the database will be updated, and your name and nickname will be displayed on the list of current attendees.
6. The current attendance list is fetched from an external API and displayed on the webpage. The list is automatically refreshed when a new participant is added.

## Dependencies
The application does not require any additional dependencies as it is based on pure JavaScript.

## Project Structure
The project includes the following main file:
- index.html - HTML file containing the application structure.
Additionally, the main folder may contain additional files such as a CSS file for application styling.

## Additional Information
- The project utilizes the fetch method for communicating with the API.
- Field validation in the form is performed using dedicated JavaScript functions that verify the correctness of the entered data.
- Upon sending data to the API, the HTTP response status is analyzed, and an appropriate message is displayed on the webpage.

## Desktop overview layout
![attendance-management-application_1](https://github.com/anna-bachorska/attendance-management-application/assets/125367541/ccda6f6a-7c19-4c5c-9fec-f70354366f1e)
![attendance-management-application_2](https://github.com/anna-bachorska/attendance-management-application/assets/125367541/fd45db19-a1bc-42fe-ab0e-b84dacb76236)
![attendance-management-application_3](https://github.com/anna-bachorska/attendance-management-application/assets/125367541/7b670022-e57c-4247-8986-560a6694b3a9)
