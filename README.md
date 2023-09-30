# Email Notification-Microservice

## Introduction 
Email Notification Microservice: The Notification microservice is used to send emails to users 

## Service Provider used
Mailtrap


### Endpoints
Send mail Endpoints : http://localhost:8082/api/v1/mail     [Post]

## payload:
Request Payload : 
{

    "subject" : "Subject of the mail" //Required

    "recipient" : "recipient name" //Required

    "body" : "Body of the message" // Required

    "sender" : "sender name" // Required

    "attachment" : "attachments" 
    
    "cc" : "cc"
    
    "bcc" : "bcc" ;

}
