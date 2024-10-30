# Project Setup Instructions

This project consists of three parts: the frontend, the backend, and the AI. Follow the instructions below to set up each part.

## Frontend Setup

1. Navigate to the `web` directory and Install the necessary npm packages:

```bash
cd web

npm install
```

2. Add environment variables to the `.env` file and place it in web folder:

```bash
VITE_APPWRITE_PROJECT_ID'
VITE_APPWRITE_URL'
VITE_APPWRITE_DATABASE_ID'
VITE_APPWRITE_DASHBOARD_COLLECTION_ID'
VITE_APPWRITE_STREAM_COLLECTION_ID' 
VITE_APPWRITE_USER_SOCIALMEDIA_ACCOUNTS_COLLECTION_ID'
VITE_APPWRITE_REPORT_CHART_COLLECTION_ID'
VITE_APPWRITE_SOCIALMEDIA_FEEDS_COLLECTION_ID'
VITE_APPWRITE_POSTS_REPLIES_COLLECTION_ID'
VITE_APPWRITE_USER_PROFILE_COLLECTION_ID'
VITE_APPWRITE_BUGREPORTS_COLLECTION_ID'
VITE_APPWRITE_BILLINGS_COLLECTION_ID'
VITE_APPWRITE_SUBPLAN_COLLECTION_ID'
VITE_APPWRITE_USERACCOUNT_COLLECTION_ID'

REACT_APP_BASE_URL=localhost:8080/api/v1
```

3. Start the development server:

```bash
npm run dev
```

## Backend Setup

1. Clean and install the project (for Windows OS):

```bash
.\mvnw clean install
```

2. Run the Spring Boot application:

```bash
.\mvnw spring-boot:run
```

## AI Setup

1. Navigate to the Hugging Face AI directory:

```bash
cd "Hugging Face AI"
```

2. Create a virtual environment using Python 3.10 and activate it:

```bash
python3.10 -m venv env
source env/bin/activate
```

3. Install the necessary Python packages:

```bash
pip install -r requirements.txt
```
