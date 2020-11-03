---
display_name: AWS Rekognition
icon: "https://assets.koyeb.com/icons/aws.svg"
short_description: The AWS Rekognition function allows you to analyze your images within a few minutes.
status: ACTIVE
---

## Summary

AWS Rekognition is an image detection service that employs deep learning technology to analyze image content.
The AWS Rekognition function allows you to identify objects, people, texts, activities, and inappropriate content in images.

This function comes with the following variants:

- **Image text detection**, to identify text in an image as long as the text is within a 90 degrees orientation of the horizontal axis.
- **Image label detection**, to detect objects, scenes, and activities in an image.
- **Image face detection**, to identify the 100 largest faces in an image. For each face detected, the integration returns details about the face including: the gender of the face, the coordinates of facial landmarks such as eyes and mouth, and more.
- **Image explicit content detection**, to detect unsafe content in an image. This feature allows you to filter images that contain nudity, but not images containing suggestive content.
- **Image celebrities detection**, to detect the 100 largest faces in an image. For each face detected, the integration returns face details, including the name of the celebrity detected, URLs pointing to information about the celebrity, and more.

## Advantages of using Koyeb's AWS Rekognition Function

With Koyeb, you can run the AWS Rekognition integration to add image analysis to your applications in seconds:

- Store the result on the cloud service provider of your choice
- Ready to use, no code or complex configuration required to get started
- Combine additional processing actions that immediately use the results of the AWS Rekognition function

## Popular Use Cases with the AWS Rekognition Function

- Creating image libraries that are easier to search
- Conducting sentiment and demographic analysis
- Detecting explicit content in images
- Enriching your application database
- Identifying text and numbers automatically in images

## How the AWS Rekognition Function Works with Koyeb

To get started with the AWS Rekognition function, you have to copy the configuration snippet below and replace the required values with yours.
This function is triggered each time an object is created in the Store you use.

Below is what you need to use this function:

* A Koyeb valid account
* Valid AWS credentials with permissions to access AWS Rekognition service
* A Store to upload images and save the function result
