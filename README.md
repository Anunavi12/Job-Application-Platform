#Job Portal

Job Portal is a web application built using the MERN stack, designed to simplify the job application
process. Users can choose their role as either an applicant or a recruiter and create an account to
get started.

Once logged in, recruiters can create, update, or delete job postings, as well as shortlist, accept, or
reject applications and view resumes. Applicants can browse job listings, use filters for a tailored
search, apply for jobs by submitting a Statement of Purpose (SOP), view their applications, upload a
profile picture and resume, and edit their profiles. This platform aims to provide a comprehensive
solution for job applications.

#Directory Structure
- backend/
 - public/
 - profile/
 - resume/
- frontend/
- README.md

#Getting Started:

Follow these steps to set up the web app on your machine:
1. Install Required Software:
 - Make sure you have Node.js and MongoDB installed.
2. Start the MongoDB Server:
  bash
 sudo service mongod start

3. Set Up the Backend:
 - Navigate to the backend directory:
  bash
 cd backend

 - Install backend dependencies:
  bash
 npm install

 - Start the Express server:
  bash
 npm start

 - The backend server will run on port 4444.
4. Set Up the Frontend:
 - Go back to the main directory and then navigate to the frontend directory:
  bash
 cd ../frontend

 - Install frontend dependencies:
    bash
 npm install
    
 - Start the frontend server:
    bash
 npm start
    
 - The frontend server will run on port 3000.
5. Access the Web App:
 - Open your browser and go to http://localhost:3000/. You can start creating jobs and applications
by signing up in your chosen role.

#Dependencies:

Frontend
- @material-ui/core
- @material-ui/icons
- @material-ui/lab
- axios
- material-ui-chip-input
- react-phone-input-2

Backend
- bcrypt
- body-parser
- connect-flash
- connect-mongo
- cors
- crypto
- express
- express-session
- jsonwebtoken
- mongoose
- mongoose-type-email
- multer
- passport
- passport-jwt
- passport-local
- uuid

