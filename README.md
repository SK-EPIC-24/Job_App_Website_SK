# Job_App_Website_SK website:

💼 Job Application Form (Developer Role)
This project is a responsive Job Application Form built with HTML5 and CSS3. It provides a clean, professional UI for candidates to submit their application for various developer roles. The form includes input validation structure, file upload, and date selection, styled over a sleek background.

🛠️ Technologies Used
HTML5 – For semantic structure and form controls.

CSS3 – For layout, styling, responsiveness, and interactivity.

Media Queries – To support smaller screen devices (mobile-friendly design).

📋 Key Features
📄 Form Inputs:

First Name, Last Name, Email

Dropdown for selecting Job Role

Address (multiline textarea)

City, Pincode, Date

CV Upload (file input)

🎨 Stylish UI:

Background image to enhance aesthetic appeal

Semi-transparent form container with subtle box shadow

Responsive grid layout for neatly aligned inputs

🧠 Form UX Enhancements:

Highlight input focus with red border

Hover effects on button for interactive feedback

Placeholder texts guide the user during input

📂 Folder/File Structure

pgsql

Copy

Edit

project-folder/

│

├── index.html

├── style.css

└── image/

  └── DESK.jpg   <-- Background image for form

🧱 Breakdown of HTML Structure
.container: Wraps the whole form content.

.apply_box: Contains the form elements styled with padding, shadows, and border radius.

<form>: Includes multiple input fields, select dropdown, and file upload.

.form_container: Uses a CSS grid to arrange input fields side-by-side (responsive).

.textarea_control: Spans full width for address field.

.button_container: Contains the "Apply Now" button styled for hover effects.

🎨 CSS Highlights
Uses box-shadow, border-radius, and rgba() background for soft UI feel.

input:focus outlines in red to help identify the active field.

Responsive design using @media queries to adjust layout on smaller screens.

Custom button styling with transition effects for hover interaction.

📱 Responsive Behavior
For devices with screen width below 460px:

Address field layout changes to better fit the screen

Grid columns adjust automatically

🧪 How to Use
Clone/download the repository.

Place your DESK.jpg background image inside the image/ folder.

Open index.html in your browser to view the form.

Modify and expand form functionality as needed (e.g., add validation or backend integration).
