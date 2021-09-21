## Infrastructure

User deals with the frontend which is held on a S3 bucket and whenever the user retrive or post an image, the API then will make a call to the database RDS postgresql and make another call for S3 bucket that has the image.

![System infrastructure](https://user-images.githubusercontent.com/53359513/134192348-26d60a18-1f0f-4988-84be-1ddeafa2f28f.png)
