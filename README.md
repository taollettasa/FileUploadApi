# FileUploadApi
------------------------------------------------------------------------------------------------------------------------
## Challenges

As the technology I use at present is proprietary, I had to refresh my knowledge surrounding certain technologies.
In respect to the technologies used by NCTech and my experience at my previous role, I chose to undertake this with a
Spring boot framework. I also attempted to include a Swagger implementation, but due to time constraints and other
commitments I was unable to complete this.

## Enhancements

### 1. Authentication

Spring boot security to ensure that the application isn't executable to those without a predetermined username/password
combination.

### 2. Uploaded files and progress/Resumable uploads

Ensure that multipart upload is implemented as part of the solution, allowing you to use this to monitor what chunks
have been uploaded and stop/start the API at certain times.
