# TalkYT - Chrome Extension for Chatting with YouTube Videos

TalkYT is a Chrome extension that allows users to interact with YouTube videos using natural language. By integrating transcript analysis with AI models, TalkYT enables students, developers, and learners to ask questions about a video and receive timestamped answers and extracted content, such as code snippets or formulas. The extension is powered by LangChain and Google Gemini (via the Generative AI SDK).

## Project Description

YouTube is a popular resource for learning, but navigating long videos to find specific information can be time-consuming. TalkYT solves this problem by enabling users to ask questions about the content of a YouTube video and receive instant, relevant answers with timestamps and context, without having to manually scrub through the video.

The backend processes YouTube transcripts, embeds them using vector search, and retrieves the most relevant sections to respond to user queries.

## Features

- Ask natural-language questions about YouTube videos
- Receive timestamped responses that point to specific parts of the video
- Extract and copy key information such as code blocks or formulas
- Supports developers, students, and self-learners in efficiently navigating long-form content

## Tech Stack

**Frontend**
- HTML, CSS, JavaScript
- Chrome Extension APIs

**Backend**
- Python, FastAPI
- LangChain for orchestration
- Gemini API via Google Generative AI SDK

## Installation

### 1. Clone the Repository


git clone https://github.com/codingbot221/TalkYT.git <br>
cd talkYT <br>

## 2. Load the Chrome Extension

Open Google Chrome and go to chrome://extensions   <br>

Enable "Developer Mode" (top right)  <br>

Click "Load Unpacked"  <br>

Select the extension/ folder inside the project directory <br>

## 3. Using the Extension
Visit any YouTube video  <br>
  
Click the TalkYT extension icon  <br>

Ask a question about the video content in the popup interface  <br>




### Running the Backend Locally (Optional)
If you want to run the backend on your local machine:  <br>

## 1. Navigate to the backend folder

cd backend  <br>

## 2. Install the dependencies

pip install -r requirements.txt <br>

## 3. Start the server

uvicorn main:app --reload <br>
Ensure your frontend is configured to send requests to http://localhost:8000/chat instead of the production URL when testing locally.  <br>

## Configuration Notes
Make sure the Gemini API key is configured properly in your backend environment. <br>

Ensure CORS middleware is correctly set up in FastAPI to allow requests from the Chrome extension.  <br>



### Contribution Guidelines
- Contributions are welcome and encouraged. To contribute: 

Fork the repository  <br>

Create a new branch (git checkout -b feature-name)  <br>

Commit your changes (git commit -m 'Add new feature')  <br>

Push to your branch (git push origin feature-name)  <br>

Open a pull request with a clear description of your changes  <br>

Before submitting a pull request, please ensure:  <br>

The code follows standard style conventions  <br>

Changes are well-documented  <br>

New features include relevant updates to the README (if applicable)   <br>

## Photos
![IMG_2040](https://github.com/user-attachments/assets/12ce649d-33d2-4fdb-b23d-da7958cf90bc)  <br> <br>
![IMG_2041](https://github.com/user-attachments/assets/3ea932a3-dcb9-4dd1-a18e-6b0645920c8b)  <br> <br>
![IMG_2042](https://github.com/user-attachments/assets/20d8cd93-f314-487d-9172-6a489efa6017)  <br> <br>
![IMG_2043](https://github.com/user-attachments/assets/d89f4e37-5f3f-4189-8e65-fb67aebdc235)  <br> <br>



