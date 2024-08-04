# Chatbot
Welcome to the Chatbot Project repository! This project is a versatile and interactive chatbot designed to provide various functionalities, including answering questions, providing recommendations, and more. The chatbot is built using Python, Anaconda, and Google Gemini.

# Table of Contents
Introduction

Features

Installation

Usage

# Introduction
This chatbot project aims to create an intelligent assistant capable of understanding and responding to user queries. The chatbot sets up a virtual environment to run on a local host using Anaconda, ensuring an isolated and consistent development environment. It sends queries to Google Gemini and retrieves the answers, providing a seamless and efficient interaction experience.

# Features
Simple User Interface
Utilizes Features of Google Gemini for Accurate and Fast Responses

# Installation
To get started with the chatbot, follow these steps:

1.Install Anaconda and Python IDLE:
Download and install Anaconda from the official website.
Install Python IDLE if you prefer to use it alongside Anaconda.

2.Create a project folder and open it in your compiler (e.g., VS Code):
Create a new folder for your project.
Open this folder in your preferred code editor (e.g., VS Code).

3.Create and activate an Anaconda environment:
In your compiler's terminal, run the following commands:
conda create -p venv python==3.10 -y
conda activate venv/

4.Install the required libraries:
In the terminal, run the following commands:
pip install streamlit 
pip install google-generativeai 
pip install python-dotenv

5.Set up environment variables:
Create a .env file in the root directory.
Add your Google API key in the .env file like this:
GOOGLE_API_KEY = "Your API Key"
You can get a free API key for Google Gemini Pro.

6.Run the chatbot:
In the terminal, run the following command:
streamlit run app.py

# Usage
Once the chatbot is up and running, it will open in your default browser, and you can interact with it. You can also customize its interface according to your needs.
