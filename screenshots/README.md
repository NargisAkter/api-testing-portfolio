## Screenshots

### Postman Collection 
This Postman collection demonstrates the complete parking availability workflow integration. The requests validate the end-to-end process of retrieving authentication tokens from the IPParking vendor system, using those tokens to fetch real-time parking occupancy data, and validating the backend responses utilized by the  application to display available parking spots to users.

### Parking API Validation
This API response demonstrates the real-time parking data retrieved from the IPParking vendor system. The validation ensures that the application receives accurate parking capacity and occupancy information from the external vendor integration before processing and displaying available parking spots to end users.

### GraphQL API Response

This GraphQL response is used by the KPI-service microservice, which is triggered when a user clicks the Parking menu in the application. The service retrieves real-time parking capacity and occupancy data from the integrated parking system and calculates the available parking spots by subtracting occupied spaces from the total parking capacity before displaying the availability information to the user interface.

### SIT Workflow

This SIT workflow demonstrates the end-to-end integration process where the application retrieves accurate parking availability information from the GraphQL API response and displays the real-time available parking spots to users through the frontend UI.
