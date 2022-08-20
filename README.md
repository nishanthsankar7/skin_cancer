# SkinCancerApi

This is in backend for the skin cancer is application which is developed using the flask library in python.
## Technologies
- Python
- fastai
- numpy
- pandas

## Usage
Urls
www.<yourapiurl>/register for registerin new user-POST Method Form with 5 parameters
{
username
password
request
premium
emailId
}

www.<yourapiurl>/auth -authenticate the user eg.login POST Method  with 2 parameters
{
username
password
}

www.<yourapiurl>/model -predict the image  POST Method  with 2 parameters
{
username 
image:"the photo"
}
