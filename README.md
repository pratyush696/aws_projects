# aws_projects
Project Overview: I developed a text-to-speech converter using AWS Lambda and Polly. The goal was to create a service where users could submit text, and the system would return an audio file in response.
Setting Up AWS Lambda:
•	Created a Lambda function in the AWS Management Console using Python.
•	Configured the function to call Amazon Polly's synthesizeSpeech API to convert text into speech.
•	Used base64 encoding to return the audio stream as a response.
API Gateway Setup:
•	Set up an API Gateway to trigger the Lambda function via a POST request.
•	Configured the endpoint to accept text in the request body and return the audio file in base64 format.
•	Ensured that CORS and authorization were correctly configured to allow access to the API.
Testing & Debugging:
•	Initially tested the Lambda function using the built-in test feature in the AWS Lambda console.
•	Used Postman(it’s a tool for API testing) for end-to-end testing, ensuring the system worked as expected.
Deployment:
•	Deployed the API on a stage in API Gateway and ensured the Lambda function was linked correctly to the API.
•	Published the API and tested it with real input to verify functionality.

We can now convert the base64 format in mp3 using online tool or code. 



