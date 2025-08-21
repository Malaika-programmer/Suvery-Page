AK Institute Website Requirements Survey
This repository contains the front-end code for the AK Institute Website Requirements Survey. This is a static web page designed to collect business and technical requirements from clients to inform the development of a new website. The form submissions are handled by Netlify's built-in form-handling feature.

📋 Features
Comprehensive Survey: A detailed questionnaire covering general, front-end, back-end, and security requirements.

Netlify Forms Integration: The form uses Netlify's native form-handling capabilities, so no server-side code or backend is required.

Spam Protection: Includes a hidden "honeypot" field to automatically filter out spam submissions.

User-Friendly Design: A clean, responsive design using a simple HTML and CSS structure.

Submission Confirmation: A JavaScript-powered pop-up confirms successful form submissions and resets the form for a better user experience.

Client-Side Validation: The form uses the required attribute to ensure that key fields are completed before submission.

🚀 How to Use
To use this survey page, you can either clone this repository or download the index.html file directly.

Clone the repository:

Bash

git clone https://github.com/your-username/your-repo-name.git
Open the file:
Open the index.html file in your web browser to view the survey form.

🌐 Deployment
This project is built to be deployed on Netlify for seamless form handling.

Create a Netlify Account: If you don't have one, sign up at https://www.netlify.com/.

Deploy your project:

Option A (Recommended): Connect your GitHub repository to Netlify. Netlify will automatically detect the HTML form and deploy your site. Any future changes you push to GitHub will automatically trigger a new deployment.

Option B (Manual): Drag and drop your project folder (or the index.html file) onto the Netlify dashboard.

View Submissions: After the first submission on your live site, go to your Netlify dashboard, select your site, and navigate to the Forms tab. You will see all submissions listed there.

Set up Email Notifications: To receive email alerts for new submissions, go to your site's Forms tab in the Netlify dashboard, and set up an email notification in the "Form submission notifications" section.
