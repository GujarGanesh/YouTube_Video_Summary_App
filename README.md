Smart Summarize

Smart Summarize is an AI-powered content summarization and document generation tool, designed to simplify tasks like summarizing YouTube videos, PDFs, and converting text into PowerPoint presentations or PDFs. Built with Python and powered by Streamlit for a simple and intuitive user experience, Smart Summarize offers multiple features to streamline content generation and enhance productivity.

Features

🎥 Summarize YouTube Videos

Video Transcript Extraction: Automatically extract the transcript of a YouTube video using the URL.
Flexible Summarization Styles: Choose from various summarization formats such as bullet points, detailed paragraphs, short summaries, or key highlights.
Audio Summary: Once the summary is generated, you can also listen to the summary with text-to-speech functionality.

How to Use:
Enter the YouTube video link.
Select a summarization style.
Generate the summary and optionally listen to it.

📑 PDF Summarizer

PDF Text Extraction: Upload any PDF and extract the text content from it.
AI-Powered Summarization: Get a concise summary of lengthy PDFs, saving time and effort in reading.

How to Use:
Upload your PDF file.
Extract text and click the "Summarize PDF" button to generate a summary.

📜 Chat to PDF

Text to PDF Generation: Convert your text inputs into professional PDF files.
Simple Export: Download the generated PDF directly for easy sharing.

How to Use:

Enter your text.
Click the "Generate PDF" button and download the generated file.

📊 PPT Maker

Slide Creation: Quickly generate PowerPoint slides from manually entered content or uploaded text files.
Customizable Slide Content: Input slide titles and content manually, or upload a .txt file with pre-prepared content.

How to Use:
Enter slide content manually or upload a text file.
Click "Generate PPT" and download the file.

Installation
Clone the Repository:
bash code

git clone https://github.com/yourusername/smart-summarize.git

Navigate to the Project Directory:
bash code

cd smart-summarize

Install Required Dependencies: Ensure you have Python 3.x installed, then install the required Python libraries using:
bash code

pip install -r requirements.txt
Set Up Environment Variables:

Create a .env file in the root directory and add your Google API key for Google Gemini Pro:
makefile
Copy code
GOOGLE_API_KEY=your_google_api_key_here
Run the Application:

bash code
streamlit run app.py

Technologies Used

Python: Backend and logic for handling text extraction, summarization, and document generation.

Streamlit: Frontend framework for building the web app interface.

Google Gemini AI: API for generating AI-powered content summaries.

YouTube Transcript API: For extracting video transcripts.

gTTS (Google Text-to-Speech): To convert text summaries into speech.

PyPDF2: For PDF text extraction.

FPDF: For generating PDFs.

python-pptx: For generating PowerPoint slides.

How to Contribute
Fork the repository.

Create a new branch:
bash code

git checkout -b feature-branch

Make your changes and commit:

bash code

git commit -m "Your commit message"

Push to your forked repository:

bash code

git push origin feature-branch

Create a pull request.
License
