# nlp-powered-chatbot
A Streamlit-based chatbot for UI/UX Academy, powered by spaCy, designed to answer user queries about courses, enrollment, fees, schedules, and more. Features a friendly interface and natural language processing for seamless interactions.

# UI/UX Academy Chatbot 💬

A conversational chatbot built with Streamlit and spaCy to assist users in learning about UI/UX Academy's courses, admissions, schedules, and more.

## Features
- Responds to user queries using similarity-based matching.
- Offers predefined responses for common topics such as courses, enrollment, fees, and schedules.
- Provides default responses for off-topic queries.
- User-friendly interface styled with custom CSS.

## Tech Stack
- **Streamlit**: For the web interface.
- **spaCy**: For natural language processing and similarity calculations.
- **Python**: Backend logic and implementation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/uiux-academy-chatbot.git
   cd uiux-academy-chatbot
2. Set up a virtual environment (optional but recommended):

python -m venv env
source env/bin/activate    # On Windows: env\Scripts\activate

3. Install the required dependencies:
pip install -r requirements.txt

4. Download the en_core_web_sm spaCy model:
python -m spacy download en_core_web_sm
