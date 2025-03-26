# 🧠 Psychological Services App

## 📌 Project Overview

VocabBuilder is a web application designed to help users expand their vocabulary. The app allows users to search, filter, and view words in a dictionary, as well as complete training exercises to reinforce their knowledge.

## ✨ Key Features

### 🏠 Home Page

A welcoming interface displaying the company's slogan.

A call-to-action button that directs users to the list of available psychologists.

### 📋 Psychologists Page

Displays a list of psychologists with key details such as name, experience, specialization, price per hour, and rating.

Sorting options to arrange psychologists by name, price, or popularity.

A "Load more" button to fetch additional psychologists from the database.

Ability to view more details about each psychologist by clicking "Read more."

### ❤️ Favorites Page (Private)

Accessible only to authenticated users.

Displays psychologists marked as favorites.

Users can remove psychologists from favorites.

### 🔐 Authentication

User registration and login using Firebase Authentication.

Secure data retrieval for authenticated users.

Logout functionality.

## 📦 Firebase Integration

Psychologists' data stored in Firebase Realtime Database.

Users' favorite psychologists stored in Firebase or localStorage.

Authentication management via Firebase Authentication.

## 📅 Appointment Booking

A modal form to book an appointment with a psychologist.

Form validation using react-hook-form & yup.

Modal closes on clicking outside, pressing Esc, or clicking the close button.

## 🌐 Routing

Implemented using React Router.

Protected routes for private pages (e.g., Favorites).

## 🛠 Technologies Used

React – for building the user interface.

React Router – for managing navigation.

Redux Toolkit – for state management.

Firebase – for authentication and database storage.

react-hook-form & yup – for form handling and validation.

Styled Components / Tailwind CSS / Material UI – for styling.

ESLint & Prettier – for code formatting and quality assurance.

## 🏗 Installation Instructions

### 1️⃣ Clone the Repository

```sh
git clone git@github.com:Yarik2019/Psychologists.Services.git
cd Psychologists.Services
```

### 2️⃣ Install Dependencies and Run

```sh
npm install
npm run dev
```

The application will be accessible at:👉 http://localhost:5173

## 📖 How to Use

Visit the Home Page to learn about the service.

Go to the Psychologists Page to browse available professionals and sort them based on your preference.

Click Read More for detailed information about a psychologist.

If authenticated, click the heart icon to add psychologists to Favorites.

Click Make an Appointment to schedule a session.

Navigate to the Favorites Page to review saved psychologists.

## 🚀 Deployment

The project is deployed on Vercel:🔗 [Live Demo](https://psychologists-services-sepia.vercel.app/)

## 🎨 Design & Documentation
 🔗 Figma Design: [VocabBuilder UI]([https://www.figma.com/file/I5vjNb0NsJOpQRnRpMloSY/Psychologists.Services?type=design&node-id=0-1&mode=design&t=4zfT2zFANRbp1fCK-0](https://www.figma.com/file/XRhVBdCX1wPyzCRA567kud/VocabBuilder?type=design&node-id=0-1&mode=design&t=Aa7GiCvVIpx6Nvi5-0))
 
 📄 Technical Specification (TЗ): [Google Docs]([https://docs.google.com/document/d/1PrTxBn6HQbb0Oz17g5_zvyLGIOZg0TIP3HPaEEp6ZLs/edit?tab=t.0](https://docs.google.com/spreadsheets/d/15zCxbWA7ubDmFzjmzzXe6ysiHVMd4iD2PcZ7ilN2gRc/edit?gid=1060862504#gid=1060862504))

## 👤 Author
**Name:** Yaroslav Terno  

📧 **Email:** yroslavterno@gmail.com 

🔗 **LinkedIn:** [Yaroslav Terno](https://www.linkedin.com/in/yaroslav-terno)  

