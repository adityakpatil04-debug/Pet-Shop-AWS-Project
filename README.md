🐾 PetShop – Static Website Hosted on AWS S3

A simple and responsive Pet Shop static website built using HTML, CSS, and JavaScript, and hosted using AWS S3 Static Website Hosting. This project demonstrates cloud hosting fundamentals and modern front-end development.

🚀 Features

Fully static website (HTML/CSS/JS)

Mobile-responsive UI

Clean layout for showcasing pet products/services

Hosted on AWS S3 Website Hosting

Public URL accessible globally

Version-controlled using GitHub

🏗️ Architecture Overview
Local Code → GitHub Repository → AWS S3 Bucket (Static Hosting) → Public Website URL

☁️ AWS S3 Hosting Setup (Summary)

Created an S3 bucket with public access enabled for website hosting.

Uploaded all project files (index.html, style.css, images, scripts).

Enabled Static Website Hosting in S3 properties.

Set index document → index.html.

Applied bucket policy to allow public read access.

Verified website URL provided by S3.

📂 Project Structure
petshop/
│── index.html
│── style.css
│── script.js
│── images/
│── README.md

🔗 Live Demo (AWS S3 URL)
https://s3.ap-south-1.amazonaws.com/pet-shop.bucket/index.html
<img width="1920" height="1020" alt="Screenshot 2025-11-06 211535" src="https://github.com/user-attachments/assets/75b777e3-aa4c-44a6-9705-bf1a7672c5d7" />

(Replace with actual link)

🛠️ Technologies Used

HTML5

CSS3

JavaScript

Amazon S3 (Static Website Hosting)

Git & GitHub

📦 How to Run Locally
# Clone the project
git clone https://github.com/your-username/petshop.git

# Navigate into folder
cd petshop

# Open the website
open index.html

🌟 Future Improvements

Add a products page

Add backend API for pets listing

Add contact form with AWS SES

Add animations & better UI

👤 Author

Aditya Patil
Cloud & Web Development Enthusiast
