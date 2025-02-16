![image](https://github.com/user-attachments/assets/78487baf-5f75-42e9-8d8e-dceb6e0e0b5e)

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

- **Frontend**: React.js  
- **Backend**: Flask / FastAPI  
- **AI Models**:  
  - NLP-based chatbot (Transformers, OpenAI API)  
  - CNN-based wound analysis for medical image processing  
  - Scheduling automation (Google Calendar API, Twilio)  
- **Database**: PostgreSQL / Firebase  
- **Email Service**: SMTP, SendGrid  

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

Start the dashboard and use voice commands for interaction.
Upload a wound image for AI-powered diagnosis.
Book an appointment through voice input.
Receive an email confirmation for scheduled appointments.

## Future Enhancements

Integration with electronic health records (EHR) for personalized healthcare insights.
Multi-language support for broader accessibility.
AI-powered medication recommendations based on medical history.
