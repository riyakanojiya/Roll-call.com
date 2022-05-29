Tracking attendance using face recognition
This is a website which uses face recognition to mark attendance.

Microsoft Engage 2022 Challenge


About the Project
Engage 2022 is a Engagement and Mentorship program created by Microsoft engineers, in association with Ace Hacker team, for engineering students.Through this initiative, students get a chance to be mentored by Microsoft and be a part of AMA Sessions, Webinars and Leader talks delivered by Microsoft employees. This year there were 3 challenges . The challenge chosen by me was to build a website that uses face recognition and tracks attendance.

Development Methodology :
Scrum Methodology
Scrum is an Agile development methodology used in the development of software based on an iterative and incremental processes. Each iteration consists of two to four week sprints, where each sprint’s goal is to build the most important features first and come out with a potentially deliverable product.

Sprint Map
Below points provides insight to sprint wise progress:

Week 1 :
Learn more about Backend in Web-development.
Decide tech stack and architecture.
Learn Django for server-side rendering.
Learn about Git and GitHub.

Week 2 :
Work on the User Interface.
Complete Sign-in and Sign-up and main page of website.
Learn more about Django for server-side rendering.
Research about other features.
Tried to implement a student-teacher model for the website.

Week 3 :

Improve the User Interface.
Kept on trying to implement the student-teacher model
Came across many bugs while implementing ,so then due to approaching deadline started implementing basic functionality first.




Week 4 :
Add basic functionality i.e. attendance tracking via face recognition.
Update README.
Create demo video.

Built With
React.js
Django


Firstly, all users registers with the server. Once users have registered, they can login  to the attendance page where they can check as well as mark their attendance. The users can also view all the registered users.

Getting Started
Pre-requisites
Basic setup of React JS
Basic setup of Django

Installation
Clone the repo
git clone
for frontend-
simply right click on the  my-app   folder and open gitbash here then run the following commands
 npm i
 npm start

for backend -
simply go to the  backengage  folder and open terminal then
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
//username- riyakanojiya (super user credentials)
//password-123


Dependencies
Django
cors
babel
webpack
bootstrap
face-api.js
react-router
npm
node




Features
-Sign-in and sign-up authentication.
-Users can mark attendance through face recognition.
-Users can check attendance in the table.
-Once registered all the users will be shown in the all users page of the website.

Possible Improvements
Backend functionality to the some frontend pages.
Student-Teacher model can be implemented.
Profile photo can be uploaded during registration and saved to database, this database could then be used to recognize and mark attendance instead of fetching images.
-dark mode in the dashboard


Contact
Email : riya.kanojiya.ece20@itbhu.ac.in
