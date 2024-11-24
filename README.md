# SM IntelliBot: AI-Driven Business & Research Companion

. Empowering Document Analysis, Translation and Multimedia Insights

# 🌟 Features : 

💬 AI-Powered Chatbot: Interact with an advanced AI assistant to get answers on various topics.

📄 Document Analysis: Upload and analyze content from PDFs, Word, PPTX and Excel files.

🌐 Web Content Analyzer: Extract and interact with website content by providing the URL.

🎧 Video-to-Audio Extraction: Extract and transcribe audio from video files.

🎙️ Podcast Generator: Turn PDF content into an audio podcast for easy listening.

🌍 Multilingual Translation: Translate text and documents into multiple languages.

📊 Text-to-SQL Conversion: Convert natural language queries into SQL statements.

🧑‍🏫 Research Assistant: Analyze research documents and get insights.

🧠 Sentiment & Emotion Analysis: Evaluate the sentiment and emotions from text or transcribed audio.


# 🚀 Getting Started : 

Prerequisites
Make sure you have the following installed:

Python 3.8+

Streamlit

Ollama AI (for LLaMA chatbot)

Additional dependencies in the requirements.txt file

# Installation : 

Clone the Repository:

git clone https://github.com/SHASHWAT-MISHRA-997/Advance-Chat-Assistant.git

Install Required Packages: Install all the necessary dependencies using pip:

pip install -r requirements.txt

Run the Application: Launch the Streamlit app:

streamlit run app.py

Access the Application: The app will run on http://localhost:8501. Open it in your browser.

# 💡 Usage : 

💬 Chat with the AI-BOT:

Text Input: Type your question or command in the provided text box (e.g., "What is the capital of Japan?" or "Explain quantum physics").
The AI will process your query and generate a detailed, accurate response in real-time.

Voice Input: Click the "Speak" button and the AI will listen to your voice command.
The app uses Google Speech Recognition to understand your voice input and respond accordingly.
Example: Say, "What's the weather like in Paris today?" and the bot will reply with up-to-date information.

📄 Chat with Documents:

Upload Files: Click the "Browse files" button to upload your document. Supported formats include:

PDF
Word (DOCX)
PowerPoint (PPTX)
Excel (XLSX)
Document Analysis: Once the document is uploaded, the app extracts the text and displays it.

You can now ask questions about the document, and the AI will provide insights based on the content.
Example: Upload a PDF of a research paper and ask, "What is the conclusion of this study?"
Multiple File Support: You can upload multiple files, and the app will combine and analyze the content collectively.

Example: Upload a research paper in PDF format and a supporting Excel file, then ask, "What are the key findings from the data?"

🌐 Chat with Websites:

URL Input: Enter the URL of a website you want to analyze (e.g., a news article or blog post).

The app will fetch and display the text from the website, removing irrelevant elements like ads or scripts.
Ask Questions: Once the website content is fetched, you can ask questions about the site’s content.

Example: Enter a URL for a Wikipedia page and ask, "What are the key points in this article?"
Content Analysis: The app can summarize large articles, analyze themes and even provide sentiment analysis of the content.

🎧 Chat with Media (Audio/Video):

Upload Video: Click "Upload Video" and select an MP4, AVI, or MOV file. The app will extract the audio from the video.

After the extraction, the app displays the audio transcript.
Ask About Audio: Once the audio is transcribed, you can ask the AI to analyze the content.

Example: Upload a lecture video and ask, "What are the main points of the discussion?"
Upload Audio: You can also upload audio files (WAV format) and the app will transcribe and analyze the content.

Example: Upload a podcast and ask, "What was the speaker's opinion on climate change?"
Sentiment & Emotion Analysis: After the transcription, you can ask the AI to analyze the sentiment and emotional tone of the speech.

Example: Upload a motivational speech and ask, "What is the emotional tone of this speech?"

🎙️ Podcast from PDF:

Upload PDF: Click "Upload PDF Document" to upload a PDF file.

The app will extract the text and display it for confirmation.
Generate Podcast: Click the "Generate Podcast" button to convert the extracted text into an audio file.

The app uses Google Text-to-Speech (gTTS) to generate a high-quality audio file.
Listen: Once the podcast is generated, you can listen to it directly within the app or download the MP3 file for later use.

Example: Upload a PDF research paper and convert it into a podcast for easy consumption while driving or exercising.

🌍 AI Translator:

Text Input: Type or paste the text you want to translate into the text box.

You can also upload a PDF document and the app will extract and translate the text.
Language Selection: Choose your target language from the drop-down menu.

Supported languages include English, Hindi, Spanish, French, German, Bengali, Tamil, Telugu, and more.
Translate: Click "Translate", and the app will display the translated text.

Example: Translate an English article into Hindi for wider distribution.

📊 Text to SQL:

Natural Language Query: Type a question in plain English (e.g., "Show all employees where salary is greater than 50,000").

Convert to SQL: Click the "Convert to SQL" button and the app will generate an SQL statement based on your query.

Example: Type "Get all customers who placed orders in the last 30 days" and receive an SQL statement like:
sql
Copy code
SELECT * FROM customers WHERE order_date > NOW() - INTERVAL 30 DAY;
Database Integration (optional): Use the generated SQL to query your database and retrieve results.

🧑‍🏫 Research Assistant:

Upload Research Documents: Upload PDFs or Word documents containing research material.

The app will extract the text and provide an interface to ask questions.
Ask Research-Specific Questions: Ask the AI questions directly related to the research content.

Example: Upload a PDF research paper on machine learning and ask, "What methodology was used in this study?"
Get Summaries and Insights: The AI can provide concise summaries or detailed answers about specific sections of your research.

🧠 Sentiment & Emotion Analysis:

Text Input or Audio Upload: Enter text or upload an audio file (WAV) to analyze.

Sentiment Analysis: The app will analyze whether the text is positive, negative, or neutral.

Example: Enter a product review and get feedback on whether the tone is positive or negative.
Emotion Analysis: The app can detect emotions like joy, sadness, anger, surprise, and more.

Example: Upload a customer testimonial and ask, "What emotions are present in this text?"


# 🌍 Languages Supported :

. English

. Hindi

. Spanish

. French

. German

. Bengali

. Tamil

. Telugu

# 🛠️ Technologies Used : 
Streamlit - Interactive web applications

Ollama - AI-powered language model integration

PyPDF2, docx, pptx, pandas - Document handling

MoviePy, SpeechRecognition, gTTS - Audio processing

BeautifulSoup, requests - Web scraping

SpaCy, Transformers - NLP and sentiment analysis

## 🎥 Working Video :

<a href="https://youtu.be/A2i7E-u_wKs">
    <img src="https://img.youtube.com/vi/A2i7E-u_wKs/0.jpg" alt="Watch the video" style="display: block; margin: 0 auto; width: 90%; max-width: 1000px;" />
</a>

# 🤝 Contributing :

I welcome contributions! If you want to help improve this project, feel free to submit a pull request or open an issue.

# 📄 License :

This project is licensed under the Apache-2.0 license. See the LICENSE file for more details.

# ✨ Credits :

Created by Shashwat Mishra



