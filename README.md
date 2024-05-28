# WebApp-GroupProject-
1.0 INTRODUCTION

The SPM Student Learning Platform is a web application designed to support SPM students in their studies by providing a comprehensive and interactive online learning environment. Utilising the Laravel MVC framework, the platform aims to offer a seamless user experience with features designed to meet the specific needs of SPM students.

With the rapid advancement of technology, traditional methods of learning are evolving, and online education is becoming increasingly popular. The SPM Student Learning Platform leverages this trend by providing a convenient and accessible platform for students to engage with their studies anytime, anywhere.

By integrating the Laravel MVC framework, the platform ensures scalability, security, and maintainability, allowing for seamless updates and enhancements over time. Through a user-friendly interface, students can navigate through various features effortlessly, making their learning journey intuitive and enjoyable.

The core features of the platform includes:
User Authentication
Chapter Management
Reflection Journals
Profile Viewing

The SPM Student Learning Platform aims to empower students with the tools and resources they need to succeed academically while fostering a culture of lifelong learning and self-improvement. By harnessing the power of technology, the platform strives to revolutionise the way SPM students engage with their studies, paving the way for a brighter future.




2.0 OBJECTIVES
The main objectives of the SPM Student Learning Platform are:

To provide an easy-to-use platform for SPM students to access study materials.
To allow students to add, edit, and delete their reflections on what they have learned.
To enable students to view and manage their profiles and track their achievements.
To offer a secure login/logout system for user authentication.


3.0 FEATURES AND FUNCTIONALITIES

User
	i) Registration
	Allow new user to create an account
Form to enter user details. For example, username, email and password
Validate email and password
Save user details to the database

	ii) Login
	Allow registered user to log in
Form to enter username and password
Validate the database entered
Redirect to the dashboard

	iii) Logout
Redirect to login page after logout

	iv) Reset Password
	Allow user to reset their password if forgotten
Form to confirm email address
Send password to user’s email
Form to set a new password


Chapter
i) Search 
Allow students to search for subjects and chapters
Search bar to input keywords

ii) Add Chapter
Form to enter chapter details. For example, title and content
Save chapter details to the database
Display new chapter in the chapter list

           iii) Edit Chapter
Allow user to edit existing chapter details
Form to edit the chapter details
Update chapter details on the database after submission

          iv) Delete Chapter
Pop-up box to confirm the deletion
Remove chapter from database

          v) View List of Chapter
Display list of chapters available for a subject
There are options to view, edit or delete


Reflection Journal
i) Add
Allow students to write their reflection on what they have learned 
Form to enter reflection details based on topic selection
Save reflection to the database
Display the new reflection in the list

ii) Edit
Allow students to edit the existing reflection details
Form to edit the reflection details
Update reflection details in the database

iii) Delete
Pop-up box to confirm the deletion
Remove reflection from the database

iv) View
Display list of reflection written for every topic
There are options to view, edit or delete

Profile 
i) View profile details
Fetch student’s details from the database
Display student’s details
There are options to edit or delete the information

ii)View achievements
Allow students to see their achievement based on how many they interact with the platform
Fetch achievements from the database
Display list of achievements 

iii) View Registered subjects
Fetch registered subject from the database
Display list of subject registered

