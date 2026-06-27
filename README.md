# 📚 Study-to-Part – Integrated Student Job & Internship Portal

## Overview:

**Study-to-Part** is a responsive web application designed to connect college students with part-time jobs and internship opportunities. The platform provides an easy-to-use interface where students can browse job listings, apply for positions, and track their applications. It also demonstrates the use of modern HTML5 APIs, responsive web design, and client-side validation techniques.

---

# Problem Statement

Many students struggle to find suitable part-time jobs and internships that fit their academic schedules. At the same time, companies face difficulties in reaching qualified student candidates. There is a need for a centralized platform that connects students with employers, simplifies job applications, and allows application tracking in a user-friendly manner.

---

# Target Users

## Primary Users

* College and university students seeking part-time jobs and internship opportunities

## Secondary Users

* Companies and recruiters posting job openings.
* Educational institutions promoting student employability.

---

# Features Implemented

## Job Listings Dashboard

* Displays available job opportunities.
* Shows:
  * Job Title
  * Company Name
  * Job Type
  * Salary/Stipend
* Interactive buttons

## Application Management

* Students can apply using an online application form.
* Application status is shown as:
  * Pending
  * Accepted
  * Rejected

## Client-Side Form Validation

* Fields validation.
* Email format validation.
* Resume upload validation.
* Prevents invalid form submission.

## Responsive User Interface

* Fully responsive design using Tailwind CSS.
* Optimized for:
  * Desktop
  * Tablet
  * Mobile devices

## Dark Mode

* Toggle between Light and Dark themes.
* User preference is saved using the Local Storage API.

## Geolocation API

* Detects the user's current location.
* Displays nearby job opportunities.

## Browser Notification API

* Real-time alerts for new job opportunities.
* Notification updates every 10 seconds after permission is granted.

## Contact Page

* Contact form with validation.
* Company contact details.
* Business hours information.

---

# Technologies Used

## Technologies:

* HTML5
* CSS
* Tailwind CSS
* JavaScript

## HTML5 APIs Used

* Geolocation API
* Local Storage API
* Notification API

## Development Tools

* Visual Studio Code
* Google Chrome

---

# 📂 Project Structure

```
Study-to-Part/
│
├── index.html          # Main page
├── style.css           # Custom CSS styles
├── images/             # Job images and assets
├── README.md           # Project documentation
```

---

# How to Run the Project

1. Clone the project and paste in vs code.
2. Open the project folder.
3. Ensure all images and the CSS file are in the correct location.
4. Open **index.html** in Google Chrome or any modern browser.
5. Allow location and notification permissions when prompted.
6. Explore job listings and apply for available opportunities.

---

# Main Modules

* Home Page
* Job Listings Dashboard
* Application Form
* Applications Tracking
* About Us
* Contact Us
* API's

---

# Current Limitations

## No Backend Integration:

* Data is stored only temporarily.
* Applications disappear after page refresh.

## No Authentication:

* Users cannot register or log in.
* No recruiter accounts.

## Static Job Listings:

* Job data is hardcoded.
* Jobs cannot be added dynamically.

## No Database:

* Applications are not permanently stored.

---

# Future Scope

## User Authentication

* Student login
* Owner login

## Database Integration

* Store users
* Store jobs
* Store applications permanently

## Resume Management

* Upload resumes
* View and update resumes
* Download resumes

## AI-Based Job Recommendation

* Personalized job suggestions
* Skill-based recommendations

## Application Tracking

* Recruiter status updates
* Email notifications
* Interview scheduling

## Chat System

* Student–Recruiter messaging
* Real-time communication

## Admin Dashboard

* Manage users
* Manage job postings
* Generate reports
* Monitor applications

---

# AI Tools Used

| AI Tool        | Purpose                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------- |
| ChatGPT        | Debugging, JavaScript implementation, form validation, feature development, documentation |
| GitHub Copilot | Code completion, responsive layout assistance, page connections                           |

---

# Learning Reflections

Developing the **Study-to-Part** portal provided valuable practical experience in modern web development. During this project, I learned how to build responsive web interfaces using HTML5, CSS3, Tailwind CSS, and JavaScript. I gained hands-on experience implementing semantic HTML elements, responsive layouts, and client-side form validation.

I also learned how to integrate HTML5 Browser APIs such as the Geolocation API, Local Storage API, and Notification API to create a more interactive user experience.

Using AI tools like ChatGPT and GitHub Copilot improved my understanding of efficient coding practices, debugging techniques, responsive UI development, and JavaScript programming. These tools accelerated development while enhancing my problem-solving skills and overall understanding of front-end web application development.

