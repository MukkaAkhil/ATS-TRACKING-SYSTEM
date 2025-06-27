ATS Resume Expert
Overview
ATS Resume Expert is a Streamlit application designed to help job seekers evaluate their resumes against job descriptions using AI. The application leverages Google’s generative AI to provide insights on how well a resume matches a job description and offers professional evaluations on strengths and weaknesses.

Features
Resume Upload: Upload resumes in PDF format for analysis.
Job Description Input: Input a target job description.
Match Score: Get a percentage match score indicating resume relevance to the job description.
Detailed Feedback: Receive tailored insights on resume strengths and weaknesses.
Prerequisites
Python 3.6 or higher
Required Packages:
streamlit
python-dotenv
Pillow
pdf2image
google-generativeai
Installation
Clone the Repository:

git clone https://github.com/yourusername/ATS-Resume-Expert.git
cd ATS-Resume-Expert
Install Dependencies:

pip install -r requirements.txt
Configure API Key:

Create a .env file in the root directory and add your Google API key:
GOOGLE_API_KEY=your_api_key_here
Usage
Start the Application:

streamlit run app.py
Access the App: Open your browser and go to http://localhost:8501.

Analyze Resume:

Upload your resume in PDF format.
Input a job description and click "Tell Me About the Resume" or "Percentage Match" to get a detailed evaluation.
Code Structure
app.py: Main Streamlit app file.
.env: Holds environment variables for API key configuration.
requirements.txt: Lists all package dependencies.
Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch for your feature or bug fix.
Make and commit your changes.
Push to your fork and submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions, suggestions, or collaboration inquiries, please reach out to:

Email: akhilmukka2004@gmail.com
GitHub: mukkaakhil
LinkedIn: Mukka Akhil
