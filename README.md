# OpenCV-Rekognition

This is an example project for using OpenCV together with AWS Rekognition


OpenCV tracks faces and monitors for smiles, when a smile is detected a picture is saved to the hard-drive, sent to AWS S3, Rekognition is invoked to analyze that picture, and the results are sent back to console.  

In order to run the project you need to create a S3 bucket, follow instructions here: 

http://docs.aws.amazon.com/AmazonS3/latest/gsg/SigningUpforS3.html

The bucket needs open write premissions 


You need OpenCV installed with python bindings : http://docs.opencv.org/2.4/doc/tutorials/introduction/linux_install/linux_install.html

You also need to install boto3: pip install boto3 
for more info on boto see: https://github.com/boto/boto3

Have Fun!
