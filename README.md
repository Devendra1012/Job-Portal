
# MERN Job Portal

A full-stack job portal web application built using the MERN stack. This project helps users explore job opportunities and apply for jobs.

## Technologies Used

- **Frontend:** React.js, Vite
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, cookies
- **Other tools:** Axios, Git, GitHub

## Features

- User registration and login
- Browse available jobs
- View job details
- Company-related functionality
- Apply for jobs
- Backend API integration

## Project Structure

```text
JP/
├── client/       # React frontend
└── Backend/      # Express backend and APIs
```

## Getting Started

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd JP
```

### 2. Install frontend dependencies

```bash
cd client
npm install
```

### 3. Install backend dependencies

Open another terminal:

```bash
cd Backend
npm install
```

### 4. Configure environment variables

Create a `.env` file inside `Backend` and add your own configuration:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
```

Add any other environment variables required by your project. Never publish real passwords, JWT secrets, or API keys.

### 5. Run the backend

From the `Backend` folder:

```bash
npm run dev
```

### 6. Run the frontend

From the `client` folder:

```bash
npm run dev
```

Open the local URL shown in the frontend terminal, usually `http://localhost:5173`.

## Author

Devendrasinh Thakor

## License

This project is for learning and portfolio purposes.
