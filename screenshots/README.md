## Screenshots

### Postman Collection
![Postman Collection](screenshots/postman-collection.png)

This Postman collection demonstrates the complete parking availability workflow integration. The requests validate the end-to-end process of retrieving authentication tokens from the IPParking vendor system, using those tokens to fetch real-time parking occupancy data, and validating the backend responses utilized by the  application to display available parking spots to users.

### Parking API Validation
![Parking API](screenshots/parking-api-validation.png)

This API response demonstrates the real-time parking data retrieved from the IPParking vendor system. The validation ensures that the application is successfully receiving accurate parking capacity and occupancy information from the external vendor integration before processing and displaying available parking spots to end users.

### GraphQL API Response
![GraphQL Response](screenshots/graphql-response.png)

This GraphQL response is utilized by the KPI-service microservice, which is triggered when a user clicks on the Parking menu within the application. The service retrieves real-time parking capacity and occupancy data from the integrated parking system and calculates the available parking spots by subtracting occupied spaces from the total parking capacity before displaying the availability information to the user interface.

### SIT Workflow
![SIT Workflow](screenshots/sit-workflow.png)

This SIT workflow demonstrates the end-to-end integration process where the application retrieves accurate parking availability information from the GraphQL API response and displays the real-time available parking spots to users through the frontend UI.
