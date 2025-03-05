# FADHOS - Framework for Detection and Integration of Unstructured Data of Hate Speech on Facebook Using Sentiment Analysis

## Project Overview
FADHOS is a machine learning-based framework designed to detect and analyze hate speech within unstructured social media data, particularly on Facebook. The system leverages Natural Language Processing (NLP) techniques like sentiment and emotion analysis to identify harmful content and classify it efficiently.

## Features
- **Hate Speech Detection:** Uses NLP and machine learning models to identify dehumanizing or harmful language.  
- **Sentiment & Emotion Analysis:** Analyzes the tone and intent behind detected hate speech.  
- **Dataset Processing & Clustering:** Organizes detected hate speech for better evaluation.  
- **Machine Learning Integration:** Improves classification accuracy compared to existing solutions.  
- **Graph Analysis:** Identifies influential pages spreading hate speech on Facebook.  

## Tech Stack
- **Programming Language:** Python (3.8+)
- **Framework:** Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** MySQL
- **Machine Learning:** Scikit-learn, TensorFlow
- **NLP:** NLTK, SpaCy

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip
- MySQL
- Virtual Environment (optional but recommended)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/FADOHS.git
   cd FADOHS
   ```
2. Create and activate a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Set up the database:
   ```sh
   python manage.py migrate
   ```
5. Run the development server:
   ```sh
   python manage.py runserver
   ```

## Usage
1. Access the web interface at `http://127.0.0.1:8000/`
2. Upload datasets for processing.
3. View classified hate speech results and sentiment analysis.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any inquiries, feel free to reach out at [raviteja2675@gmail.com](mailto:raviteja2675@gmail.com).
