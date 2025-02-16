   ![image](https://github.com/user-attachments/assets/c4ae9ba9-312e-4096-a32c-0434ca17b80b)

# ArogyaMitra: AI-Powered Virtual Nurse  

## Overview  

ArogyaMitra is an AI-powered virtual nurse assistant designed to provide intelligent medical support through voice interaction and computer vision. It can analyze wounds, suggest treatments, book doctor appointments, and send automated email confirmations. The system leverages AI-driven diagnostics and natural language processing to enhance healthcare accessibility.  

## Features  

- **Voice-Based Medical Assistance**: Provides real-time responses to health-related queries.  
- **Computer Vision for Wound Analysis**: Analyzes images to determine severity and suggest treatment.  
- **Automated Appointment Booking**: Schedules doctor visits and sends confirmation emails.  
- **AI-Driven Recommendations**: Suggests home remedies for minor issues and hospital visits for critical cases.  
- **24/7 Virtual Nurse Support**: Always available to assist users with healthcare concerns.  

## Technology Stack  

- **Frontend**: Streamlit 
- **Backend**: Flask 
- **AI Models**:  
  - NLP-based chatbot(Groq API,Whisper-large-v3,gemma2,deepgram client,ultravox)
  - Finetuned Qwen2.5VL-7B-Instruct based wound analysis for medical image(frames) processing  
  - Scheduling automation (Google Calendar API, Twilio)  
- **Database**: ChromaDB/SQL
- **Email Service**: SMTP,Phidata

## Installation  

Clone the repository  
```bash
git clone https://github.com/your-username/arogyamitra.git
cd arogyamitra
```
## Install dependencies

```bash
pip install -r requirements.txt  
```

## Run the application
```bash
Streamlit run app.py
```
## Usage

Start the dashboard and use voice commands for interaction to book any appointment using tab1.
Receive an email confirmation for scheduled appointments.
Ask any health related query to ArogyaMitra Chatbot for AI-powered diagnosis.
Uploads image and Videos for suggestions ralted to Cuts and Wound upto a certain threshold level.

## Future Enhancements

Integration with electronic health records (EHR) for personalized healthcare insights.
Multi-language support for broader accessibility.

