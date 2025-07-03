 
# Checklog - Interview Scheduler

## ✅ Completed Tasks

- **GET** `/api/hr/interview`  
  → Fetches and returns candidate data from the database.

- **POST** `/api/hr/interview`  
  → Uploads the candidate's resume to Google Drive and stores their data in the database.

- **PATCH** `/api/hr/interview`  
  → Updates the interview status of a candidate by finding them via their ID.

- **DELETE** `/api/hr/interview`  
  → Deletes a candidate's record from the database using their ID.

- **PUT** `/api/hr/interview`  
  → Updates candidate details and resume by locating the user via ID and applying changes.

- **POST** `/email/send`  
  → Sends an interview-related email to the candidate and HR team members.