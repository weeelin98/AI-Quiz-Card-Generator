AI Quiz Card Generator
This is a simple HTML project that can run locally in your browser.

Project Description
The goal of this project is to create an app/webpage where users can upload a PDF or image containing exam questions. The program reads the file, analyzes each question to identify the correct answer, and generates detailed explanations based on a preset AI prompt. The user interface presents questions one by one, similar to Anki flashcards, making it easy to study.

Features
Supports PDF and Multi-Image Upload: You can upload a single PDF document or select multiple image files at once.

AI-Powered Analysis: Extracts questions, answers, and explanations using the Gemini AI.

Interactive Flashcards: Presents questions one by one in a flashcard-style interface.

Instant Feedback: Click on an option to see if you are correct, or flip the card to view the answer and detailed explanation.

Favorites Feature: A feature to add questions to a "favorites" list is planned for future development.

Configuration
To use the AI analysis feature, you need to obtain your own free Gemini API key from Google AI Studio and insert it into the project.

How to get your Gemini API Key:
Open your browser and go to Google AI Studio. You may need to log in with your Google account.

In the left menu, click Get API key.

Click Create API key in new project on the page that opens.

Copy the generated API key string.

How to add your API key to the project:
Open the project in VS Code (or your code editor).

Open the index.html file.

Find the following line in the JavaScript section (around line 400):
<pre>
const apiKey = ""; 
</pre>

Paste your API key between the quotes.

Issues to be Solved
UI Optimization: The user interface can be further improved for a better user experience.

Recognition Accuracy: The precision of PDF recognition, especially for questions involving charts and diagrams, needs improvement. A feature to display the relevant chart/image alongside the question text is also needed.

Performance: The file size limit is relatively large, which can lead to long loading and processing times. This needs to be optimized.
