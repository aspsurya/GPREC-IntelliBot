# GPREC IntelliBot

An AI-Powered Navigator and Information Hub for GPREC Students.

## Abstract

Transitioning into college life can be challenging for new students, who often struggle to access essential information related to campus navigation, administrative procedures, and placement processes. To bridge this gap, we present GPREC IntelliBot – an intelligent, multilingual student assistant that leverages machine learning and natural language processing (NLP) to deliver personalized, real-time guidance and support. The proposed system goes beyond static rule-based bots by integrating core ML components to enhance user interaction and adaptability.

## Key Features

* **NLP-Based Query Handling:** Understands and responds to diverse student queries using natural language processing.
* **Interactive Campus Map:** Offers a visual, clickable map for exploring campus locations and navigation.
* **Placement Analyzer and Predictor:** Recommends eligible companies based on student profiles and past placement data.
* **Real-Time Notification System:** Delivers timely updates on events, exams, and placements, personalized using ML.
* **Voice Interaction Support:** Allows hands-free question asking through speech recognition and intent detection.

## Project Setup

### Backend

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/aspsurya/gprec-intellibot.git
    cd gprec-intellibot
    ```
2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Download NLTK data (if not already present):**
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('wordnet')
    nltk.download('omw-1.4')
    ```
5.  **Download SpaCy model:**
    ```bash
    python -m spacy download en_core_web_sm
    ```
6.  **Run the backend server:**
    ```bash
    cd backend
    python app.py
    ```

### Frontend

1.  **Navigate to the frontend directory:**
    ```bash
    cd frontend
    ```
2.  **Install Node.js dependencies:**
    ```bash
    npm install
    ```
3.  **Start the development server:**
    ```bash
    npm start
    ```

## Usage

* Access the frontend application through your web browser (usually `http://localhost:3000`).
* Interact with the chatbot by typing queries or using voice commands.
* Explore the interactive campus map.
* Input student profile data to get placement recommendations.
* Receive personalized notifications.

## Development

Refer to the individual component sections for detailed development guidelines.

