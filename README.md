# Resume Categorization

## Overview

This project was created to categorize resumes submitted by users for job applications. The system performs two primary tasks:

1. Adds the user information to a CSV file.
2. Categorizes the uploaded resume into relevant categories.

---

## Installation

Follow the steps below to set up and run the project:

### Step 1: Clone this Repository

Clone the repository to your local system:

```bash
git clone https://github.com/shehab0911/Resume-Categorization.git
cd Resume-Categorization
```

---

### Step 2: Create a Virtual Environment

Set up a virtual environment to manage dependencies:

```bash
python -m venv venv
source venv/bin/activate      # For Linux/Mac
venv\Scripts\activate        # For Windows
```

---

### Step 3: Install Dependencies

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

---

### Step 4: Run the Application

Launch the Streamlit application:

```bash
streamlit run app.py
```

---

## Features

- **Resume Upload**: Allows users to upload their resumes in various formats (e.g., PDF, DOCX).
- **Resume Categorization**: Automatically categorizes the resumes into relevant categories like Engineering, Data Science, Management, etc.
- **CSV Logging**: Saves user details and categorization results into a CSV file for further analysis.

---

## Repository Structure

```
Resume-Categorization/
├── app.py              # Main Streamlit application
├── requirements.txt    # Dependencies
├── utils/
│   ├── categorizer.py  # Resume categorization logic
│   ├── file_handler.py # File upload and processing logic
├── data/
│   └── resumes.csv     # Stores user and categorization data
└── README.md           # Project documentation
```

---

## How to Contribute

We welcome contributions to enhance the functionality of this project. Here's how you can contribute:

1. **Fork the Repository**: Click the "Fork" button on the top-right corner of this page to fork this repository.

2. **Clone Your Fork**:

   ```bash
   git clone https://github.com/your-username/Resume-Categorization.git
   cd Resume-Categorization
   ```

3. **Create a New Branch**:

   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Changes**: Implement your feature or fix a bug.

5. **Commit Your Changes**:

   ```bash
   git add .
   git commit -m "Describe your changes"
   ```

6. **Push to Your Branch**:

   ```bash
   git push origin feature/your-feature-name
   ```

7. **Submit a Pull Request**: Go to the original repository, click on "Pull Requests," and submit your pull request for review.

---

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for educational and personal purposes.

---



Happy coding! If you find this project useful, please ⭐ the repository!

