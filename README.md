# Secure-File-Transfer  
secure file storage in the cloud using Aes Encryption :

  In the cloud environment, resources are shared among all the servers, users and individuals. So, it is difficult for the cloud provider to ensure file security. As a result, it is very easy for an third party to access, misuse and destroy the original form of data. To secure the file, we use the  model which uses the concept of encryption scheme to meet security needs.The AES Algorithm is used to encrypt the file and decrypt the file.
  
  Execution:
  
    1. Registration : Intitially user needs to register by fiiling the details and the filekey is send to their respective mails.
    2. Login : login using " userid " and " password ".
    3. After login user have two options  a. file upload
                                         b. file download
    File upload : First we need to choose a file and when we click on submit AES Aalgorithm applies at Background and file get Encrypted                     and saved into aws s3 bucket. S3 Bucket in aws is automatically created with the username.
                
                  The file stored in the bucket is in Encrypted form.
                  
    File download: During the file download user had an option called "get objects".
    
                    Getobjects includes the a. Bucket name
                                            b. File name
                                            c. file key
                     Then click on download , the file downloaded into our local disk. 
                       
