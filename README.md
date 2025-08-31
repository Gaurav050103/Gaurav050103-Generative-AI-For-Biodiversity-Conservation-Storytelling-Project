Generative AI for Biodiversity Conservation Storytelling
Project Description
This project is a web-based application built with Streamlit that leverages the power of generative AI to create compelling and educational stories about biodiversity conservation. It is designed to be a tool for environmental educators, conservationists, and students to generate content that raises awareness about endangered species and critical ecosystems.

The application allows users to input a topic (e.g., a specific species or a conservation area) and choose a storytelling style and length. It then uses the Gemini API with Google Search grounding to generate a factually-informed and engaging narrative. The use of a modular codebase and external API integration makes this a robust and modern application, suitable for a final-year project.

Features
Interactive UI: A user-friendly interface built with Streamlit.

AI-Powered Story Generation: Creates unique, coherent, and contextually relevant stories using the Gemini API.

Factually Grounded: Utilizes Google Search grounding to ensure stories are based on real-world information.

Customizable Output: Users can control the tone, style, and length of the generated story.

Modular Codebase: The core AI logic is separated from the frontend UI for clean and maintainable code.

Technologies Used
Frontend Framework: Streamlit

AI Model: Gemini (gemini-2.5-flash-preview-05-20)

Programming Language: Python

API Integration: Google Generative AI Python SDK

Prerequisites
Python 3.8 or higher installed on your system.

A Google AI Studio API key. You can obtain one by visiting https://aistudio.google.com/app/apikey.

Project Setup
Create a Project Folder:

mkdir biodiversity_ai_project
cd biodiversity_ai_project

Create the Files:
Create the following four files in the biodiversity_ai_project folder and copy the provided code into each one:

app.py

story_generator.py

requirements.txt

README.md (this file)

Install Dependencies:
Open your terminal or command prompt, navigate to the biodiversity_ai_project directory, and run the following command to install all required libraries:

pip install -r requirements.txt

Add Your API Key:
Open the app.py file and replace the placeholder YOUR_API_KEY with your actual Google AI Studio API key.

How to Run the Application
From your terminal, navigate to the project directory.

Run the Streamlit application with the following command:

streamlit run app.py

The application will automatically open in your default web browser. If it doesn't, you can copy and paste the provided local URL into your browser's address bar.

Project Structure
app.py: The main file that runs the Streamlit application. It handles the user interface and calls the story generation logic.

story_generator.py: A module containing the core function to interact with the Gemini API for story generation. This separation of concerns is a key part of good software design.

requirements.txt: Lists all the necessary Python libraries for the project, making it easy to set up the development environment.
