# Analyze_Images_with_Azure_AI_vision

## Project Description

This project utilizes Microsoft Azure's Computer Vision API to analyze images. The application performs tasks such as language detection, object detection, and background removal. It leverages the Azure AI Vision client to extract valuable insights from images, including captions, tags, and detected objects.

## Features

- Analyze images to extract captions, tags, and detected objects.
- Draw bounding boxes around detected objects and people.
- Remove backgrounds from images using Azure's segmentation capabilities.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine.
- An Azure account with access to the Computer Vision API.
- Required Python packages installed (see Installation section).

## Example Output

Original Image

![street](https://github.com/user-attachments/assets/10b6479b-ed83-4d3b-b6e2-ac75bc828d7b)

Detected Image

![street detected](https://github.com/user-attachments/assets/61d87df4-c767-44e9-8fec-df60dec85c98)

Street Background Removing

![street background remove](https://github.com/user-attachments/assets/685b3fab-beb7-4816-8711-94f88bf4b805)

Foreground Matting

![forge matting](https://github.com/user-attachments/assets/24a293b9-c406-4655-b01b-39a2b986183b)

## Setup

## Create a .env

Set up your environment variables. Create a .env file in the root directory of the project and add your Azure credentials:

AI_SERVICE_ENDPOINT= <your_azure_endpoint>

AI_SERVICE_KEY= <your_azure_key>

## Acknowledgments

- Microsoft Azure for providing the Computer Vision API.
- Pillow for image processing.
- Matplotlib for visualizing the results.
