

 # Speech-to-Text Translation and Sentiment Analysis Application

![image](https://github.com/user-attachments/assets/f8fa4ac8-c18c-4900-8ca9-603e6aeffe92)



## Overview

This project is a web application that takes an audio file as input (in either Arabic or English) and processes it to perform speech-to-text conversion. It includes a language detection module to determine the spoken language, and based on the detected language, it translates the text and performs sentiment analysis. The application is built with a front-end interface and deployed on Azure.

## Features

- **Speech-to-Text Conversion**: Convert audio files into text format.
- **Language Detection**: Automatically detect the language of the spoken content (Arabic or English).
- **Translation**: Translate the detected text to the specified language.
- **Sentiment Analysis**: Analyze the sentiment of the translated text.
- **User-Friendly Frontend**: A simple interface for users to upload audio files and receive results.


## Project Structure
```
TELEK-APP/
├── env/                # Virtual environment for dependencies
├── templates/          # HTML templates for the web interface
├── app.py              # Main application file
└── requirements.txt    # Required Python packages
```

## UI
![image](https://github.com/user-attachments/assets/4a6c81a1-e1e5-4ecd-b460-b07e60d416b4)




## DEMO



https://github.com/user-attachments/assets/71da040d-99c3-4925-af95-7e10f7c64eed





https://github.com/user-attachments/assets/094fe3bf-b7be-4bb6-91b7-e469e68c3822





## Requirements

To install the necessary packages, run:

```bash
pip install -r requirements.txt
```

Install ffm (if not installed on the machine):

```bash
sudo apt update
sudo apt install ffmpeg
ffmpeg -version
```

Activate the virtual environment:

```bash
source env/bin/activate
```



Then run the application:

```bash
python app.py
```

## Deployment
This application is deployed on Azure. For details on deployment, refer to Azure documentation or check the deployment settings in the app. http://48.217.82.28:8080


## Usage
Upload an audio file (in Arabic or English) through the web interface.
The application will convert the audio to text, detect the language, translate the text, and perform sentiment analysis.
The results will be displayed on the interface.





