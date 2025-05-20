![Home page](https://github.com/user-attachments/assets/67b69f59-8f51-48a2-822c-e3de96918700)# SLT Mobitel Training Program Portal

A  web application for SLT Mobitel's training program management system designed with pure HTML, CSS, and JavaScript.

## Project Overview

This project implements a comprehensive web portal for SLT Mobitel's training programs and job vacancies. The system provides an intuitive interface for both job seekers and administrators to interact with training opportunities and manage applications.

## Features

### Public-Facing Features
- **Home Page**: Displays available job vacancies and company information
- **About Us**: Information about SLT Mobitel and its training programs
- **Job Vacancies**: Browse and search available positions
- **Job Application**: Submit applications with resume upload
- **Job Status Tracking**: Check application status

### Administrative Features
- **Admin Dashboard**: Overview of applications and job postings
- **Job Creation**: Add new job vacancies to the system
- **Job Modification**: Edit or delete existing job listings
- **CV Management**: Review received applications
- **Applicant Tracking**: Manage and track accepted candidates

## Project Structure

```
SLT-Mobitel-Training-Program/
├── home.html                   # Main landing page
├── components/                 # Page components
│   ├── aboutus.html           # About Us page
│   ├── applyjob.html          # Job application form
│   ├── jobstatus.html         # Application status tracker
│   ├── login.html             # User/admin login
│   ├── register.html          # User registration
│   └── vacancies.html         # Job listings
├── admin/                      # Admin section
│   ├── acceptedcv.html        # Accepted applications
│   ├── jobcreation.html       # Create job listings
│   ├── jobmodification.html   # Edit job listings
│   └── recievedcv.html        # Review applications
├── styles/                     # CSS stylesheets
│   ├── style.css              # Main stylesheet
│   └── login.css              # Login/register styles
└── images/                     # Image assets
    ├── logo.png
    ├── mobitel.png
    └── [other image files]
```

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Interactivity**: Vanilla JavaScript for form handling and navigation
- **Styling**: Custom CSS with responsive design

## Installation and Setup

1. Clone the repository:
   ```
   https://github.com/yrlwijesekara/mobitel_jobportal
   ```

2. Open the project in your preferred code editor

3. Launch the application by opening `home.html` in a web browser

## Usage

### Public Users
- Navigate to `home.html` to view available jobs
- Use the navigation bar to access various sections
- Apply for jobs through the application form
- Track application status through the job status page

### Admin Users
- Login with admin credentials (admin@admin.com/admin)
- Navigate to the admin dashboard to manage jobs and applications
- Create, modify, or delete job listings
- Review applications and update their status

## Development Notes
- The system currently uses client-side functionality only (no backend integration)
- Login credentials are hardcoded for demonstration purposes
- File uploads are simulated without actual storage

## Future Enhancements
- Backend integration with database support
- Email notifications for application status changes
- Advanced search and filtering for job listings
- Analytics dashboard for application metrics
- Mobile application integration

## Screenshots
![Home page](https://github.com/user-attachments/assets/67b69f59-8f51-48a2-822c-e3de96918700)
![Home page 2](https://github.com/user-attachments/assets/6c1864c2-82e5-49f8-91bb-f663affd7a14)
![Vacancies page](https://github.com/user-attachments/assets/d19e1edf-8e5c-4489-8e19-82d73f01d5f9)
![Admin panel](https://github.com/user-attachments/assets/1f8ebe40-0fcb-45fa-a933-ab90729e445b)






## Contributors
- YRL Wijesekara

## License
This project is proprietary software developed for SLT Mobitel.
