 # Automatic Webpage Creation with Langchain using Gemini API

A dynamic AI-powered web application that automatically generates complete production-ready frontend websites (HTML, CSS, JS) based on user input.

Built using **Streamlit + LangChain + Google Gemini (Generative AI).**


**Project Overview**

This project allows users to:
  Describe the type of webpage they want to create
  
  Provide content for the webpage
  
  Automatically generate:

    index.html
    style.css
    script.js

Download the complete website as a ZIP file

The AI model acts as a Senior Frontend Developer and generates clean, structured, production-ready code.

**Tech Stack**

Python

Streamlit

LangChain

Google Gemini (gemini-2.5-flash)

HTML5

CSS3

JavaScript (ES6+)

ZipFile (Python)

**How It Works**

User enters:

Webpage description

Webpage content

The prompt is structured using ChatPromptTemplate

Gemini model generates:

HTML

CSS

JavaScript

The code is split using custom delimiters:

--html--
--css--
--js--

Files are created dynamically

All files are zipped into website.zip

User downloads the generated website

**Project Structure**
Automatic-Webpage-Creation/
│
├── app.py
├── .env
├── requirements.txt
├── README.md

Generated at runtime:

index.html
style.css
script.js
website.zip
**Environment Setup**

Create a .env file and add your Gemini API key:

gemini_key=YOUR_GOOGLE_API_KEY

 **Installation & Run**

1️.Clone the Repository

git clone https://github.com/your-username/Automatic-Webpage-Creation.git

cd Automatic-Webpage-Creation

2️.Install Dependencies

pip install -r requirements.txt

3️.Run the App

streamlit run app.py

App will open at:

http://localhost:8501

**Features**

✅ AI-generated production-ready frontend

✅ Automatic file separation (HTML, CSS, JS)

✅ ZIP download functionality

✅ Clean prompt engineering

✅ Dynamic webpage generation

✅ Simple and user-friendly UI

**Example Use Cases**

Portfolio webpage generator

Interview questions webpage

Assessment MCQ page with result system

PDF downloadable report webpage

Landing page generator

Educational content website

**Demo**

(Add screenshots of your Streamlit app here)

**Key Learning Outcomes**

Prompt Engineering

LangChain Template Structuring

Generative AI Integration

File Handling in Python

Frontend Code Automation

Streamlit UI Development

**Connect With Me**

Praveen Reddy

Aspiring Data Scientist | GenAI Developer

https://www.linkedin.com/in/praveen-reddy-mudupu-728325354/
