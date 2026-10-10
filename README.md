# CivicMind 🏙️

**A Smart Civic Issue Reporting and Management Platform**

CivicMind is a web-based platform designed to help citizens report civic issues, track complaints, and bring attention to problems in their communities. By connecting a user-friendly frontend with a Supabase backend, the platform aims to make civic issue reporting more accessible and organized.

## 🎯 Project Objectives

- Make reporting civic issues simple and accessible.
- Allow citizens to submit complaints with relevant details.
- Store and retrieve complaints through a centralized database.
- Support community participation through complaint voting.
- Help organize complaints by category, location, severity, and status.

## ✨ Features

- **Civic Issue Reporting:** Submit complaints about problems in the community.
- **Complaint Management:** Store complaint details in a Supabase database.
- **Issue Tracking:** Display complaint status and relevant information.
- **Community Voting:** Allow users to vote for reported issues.
- **Issue Categorization:** Organize complaints by category and severity.
- **Responsive Web Interface:** Provide a user-friendly interface for interacting with the platform.

*Features depend on the current frontend implementation and backend integration.*

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML | Webpage structure |
| CSS | Styling and layout |
| JavaScript | Frontend interactions and backend communication |
| Supabase | PostgreSQL database and backend services |
| Git & GitHub | Version control and project hosting |

## 📁 Project Structure

```text
CivicMind/
├── index.html
├── assets/
├── supabase/
│   ├── schema.sql
│   └── complaints.js
├── README.md
└── .gitignore
```

*This is a suggested structure. Adjust the filenames and folders to match the actual files in your repository.*

## ⚙️ Setup and Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd CivicMind
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your repository's HTTPS URL.

### 2. Configure Supabase

1. Create or open your project in the [Supabase Dashboard](https://supabase.com/dashboard).
2. Open the SQL Editor.
3. Run the database setup script from `supabase/schema.sql`, if included.
4. Obtain your Supabase Project URL and publishable key.
5. Configure the frontend to use the correct project credentials.

### 3. Run the website

Open the project in Visual Studio Code and launch the frontend using a local development server, such as the Live Server extension.

Ensure the Supabase JavaScript library loads before the code that initializes the Supabase client.

## 🗄️ Backend Overview

CivicMind uses Supabase to store and retrieve civic complaints.

The planned complaint data includes:

- Complaint ID
- Title
- Category
- Location
- Description
- Severity
- Vote count
- Priority score
- Status
- Creation timestamp

The database schema and access policies should be configured in Supabase before testing backend operations.

## 🔐 Security

- Use a Supabase publishable key for browser-side applications.
- Never commit service-role keys, secret keys, database passwords, or private credentials.
- Enable and review Row Level Security (RLS) policies.
- Restrict sensitive actions, such as administrative status changes, to authorized users.
- Add appropriate validation and abuse protection before production deployment.

## 🚀 Future Improvements

- User authentication and personalized complaint tracking.
- Image uploads for civic complaints.
- Administrative dashboards for complaint resolution.
- Notifications when complaint statuses change.
- Improved prioritization of urgent civic issues.
- Maps and location-based issue discovery.

## 👥 Contributors

1. Lahari DN
2. Apeksha N
3. BR Nikita
4. Maanya Achar
