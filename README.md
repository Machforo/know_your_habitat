# know_your_habitat
This is a project in which we have designed a deep learning model which is trained on the dataset of the images of  various buildings present in our campus. Further we have built a software that basically takes the image of the building present in the campus and classifies this is which all buildings are present in the image. 

The software will come in very handy for the individuals who are new to the campus and confused between various buildings present in the campus like academc block , hostel area , medical centre etc.

The model is trained such that it could classify the building from the image clicked from any angle.

The repository contains two ipynb files, one file is present to classify that the image is from which campus(IIT Mandi has three campuses North ,south and Mandi). 
This will reduce the computation for the system.
Depending on the output of the previous file our second file gives the prediction of which all images are present in the image(object detection model).

Further we have saved our model in pickle format and then used flask for developing the web application for our product.

We accept images from our web application , do the prediction through our ML model and then give the output through the website.

We have also made a YouTube video for explaining the whole project.
Following is the link to the same: https://www.youtube.com/watch?v=hMEhd8FlJ5U&list=LL&index=16&t=10s
