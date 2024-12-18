# AI Vision and Weather Application

This project is an interactive AI chatbot with vision and weather application that integrates multiple technologies, including speech recognition, text-to-speech, weather updates, and real-time computer vision using a camera feed. The project uses **JavaScript**, **Python**, and **Eel** to build a web-based interface that communicates with backend systems to process speech commands and generate responses using Google's Generative AI, Gemini-1.5-flash. And also uses various API's for speech recognition.

## Features

1. **Speech Recognition and Text-to-Speech**:
   - The application listens to user speech, interpret it, and processes commands.
   - It uses the browser’s Speech Recognition API to capture user input.

2. **Generative AI**:
   - The project integrates Google's **Gemini-1.5-flash** model for AI-based content generation.
   - The AI processes user input, generates responses, and delivers them back to the user in speech and text.

3. **Weather Widget**:
   - The application displays real-time weather data for the user's current location.
   - It uses the `api-ninjas.com` weather API to fetch the latest temperature, humidity, wind speed, and sunrise/sunset times.

4. **Computer Vision**:
   - A live video feed from the camera is displayed, and the feed can be processed for image-based AI tasks like content generation using **Google Generative AI**.

5. **Time Widget**:
   - A clock widget displays the current time, updated every second.
6. **IP_info**
   - Uses the `http://ipinfo.io` for getting the approximate location based on IP address.

## Technologies Used

- **JavaScript (Browser APIs)**:
  - Speech Recognition and Text-to-Speech.
  - Weather data visualization and real-time updates.
  
- **Python**:
  - video feed processing using **OpenCV**.
  - Speech-to-text and weather data handling via API requests.
  - Communication between frontend and backend using **Eel**.

- **Google Generative AI**:
  - Integrated for processing user commands and generating intelligent responses.

## Setup Instructions

### Prerequisites

- Install Python 3.x
- Install **Eel** Python library: 
    ```bash
    pip install eel
    ```
- Install **OpenCV** for Python:
    ```bash
    pip install opencv-python
    ```

### API Keys

- Configure your **Google Generative AI** and **Weather API** keys in a `config.py` file:
    ```python
    Config = {
        'API-KEY': 'YOUR_GOOGLE_GENERATIVE_AI_KEY',
        'API_KEY_weather': 'YOUR_WEATHER_API_KEY'
    }
    ```

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ai-vision-weather.git
   cd ai-vision-weather
