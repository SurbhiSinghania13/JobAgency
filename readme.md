# YMAgency Job Agency Website

## Overview

YMAgency is a Job Agency website developed using core PHP. It facilitates the process of job applications, allowing applicants to create profiles, and apply for jobs, and enables the admin to post job listings.

## Features

- **Job Listings:** Admin can post job openings.
- **Applicant Profiles:** Users can create applicant profiles. Users can upload resumes with the profile creation.
- **Application Submissions:** Applicants can apply for jobs. Admin can download resume files from the profile.
  
## Project Structure

The project consists of three main tables:

1. **Jobs:** Stores information about job listings.
2. **Applicants:** Contains details of the applicants.
3. **Applications:** Manages job applications.

## Usage

- Access the website by navigating to the project root.
- Applicants can create profiles, view job listings, and submit applications.
- Admins can log in to manage job listings and applicant data.

## Technologies Used

- **Backend:** Core PHP
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript, BootStrap


## 📥 How to Download and Run Locally

### ✅ Prerequisites
- XAMPP or WAMP installed on your machine
- PHP 7+ and MySQL

---

### 🧾 Steps

#### 1. **Clone the Repository**
```bash
git clone https://github.com/SurbhiSinghania13/JobAgency.git
```
#### 2. **Move the Project Folder**
 - For XAMPP: Move the folder into htdocs/

 - For WAMP: Move the folder into www/

#### 3. **Start Apache and MySQL**
 - Open the XAMPP/WAMP Control Panel

 - Start Apache and MySQL services

#### 4. **Import the Database**
 - Open phpMyAdmin

 - Create a new database named:
ymagency
 - Click Import and select the provided SQL file (jobboard.sql) from the project directory

 ### 🔐 Environment Configuration

A `.env` file is already included in the project.  
Please **open the `.env` file** and **add your local database details** as shown below:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=
DB_NAME=ymagency
```

 #### 5. **Access the Project in Browser**
http://localhost/JobAgency/
