# PrepWise AI – AI-Powered Job Preparation Platform

An AI-powered career preparation platform that helps job seekers improve their employability through intelligent resume analysis, job description matching, skill gap detection, ATS-friendly resume generation, and personalized interview preparation.

## 📸 Application Screenshots

<!-- Add your GitHub-hosted screenshots below -->

<p align="center">
  <img src="https://github.com/user-attachments/assets/d8545a38-8887-4b59-baca-e7ef87f358b9" width="85%" alt="PrepWise AI Screenshot 1" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/303ed090-45db-4ac3-8d5c-47adb044ff88" width="85%" alt="PrepWise AI Screenshot 2" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c2a18388-f0e5-46dd-b17e-963656b9d4c7" width="95%" alt="PrepWise AI Dashboard" />
</p>

## ✨ Key Features

- **Secure Authentication:** User registration and login with JWT authentication and token blacklisting.
- **AI-Powered Resume Analysis:** Extracts and evaluates candidate information using Google Gemini API.
- **Job Description Matching:** Compares candidate profiles and resumes against target job requirements.
- **Skill Gap Analysis:** Identifies missing skills and highlights areas requiring improvement.
- **Personalized Interview Preparation:** Generates role-specific technical and behavioral interview questions with AI-powered answer guidance.
- **ATS-Friendly Resume Generation:** Generates tailored, downloadable PDF resumes using Puppeteer.
- **Personalized Learning Recommendations:** Suggests relevant skills and learning areas based on identified skill gaps.
- **Interview Dashboard:** Provides centralized access to interview reports, preparation history, and AI-generated insights.

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React.js, Vite, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas, Mongoose |
| Generative AI | Google Gemini API |
| Authentication | JWT, Token Blacklisting |
| PDF Generation | Puppeteer |
| State Management | React Context API, Custom Hooks |
| Development Tools | Git, GitHub, npm, VS Code |

## 📁 Project Structure

```text
AI-Job-Preparation/
│
├── Backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   │
│   ├── server.js
│   └── package.json
│
├── Frontend/
│   ├── public/
│   ├── src/
│   ├── index.html
│   └── package.json
│
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

- Node.js (LTS version)
- npm
- MongoDB Atlas account or MongoDB connection string
- Google Gemini API key

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd "Job-Preparation"
```

### 2. Configure the Backend

```bash
cd Backend
npm install
```

Create a `.env` file inside the `Backend` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_GENAI_API_KEY=your_gemini_api_key
```

Start the backend server:

```bash
npm run dev
```

### 3. Configure the Frontend

Open a new terminal:

```bash
cd Frontend
npm install
npm run dev
```

Open the local development URL displayed in the terminal (usually `http://localhost:5173`).

## 🔄 Application Workflow

1. Register or log in using secure authentication.
2. Upload your resume in PDF format OR text Self-Description.
3. Enter the target job description.
4. Analyze resume compatibility with job requirements.
5. Review identified skill gaps and personalized recommendations.
6. Generate tailored interview questions and preparation guidance.
7. Create and download an ATS-friendly PDF resume.
8. Track interview reports and preparation history through the dashboard.

## 🔐 Security

- JWT-based user authentication.
- Token blacklisting for authentication invalidation.
- Environment variables for sensitive credentials.
- MongoDB Atlas for persistent data storage.



