# AI Resume Screening & Candidate Ranking System

## Problem Statement
In the modern recruitment process, organizations receive an overwhelming number of resumes for each job opening. Screening these resumes to identify the most suitable candidates is a time-consuming and labor-intensive task. Automating this process using machine learning and natural language processing (NLP) techniques can significantly improve the efficiency and effectiveness of recruitment.

## Proposed Solution
To address the challenges of automating the resume screening process, we propose a solution that leverages deep learning and natural language processing (NLP) techniques. The solution will involve developing a comprehensive pipeline that handles:

- **Job description matching**
- **Candidate ranking**

The final product is a web-based application that recruiters can use to streamline the initial stages of the recruitment process.

## Features
### Resume Processing
- **Extracting User's Information**: Using PyResparser to extract user details from resumes.
- **Extracting Resume Text**: Using PDFMiner to convert PDF resumes into text for processing.

### User & Admin Sections
- **Resume Score**: Provides a score based on how well the resume matches the job description.
- **Career Recommendations**: Suggests career paths based on the user's skills and experience.
- **Resume Writing Tips**: Offers suggestions to improve the resume.
- **Courses Recommendations**: Recommends relevant courses to enhance skills.
- **Skills Recommendations**: Suggests skills to add to the resume.
- **YouTube Video Recommendations**: Provides links to relevant YouTube videos for skill improvement.

### Machine Learning
- **KNN Algorithm**: Used in `Classifier.py` for resume classification and ranking.

## Usage
### Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/ai-resume-screening.git
cd ai-resume-screening
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```
Set up XAMPP or any other control panel and turn on the Apache & SQL services.

### Running the Application
Run the Streamlit application:
```bash
streamlit run App.py
```
Open your web browser and navigate to the provided localhost URL to access the application.

### Admin Access
- **Username**: deepu_sid
- **Password**: deepu@21

## Future Scope
- **Advanced NLP Techniques**: Integrate advanced NLP techniques like BERT or GPT for improved contextual understanding and semantic matching.
- **Custom-Trained Deep Learning Model**: Implement a custom-trained deep learning model for more accurate resume ranking.
- **Structured Data Extraction**: Incorporate structured data extraction from resumes to better assess qualifications and skills.
- **Interactive Dashboards**: Expand with interactive dashboards for data visualization and improved user interaction.
- **Multi-Language Support**: Add multi-language support to cater to a global audience.
- **Security Measures**: Strengthen security measures for robust protection of data and system integrity.
- **Regular Updates**: Establish regular updates and feedback loops for continuous improvement and adaptability to industry changes.

## Project Structure
- `App.py`: The main Python file for the Streamlit web application.
- `Courses.py`: Contains courses and YouTube video links for recommendations.
- `Uploaded_Resumes/`: Folder containing user-uploaded resumes.
- `Classifier.py`: Contains the KNN algorithm for resume classification.
- `requirements.txt`: Lists all the dependencies required to run the project.

## 📸 Image Gallery

### Admin Dashboard
![Admin Dashboard](screenshots/admin_dashboard.png)

### Resume Processing
![Resume Processing](screenshots/resume_processing.png)

### Career Recommendations
![Career Recommendations](screenshots/career_recommendations.png)

### Running the Application
![Application Running](screenshots/app_running.png)

### Admin Dashboard
![Admin Dashboard](screenshots/admin_dashboard.png)


## Acknowledgments
Thanks to the open-source community for providing the tools and libraries that made this project possible.

Special thanks to the contributors who helped in developing and testing the system.

## Contact
For any queries or support, please contact:

- **Name**: Deepika Sidda
- **Email**: siddadeepika@gmail.com
- **GitHub**: [DeepikaSidda](https://github.com/DeepikaSidda)

