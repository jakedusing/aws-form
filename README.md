# Contact Form with AWS API and Lambda
This project demonstrates how to build a contact form that uses AWS API and Lambda to process form submissions. When a user submits the form, the data is sent to AWS Lambda, which sends a notification email to the admin and an
auto-reply email to the user.  The project uses Amazon SES (Simple Email Service) for email functionality.

## Features
- **Contact Form**: Users can submit their name, email, and message through a form.
- **AWS API Gateway**: Serves as the endpoint for the form submission.
- **AWS Lambda**: Handles the form data, sends email notifications using Amazon SES.
- **Amazon SES**: Used to send emails to both the admin and the user.
