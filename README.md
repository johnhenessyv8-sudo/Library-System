# NEU LibConnect - Library Visitor Management System

A specialized visitor management and logging system designed for New Era University Library.

## Features

- **Automated Check-in**: Kiosk-style interface for students and faculty to log their visits with strict verification.
- **Admin Dashboard**: Real-time statistics, college distribution charts, and automated login logs.
- **Member Management**: Create, edit, and delete library profiles with automated ID generation (e.g., Student-001, Admin-005).
- **Security**: Mandatory NEU institutional email verification and administrative access control.
- **Data Export**: Export the entire visitor log to CSV for use in Microsoft Excel.

## How to move this to your computer

### 1. Push to GitHub (Best for Saving)
If you have a terminal open here, run these commands:
```bash
git init
git add .
git commit -m "Final version of NEU LibConnect"
# Create a new repo on github.com then:
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

### 2. Running the App Locally
Once you have the files on your computer:
1. **Install Dependencies**: Open your terminal in the project folder and run:
   ```bash
   npm install
   ```
2. **Start the Development Server**:
   ```bash
   npm run dev
   ```
3. **View the App**: Open [http://localhost:3000](http://localhost:3000) in your browser.

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Database**: Firebase Firestore
- **Authentication**: Firebase Auth (NEU Institutional Email Only)
- **UI Components**: ShadCN UI & Radix UI
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Charts**: Recharts
