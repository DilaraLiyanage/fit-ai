# Fit-AI

Fit-AI is a beginner-friendly full-stack web application that predicts health risks such as diabetes using AI. It combines a Python machine learning model, a Java Spring Boot backend, and a React frontend to provide users with personalized health risk assessments based on their biological data.

## Features

- Predicts risk of diabetes using an AI model trained on medical datasets  
- Interactive frontend built with React for user-friendly data input  
- Robust Java Spring Boot backend managing API requests and database operations  
- Stores user inputs and prediction history for future reference

## Technologies Used

- **Python** (scikit-learn) — AI model and prediction  
- **Java** (Spring Boot) — Backend API and database integration  
- **React.js** — Frontend user interface  
- **MySQL** — Data storage  
- **Git & GitHub** — Version control and collaboration


## Technology Stack

| Layer                                | Technology           |
|--------------------------------------|----------------------|
| AI Model and Prediction              | Python, scikit-learn |
| Backend API and Database Integration | Java, Spring Boot    |
| Frontend UI                          | React.js             |
| Database                             | MySQL / PostgreSQL   |
| Version Control and Collaboration    | Git & GitHub         |


## Getting Started

### Prerequisites

- Python 3.12+  
- Java JDK 17+  
- Node.js & npm  
- MySQL server installed and running


### Installation

1. **Clone the repository**  
```bash
git clone https://github.com/YOUR-USERNAME/fit-ai.git
cd fit-ai
````

2. **Set up Python AI service**

* Navigate to the AI service folder (`ai-predictor/`)
* Install required Python packages:

```bash
pip install -r requirements.txt
```

* Train and save the AI model:

```bash
python ai_model.py
```

3. **Set up Java backend**

* Open `backend/` folder in your favorite IDE (e.g., IntelliJ IDEA or VS Code with Java extensions)
* Configure database connection in `application.properties`
* Run the Spring Boot application

4. **Set up React frontend**

* Navigate to `frontend/` folder
* Install dependencies:

```bash
npm install
```

* Run the React app:

```bash
npm start
```


## Usage

* Open the React frontend in your browser
* Input your health data such as age, weight, blood pressure, glucose levels
* Submit the form to receive your personalized health risk prediction
* View your past predictions in the history section


## Contact

Created by Dilara Liyanage.
Connect with me on [LinkedIn](https://www.linkedin.com/in/dilara-liyanage-65b20b220/).
