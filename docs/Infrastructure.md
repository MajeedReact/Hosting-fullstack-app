## Infrastructure

User deals with the frontend which is held on a S3 bucket and whenever the user retrive or post an image, the API then will make a call to the database RDS postgresql and make another call for S3 bucket that has the image.
