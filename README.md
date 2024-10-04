# End To End Resume ATS Tracking LLM Project With Google Gemini Pro

A web application that evaluates resumes against job descriptions using Google's Gemini AI and Applicant Tracking System (ATS) technology. This project processes PDF resumes, analyzes them against job descriptions, and provides a match percentage.

## Features

- **Resume Upload (PDF)**: Upload resumes in PDF format for analysis.
- **AI-Powered Analysis**: Utilizes Google Generative AI (Gemini model) to analyze resumes based on job descriptions.
- **Match Percentage**: Provides a score indicating how well a resume aligns with the job description.
- **ATS Evaluation**: Simulates Applicant Tracking Systems to assess resumes, identifying missing keywords.

## Technologies Used

- **Streamlit**: Web interface framework.
- **Google Generative AI (Gemini)**: For resume analysis and feedback.
- **Python Dotenv**: Manages environment variables.
- **PDF2Image**: Converts uploaded PDFs to images.
- **Pillow (PIL)**: Image handling and manipulation.

## Installation and Setup

Follow the steps below to set up the application locally:

### 1. Clone the repository:

```bash
git clone https://github.com/4Pranjal/End-To-End-Resume-ATS-Tracking-LLM-Project-With-Google-Gemini-Pro
```
Open the folder
```bash
cd End-To-End-Resume-ATS-Tracking-LLM-Project-With-Google-Gemini-Pro
```
## 2. Set up a Python virtual environment 
   ```bash
   python3 -m venv venv
   ```
or you can use conda to create environment.
On Windows use
   ```bash
venv\Scripts\activate
   ```
## 3. Install dependencies
Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 4. Set up environment variables
Create a .env file in the root directory of your project.
Inside this file, set your Google API key:
   ```bash
GOOGLE_API_KEY="your_google_api_key_here"
   ```
You can get your API key from the Google Cloud Console.

## 5. Run the applications
You can run each application by navigating to the project folder and executing the following command:

For Q&A Chatbot:
   ```bash
   streamlit run app.py
   ```
 

## Contributors

- [Pranjal Jain](https://github.com/4Pranjal)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
