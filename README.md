# Ai-text-validator and Health Information Checker

## Overview
This application allows users to check the trustworthiness of health-related information by entering text and receiving an analysis based on an external API response.

## Functionality
- **Input Section**: Users can input text related to health information.
- **Analyze Button**: Clicking the "Analyze" button triggers an analysis of the provided text.
- **Response Display**:
  - If the health information is trustworthy, a green response is displayed with related details from the API.
  - If the information is doubtful, a yellow response is shown with alternative references from the API.
  - For fake information, a red response is displayed with links to the referenced content from the API.
  - If no text is entered, a generic response displays the opinion of the LARGE LANGUAGE MODEL.
- **Result Section**: Different colored buttons indicate the analysis result in case we havn't entred anything yet.

## Setup

### **1. Clone the Repository**

Clone this repository to your local machine and navigate into the project directory:

1. git clone https://github.com/HeReFanMi/Frontend.git
2. cd /project


### **2. Build and Run the Docker Container**

1. docker build -t frontend .
2. docker run -p 3000:3000 frontend

### **3. Access the Application**

Once the container is running, access the web application:
Local Access in the browser: http://127.0.0.1:3000

### **4. Docker hub image**

You can find the image of this backend in the docker hub following the link of the repository below :

  https://hub.docker.com/repository/docker/abdelaliichou/frontend

## Usage
1. Enter health-related information in the input field.
2. Click the "Check reliability" button to trigger the analysis.
3. Observe the displayed response and buttons indicating the trustworthiness of the information.

Feel free to check the other files and the structure of components for better understading.
