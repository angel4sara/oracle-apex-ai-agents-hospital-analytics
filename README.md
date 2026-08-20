# Hospital Operations AI - Oracle APEX

Hospital Operations AI is an Oracle APEX application combining
hospital operational analytics with Generative AI and AI Agents.

## Features

- Patient management
- Patient Details modal form
- Appointment management
- Clinic management
- Follow-up tracking
- Hospital operations dashboard
- Appointment status analytics
- DNA (Did Not Attend) analysis
- Average waiting-time analysis
- Generative AI Hospital Operations Assistant

## AI Agent

The application includes an Oracle APEX AI Agent that allows users
to interact with hospital operational data using natural language.

Current AI tools include:

- `search_patient` - Search patients by patient number or name
- `get_patient_appointments` - Retrieve patient appointment history
- `appointment_summary` - Appointment counts and statistics
- `dna_analysis` - Calculate overall DNA statistics
- `get_patients_by_status` - Find patients by appointment status

Example questions:

- Find patient P1001
- Show appointments for P1001
- How many appointments are there today?
- How many completed appointments are there?
- What is the hospital's DNA rate?
- Which patients have DNA appointments?

## Analytics

The application provides operational analytics including:

- Total appointments
- Completed appointments
- Cancelled appointments
- DNA appointments
- Average waiting time
- Appointments by clinic
- Appointment trends
- DNA rates

## Technology

- Oracle APEX 26.1
- Oracle Database
- SQL / PL/SQL
- Oracle APEX Generative AI
- Oracle APEX AI Agents
- Cohere Generative AI API

## Database

Core tables:

- `PATIENTS`
- `CLINICS`
- `APPOINTMENTS`
- `FOLLOW_UPS`

All patient data included in this repository is fictional sample data
created for demonstration purposes.

## Architecture

User → Oracle APEX → AI Agent → AI Tools → Oracle Database → AI Response

## Disclaimer

This project is designed for hospital administrative and operational
analytics only. It does not provide medical diagnosis, clinical
decision support, or treatment recommendations.

This project used synthetic/made-up date, it doesn't have any similarities to any person 
