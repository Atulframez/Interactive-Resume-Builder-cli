# Interactive Resume Builder

This Python project is a command-line interface (CLI) tool for building professional resumes. The tool allows users to interactively input various sections of their resume, such as contact information, work experience, education, skills, projects, certifications, and achievements. The resume is then formatted and exported as a PDF file.

## Features

- Interactive CLI for entering resume data (contact info, work experience, education, etc.).
- Ability to add, update, and modify multiple resume sections.
- Automatically generates a well-formatted PDF resume.
- Includes functionality to add detailed descriptions for work experience and projects.
- Supports multiple certifications and achievements.
- Simple and intuitive navigation using `prompt_toolkit` for menu interactions.

## Prerequisites

- Python 3.x must be installed on your system.

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/username/your-repo.git
    cd your-repo
    ```

2. **Create and activate a virtual environment**:

    For macOS/Linux:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

    For Windows:
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

3. **Install the necessary dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    python resume_builder.py
    ```

## Usage

- **Interactive Menu**: The program presents a menu to select which section of the resume you want to edit or add.
- **PDF Generation**: Once all sections are filled, you can generate a PDF with all the input data.
- **Options**:
    - Add or edit Contact Information, Work Experience, Education, Skills, Projects, Certifications, and Achievements.
    - Generate the PDF after completing the resume input.

## Dependencies

- `geopy`: For any geographic distance calculation (if needed for future features).
- `prompt_toolkit`: A library for building beautiful command-line applications.
- `fpdf`: A library for generating PDF documents from the entered resume data.

## License

This project is licensed under the MIT License.

## 🚀 Features

- Interactive menu-driven interface
- Add/Edit:
  - Contact Information
  - Work Experience
  - Education
  - Skills
  - Projects
  - Certifications
  - Achievements
- Generate professional PDF resume
- Multiple entries support (Experience, Education, Projects, etc.)
- Auto-opens generated PDF
- Clean and structured resume formatting

---

## 🧠 Tech Stack

- Python 3.x
- prompt_toolkit
- FPDF
- geopy (future enhancement support)

## 📑 Resume Sections Supported

Contact Information
Work Experience (multiple entries)
Education (multiple entries)
Skills
Projects
Certifications
Achievements

## 🎯 Learning Outcomes

Building interactive CLI applications
Menu-driven program design
PDF generation using FPDF
Structured data handling
Modular Python development
Real-world application development

## 🔮 Future Enhancements

Resume templates (Modern / Classic / Minimal)
Custom font support
Export to DOCX
Web version (Flask/FastAPI)
Resume preview before PDF generation
Cloud storage integration

## 👨‍💻 Author

Atul Anand
BCA (Hons)
Amity University, Noida

## ⭐ Support

If you like this project, please consider ⭐ starring the repository!
