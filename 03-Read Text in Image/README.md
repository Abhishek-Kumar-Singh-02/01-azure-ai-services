# Read Text in Image

## Project Description

This project utilizes Microsoft Azure's Computer Vision API to read test in an images. The application performs tasks such as image text analyser and handwritting analyser . It leverages the Azure AI Vision client to extract valuable insights from images, including captions, tags, and detected objects.


## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine.
- An Azure account with access to the Computer Vision API.
- Required Python packages installed (see Installation section).

## Example Output

Original Image

![normal handwriting](https://github.com/user-attachments/assets/ac2352ff-bdfc-4c9d-8555-8e82911093a7)


Detected Image

![image text read](https://github.com/user-attachments/assets/ca542f01-5b28-42a2-841f-00829f167437)

Detected Handwriting Image

![handwritting read](https://github.com/user-attachments/assets/85b3eb2d-679e-4bfe-a19a-a3239acb3e7d)



## Setup

## Create a .env

Set up your environment variables. Create a  `.env` file in the root directory of the project and add your Azure credentials:

AI_SERVICE_ENDPOINT= `<your_azure_endpoint>`

AI_SERVICE_KEY= `<your_azure_key>`

## Acknowledgments

- Microsoft Azure for providing the Computer Vision API.
- Pillow for image processing.
- Matplotlib for visualizing the results.
