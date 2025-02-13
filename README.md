# Chatbot Application using Streamlit and Gemini-Pro

## Overview

This project is a **Chatbot Application** built using Streamlit and Google's Gemini-Pro AI model. Users can interact with the chatbot in a conversational manner.

## Features

- **Chat Interface**: Streamlit-powered UI for real-time chat.
- **Google Gemini-Pro Integration**: Utilizes Gemini-Pro for AI responses.
- **Session Management**: Maintains chat history during interactions.
- **Environment Variable Support**: API key stored securely using dotenv.

## File Structure

- `app.py` - Main application file.
- `Requirements.txt` - List of dependencies required to run the application.

## Installation

1. Clone the repository:
   ```sh
   [git clone https://github.com/Bhayal07/Chatbot-App.git](https://urban-garbanzo-x556vg6gxr55fp6pg-8501.app.github.dev/)
   ```
2. Navigate to the project directory:
   ```sh
   cd Chatbot-App
   ```
3. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```
4. Install dependencies:
   ```sh
   pip install -r Requirements.txt
   ```

## Usage

1. Set up your environment variables:
   - Create a `.env` file in the project directory.
   - Add the following line:
     ```
     GOOGLE_API_KEY=your_google_api_key
     ```
2. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
3. Interact with the chatbot via the web UI.

## Requirements

- Python 3.x
- Streamlit
- google-generativeai
- python-dotenv

## Contributing

Feel free to fork this project and submit pull requests.

## License

This project is licensed under the MIT License.

---

*Developed by Chirag Bhayal*

