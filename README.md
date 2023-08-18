# JsonDB
# Student Enrollment Form using JsonPowerDB

## Description
This project is a web-based Student Enrollment Form that utilizes JsonPowerDB for data storage. It allows users to input student details such as Roll No, Full Name, Class, Birth Date, Address, and Enrollment Date. The form follows a specific workflow for data entry, validation, saving, updating, and resetting.

## Benefits of using JsonPowerDB
JsonPowerDB is a high-performance, real-time, and developer-friendly data store. It offers several benefits for this project:
- **High Performance**: JsonPowerDB provides faster read and write operations, making it suitable for real-time applications like this enrollment form.
- **Schema-less**: Its schema-less nature allows easy storage and retrieval of structured and unstructured data.
- **Dynamic Indexing**: JsonPowerDB automatically indexes data, ensuring quick query response times.
- **Real-time Updates**: The real-time nature of JsonPowerDB ensures that changes are instantly reflected without needing to refresh the page.
- **API-driven**: JsonPowerDB offers a simple API interface that can be easily integrated with frontend technologies.

## Release History
- Version 1.0 (Initial Release)
    - Basic implementation of the Student Enrollment Form with AJAX and JsonPowerDB integration.
    - Form captures student details and performs data validation.
    - Allows saving and updating student records based on Roll No.
    - Supports resetting the form to its initial state.

## Project Instructions
1. **Roll No as Primary Key**: The form uses the Roll No as the primary key to uniquely identify student records in the database.
2. **Form Workflow**: The form follows a specific workflow for data entry, validation, saving, updating, and resetting as outlined in the project description.
3. **Control Buttons**: Three control buttons ([Save], [Update], [Reset]) are provided at the bottom of the form.
4. **AJAX Integration**: The form utilizes AJAX to communicate with the backend for data storage and retrieval.
5. **JsonPowerDB Setup**: Before running the project, ensure you have JsonPowerDB set up and running. Update the API URLs and endpoints as required.

## Getting Started
1. Clone this repository to your local machine.
2. Open the HTML file in a web browser.
3. Fill out the student details and follow the workflow as described in the project instructions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [JsonPowerDB](http://login2explore.com/jpdb/)
- [jQuery](https://jquery.com/)

---

*Note: This README is a template. Modify it according to your project's specific details.*
