# AI Resume & Cover Letter Generator 🚀

## Overview
The **AI Resume & Cover Letter Generator** is a Streamlit-based web application that helps users create personalized cover letters and analyze resume-job description match scores using AI and NLP techniques.

## Features
- 📄 **Upload a Resume (DOCX format)**
- 🔍 **Extract Skills from Resume using NLP**
- 🤖 **Generate Personalized Cover Letters using OpenAI GPT-4**
- 🎯 **Calculate Resume-Job Description Match Score**

## Technologies Used
- **Python**
- **Streamlit** (for the UI)
- **OpenAI GPT-4** (for generating cover letters)
- **NLTK** (for text processing)
- **scikit-learn** (for similarity analysis)
- **docx2txt** (for extracting text from DOCX files)

## Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/ai-resume-and-cover-letter-generator.git
cd ai-resume-and-cover-letter-generator
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Set Up OpenAI API Key
Create a `.env` file in the project directory and add:
```sh
OPENAI_API_KEY=your_openai_api_key_here
```
Or set it in your environment variables.

### 4️⃣ Run the App
```sh
streamlit run project.py
```

## Usage
1. Upload your **resume (DOCX format)**.
2. Paste the **job description**.
3. Get:
   - A **personalized cover letter**.
   - Your **resume match score**.
   - Extracted **skills** from your resume.

## Contributing
Feel free to fork this repository and submit pull requests with improvements! 🚀

## License
MIT License

