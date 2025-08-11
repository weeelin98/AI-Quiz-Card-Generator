# AI Quiz Card Generator

This is a simple HTML project that can run locally in your browser.

## Project Description

The goal of this project is to create an app/webpage where users can upload a PDF or image containing exam questions.  
The program reads the file, analyzes each question to identify the correct answer, and generates detailed explanations based on a preset AI prompt.  
The user interface presents questions one by one, similar to Anki flashcards, making it easy to study.  
There is also a feature to add questions to favorites (currently under development).

## Features

- Upload PDFs or images with exam questions  
- AI-powered extraction of questions, answers, and explanations  
- Flashcard-style interface showing one question at a time  
- Ability to flip cards to see correct answers and detailed explanations  
- Favorites feature for bookmarking questions (planned)

## Configuration

To use the AI analysis feature, you need to obtain your own free Gemini API key from Google AI Studio and insert it into the project.

### How to get your Gemini API Key:

1. Open your browser and go to [Google AI Studio](https://studio.ai.google). You may need to log in with your Google account.  
2. In the left menu, click **Get API key**.  
3. Click **Create API key in new project** on the page that opens.  
4. Copy the generated API key string.  

### How to add your API key to the project:

1. Open the project in VS Code (or your code editor).  
2. Open the `index.html` file.  
3. Find the following line in the JavaScript section (around line 200):
<pre>
    const apiKey = ""; 
</pre>
