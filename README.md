# Vadodara Common Services Center (VCSC)

VCSC is an online crime-reporting platform designed to help citizens securely and anonymously report suspicious activities in their surroundings. The platform focuses on privacy, ease of access, and removing the hesitation commonly associated with filing complaints. Users can report incidents, share details, and view important community information without revealing their identity.

---

## Features

### Anonymous Complaint Submission
Users can report crimes without sharing personal identity details. The system records essential information such as location, pincode, and nature of the incident.

### Secure Storage and Retrieval
All reports are stored in a structured database using PHP and MySQL. Complaint entries are dynamically fetched and displayed for authorized review.

### Simple and Accessible User Interface
A lightweight HTML-CSS-JS interface ensures fast loading and easy navigation. The design focuses on clarity so that users can file reports without confusion or friction.

### Multi-Page Workflow
The website includes:
- Home page introducing the purpose of the service  
- About page describing the platform  
- Complaint submission page  
- Authentication and login pages for administrators  
- A dashboard that displays complaint data  

### Real-Time Complaint Table
Submitted reports are shown in a tabular format for review. Each entry includes:
- Complaint number  
- Complainant name (if shared)  
- Location  
- Pincode  
- Complaint category or rank  

### Backend Form Handling
PHP scripts manage:
- Form submissions  
- Data validation  
- Database insertion  
- Secure redirection after successful submission  

---

## Tech Stack

The project is built using a combination of:

- HTML  
- CSS  
- JavaScript  
- PHP  
- MySQL  

---

## Project Structure

Key files and folders include:

- `home.html` – Landing page  
- `about.html` – Overview of the platform  
- `form.html` – Crime submission form  
- `submit.php` – Backend complaint processor  
- `contacts.html` – User support page  
- `auth.html` – Admin login page  
- `styles.css` – Core stylesheet  
- `submitthanks.html` – Confirmation page  

---

## Purpose

The intention behind VCSC is to create a platform that empowers citizens to report suspicious or unsafe activities without fear of repercussions. It also raises awareness and builds a more informed and proactive community.

---

## Challenges and Solutions

During development, several challenges were addressed:
- Ensuring smooth database connectivity  
- Handling complaint submissions securely  
- Designing a front-end interface that is minimal and user friendly  
- Displaying dynamic complaint records effectively  

With systematic debugging and optimization, all major issues were resolved successfully.

---

## Live Demo

The website is deployed and accessible here:

https://vcsc.netlify.app/

---

## Screenshots

<img width="1850" height="1574" alt="image" src="https://github.com/user-attachments/assets/1b72f49e-7ced-41b2-abf6-62da596da5fe" />

---

## How to Run Locally

1. Clone the repository  
2. Import the SQL file into MySQL  
3. Configure database credentials in the PHP backend  
4. Run the project using any local PHP server (XAMPP, MAMP, WAMP)  

```bash
php -S localhost:8000
```

Open your browser at `http://localhost:8000`
