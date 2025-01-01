java c
COSC2446 Web Programming
Practical Assessment 1 (worth 15%)
The due date is the 23rd   of August 2024 COB (5:30 pm)
Overview
Create a website for a fictitious pet adoption agency – Pets Victoria that will display pets available for adoption.
The assignment is an individual task that will require an individual submission.
Please ensure that you submit your assignment to the Canvas (Assignments, Assessment 1) AND   to the Jupiter web server by the due date.
Assessments submitted after the due date will be accepted as follows:·   Assessments submitted between 0-24 hours after the due date: 20% penalty·   Assessments submitted between 24-48 hours after the due date: 50% penalty·   Assessments submitted more than 48 hours after the due date will not be acceptedExtensionsIf you will not be able to meet the due date for an assessment you may apply to your teacher for an extension of up to seven days by completing the Application of Time to Submit Assessment Work Form   at https://www.rmit.edu.au/content/dam/rmit/documents/Students/Student_forms/Application-for-extension-of-time-to-submit-work.pdf      Applications for an extension of time must be received at least one working day before the due date for an assessment.Special ConsiderationIf unforeseen circumstances beyond your control prevent you from submitting your work on time you may be eligible to apply for special consideration. For further information regarding special consideration, please refer to the RMIT Special Consideration page at https://www.rmit.edu.au/students/student-essentials/assessment-and-results/special-consideration   
AI   TOOLS AND THEIR USE ARE NOT RESTRICTED FOR THIS ASSESSMENT TASK   
In this assessment task, you can use   AI   tools to assist you. All use of   AI   tools and their outputs should be appropriately acknowledged and referenced.
Create a website for a fictitious pet adoption agency – Pets Victoria according to the following basic requirements:1.   All code should reside in a “wp” GitHub repository that is under your RMIT student email account. Initially, you should clone this repository from https://github.com/tanyarmit/wp.git. You should add your respective teacher as a collaborator. The code should be placed in the “a1” directory. Your Git history should reflect your work process to authenticate your contributions.2.   All pages should use semantic HTML 5 elements like header, nav, main and footer (as discussed in week 2) and well-structured content according to the following instructions.3.   Include the logo (logo.jpeg) in the navigation bar and link it to the home page (index.html). The navigation bar should have a search form, but the search functionality is not required.4.   The main image (main.jpg) should be included as an image element in the main section of the page (home page only). The image should float right and should be displayed as a circle. Use CSS for that.5.   All pages should have the same navigation (a nav element) containing a dropdown menu for all four pages (with options appearing as Home, Pets, Add more, and Gallery).6.   All pages should have a footer with a copyright that has your name.7.   There should be one   common CSS file for all the pages (for common nav and footer styles). You must create a CSS stylesheet that all pages are linked to (in the  element).8.   Use a float for layout rather than absolute positioning.9.   The content of the page is 1200px wide and centred. Use margins on the body element to achieve this.10.   Use Google fonts for the site. “Ysabeau SC” as a default, “Poetsen One” for all headings except for 
 on the home page – “Permanent Marker”, and material icons for icons.You can have a look at the examples https://fonts.google.com/specimen/Permanent+Marker, https://fonts.google.com/specimen/Ysabeau+SC, https://fonts.google.com/icons, https://fonts.google.com/specimen/Poetsen+One11.   There should be one   common JS file for all pages (for the dropdown menu). This dropdown menu uses a JavaScript. onchange event handler to implement navigation. You will need to write a relevant JavaScript. function in a separate JavaScript. file, linked to from all web pages. You should link the JS file in the  or at the end of the  to ensure best practices.12.   Each html page should be validated against W3C standards at https://validator.w3.org/. You should validate all your HTML files and the CSS file. Correct 代 写COSC2446 Web ProgrammingJava
代做程序编程语言and re-test issues. Fix any errors or warnings.13.   Please use the techniques taught in this course so far; do not use Bootstrap or other frameworks for any functionality.14.   In the a1 directory, the README.md file should contain the link to your Jupiter site.Create the following 4 Web Pages according to the instructions given for this website
1. index.html
   As given in the below picture. Check the images provided on Canvas. Add your name in the copyright footer (The name should be the same as your Canvas name).   
2. pets.html
Create a table to describe pets with some information like name, type, age, and location.   
3. add.html
Create a Add new form. using ( tag) to submit new pets:   
Check the following link to learn more about   the   form   element.
https://www.w3schools.com/html/html_forms.asp
4. gallery.html 
Create a picture gallery presenting pictures of the pets.
You can use the images provided, or you can search for images on the following sites:
https://pxhere.com/   or https://pixabay.com/
Alternatively, you can use other Adobe Stock images. If you use the images provided or find other Adobe Stock images, place a copyright notice in your code    - “All images used are from   Adobe Stock   and used under   RMIT Education License”. This can be done as a comment on every page.Colours Used·   #36454F (text)·   #E57F3D (h1, footer background, on hover, etc.)·   #008080 (nav background, h2, th, footer text, etc.)·   #fcf9ec (home page main background)Instructions for hosting your website on the Jupiter web server
Make sure that you follow the naming convention for files and directories. Failure to do so will result in lost marks.
Files required:1.   index.html2.   pets.html       3.   add.html       4.   gallery.html       5.   style.css (in css   folder)6.   main.js (in js   folder)7.   Provided image files for the logo and the main page and images that you are including in the gallery page in the images   folder8.   README.md with the link to your Jupiter deployment
For instructions on uploading and testing files on the Jupiter web server please refer to the document “Developing and deploying with Git”.
Failure to submit the link might lead to the failure of the assessment.Instructions for submission of your website on Canvas
   Please submit the zipped-up wp/a1   directory that should contain the following files:1.   index.html2.   pets.html       3.   add.html       4.   gallery.html       5.   style.css (in css   folder)6.   main.js (in js   folder)7.   Provided image files for the logo and the main page and images that you are including in the gallery page in the images   folder8.   README.md with the link to your Jupiter deployment9.   Test.docx with screenshots of the validated html pages and the css file
Rename your zipped-up folder with your lastname_firstname_studentID   and upload the zip file to Canvas. The assessment task will have a file upload section. Please do not upload individual files – zip up your work and upload that.
Make sure that you follow the naming convention for files and directories. Failure to do so will result in lost marks.
Marking Guide for Web Programming Assessment 1
Assessment worth 15% Mark
Element to be marked
Total marks
Complete zipped up folder according to the instructions
1
Home page (index.html) according to the given instructions and html is validated.
3
The About page (pets.html) is according to the given instructions. The page has valid html.
3
The Add More page (add.html) is according to the given instructions. The page has valid html.
3
The Gallery page (gallery.html) is according to the given instructions. The page has valid html.
3
One separate css file with all the required styles. No inline css used
2
Float used for layout
1
Google fonts are correctly used for the site
2
One separate js file with the dropdown functionality. Dropdown menu works
2.5
All pages have valid html. Screenshots of the validated html page are submitted in a Test.docx document
4
Site has valid css. Screenshots of the validated css file are submitted in a Test.docx document
0.5
Site deployed to Jupiter
10
Code is in Git and has project history
10
Total marks
45
Note: The teacher may ask any student for a demonstration to validate their work

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
