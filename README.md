# GEN-AI-FOOD-CALORIES-TRACKER

This is a web-based application that uses Google’s Generative AI to analyze images of food, estimate serving sizes, and provide calorie and nutritional information. The app allows users to upload an image of food, and the AI model responds with nutritional details. If the AI cannot identify the image as food, it will respond with a message indicating that.

### Technologies Used
This project leverages the following technologies:
HTML: Provides the structure for the webpage.

CSS: Styles the UI for better user experience.

JavaScript:

ES6 Modules: Uses JavaScript’s module system for loading dependencies.

Event Handling: JavaScript is used to handle file uploads and display results.

File Handling: Converts uploaded images into base64 format for compatibility with the AI model.

Google Generative AI API:

Import Map: Loads @google/generative-ai library for image analysis.

API Integration: Uses gemini-pro-vision model to analyze food images and provide nutritional details.

### Features
Upload Food Image: Users can upload a food image in various formats.

Nutritional Analysis: Google’s AI estimates calories, serving size, and provides additional nutritional info.

User Feedback: If the image is not identified as food, the AI responds with a custom message.

### Setup

#### Prerequisites
API Key: To use this application, you’ll need a Google Generative AI API key. Visit the Google Cloud Console to obtain an API key.

Web Server: Since the application involves modules and import maps, it may require a simple local web server (such as Live Server in VS Code) to run properly in the browser.

### Installation
#### 1.Clone the repository:

git clone https://github.com/your-username/food-calories-tracker.git

#### 2.Navigate into the project directory:
cd food-calories-tracker

#### 3.Open index.html in a text editor, and replace YOUR_API_KEY with your actual API key in the code:

const API_KEY = "YOUR_API_KEY";

#### 4.Start a local server and open index.html in your browser.

### Usage
Upload Image: Click on the file input to select a food image.

Submit: Click the "Submit" button to analyze the image.

View Results: The output area will display the estimated calories, serving size, and additional nutritional information based on the image provided.

