NCERT Concept Extractor & Resource Finder

This project processes NCERT Class 7 textbooks, extracts key concepts, and enriches them with detailed study breakdowns, relevant images, and YouTube learning resources. It leverages Google Gemini, Groq LLMs, Wikipedia, and the YouTube API to build a structured study assistant.

Features

Extracts top 10 key concepts from a given NCERT textbook file.

Generates detailed study notes for each concept:

Description, key topics, detailed explanation, real-life applications, exam tips, etc.

Fetches relevant images from Wikipedia with simple student-friendly captions.

Validates and classifies images into subtopics.

Finds relevant YouTube videos tailored for Class 7 NCERT students.

Provides alternative Wikipedia titles using Groq LLM if no images are found.

Requirements

Python 3.8+

Google Gemini API key

Groq API key

YouTube Data API key

Installation
pip install google-generativeai requests beautifulsoup4

Usage

Set your API keys:

export GEMINI_API_KEY="your_gemini_api_key"
export GROQ_API_KEY="your_groq_api_key"
export YOUTUBE_API_KEY="your_youtube_api_key"


Place your NCERT textbook text file in the project directory.

Run the script:

python main.py

Output

Prints top concepts and detailed breakdowns.

Displays validated Wikipedia images with captions and subtopics.

Links related YouTube videos for better understanding.
