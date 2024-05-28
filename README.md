# SPM Student Learning Platform

## 1.0 Introduction

The SPM Student Learning Platform is a web application designed to support SPM students in their studies by providing a comprehensive and interactive online learning environment. Utilizing the Laravel MVC framework, the platform aims to offer a seamless user experience with features designed to meet the specific needs of SPM students.

With the rapid advancement of technology, traditional methods of learning are evolving, and online education is becoming increasingly popular. The SPM Student Learning Platform leverages this trend by providing a convenient and accessible platform for students to engage with their studies anytime, anywhere.

By integrating the Laravel MVC framework, the platform ensures scalability, security, and maintainability, allowing for seamless updates and enhancements over time. Through a user-friendly interface, students can navigate through various features effortlessly, making their learning journey intuitive and enjoyable.

The core features of the platform include:
- User Authentication
- Chapter Management
- Reflection Journals
- Profile Viewing

The SPM Student Learning Platform aims to empower students with the tools and resources they need to succeed academically while fostering a culture of lifelong learning and self-improvement. By harnessing the power of technology, the platform strives to revolutionize the way SPM students engage with their studies, paving the way for a brighter future.

## 2.0 Objectives

The main objectives of the SPM Student Learning Platform are:
1. To provide an easy-to-use platform for SPM students to access study materials.
2. To allow students to add, edit, and delete their reflections on what they have learned.
3. To enable students to view and manage their profiles and track their achievements.
4. To offer a secure login/logout system for user authentication.

## 3.0 Features and Functionalities

### User

#### i) Registration
- Allow new user to create an account
- Form to enter user details (username, email, password)
- Validate email and password
- Save user details to the database

#### ii) Login
- Allow registered user to log in
- Form to enter username and password
- Validate against database entries
- Redirect to the dashboard

#### iii) Logout
- Redirect to login page after logout

#### iv) Reset Password
- Allow user to reset their password if forgotten
- Form to confirm email address
- Send password reset link to user’s email
- Form to set a new password

### Chapter

#### i) Search
- Allow students to search for subjects and chapters
- Search bar to input keywords

#### ii) Add Chapter
- Form to enter chapter details (title, content)
- Save chapter details to the database
- Display new chapter in the chapter list

#### iii) Edit Chapter
- Allow user to edit existing chapter details
- Form to edit chapter details
- Update chapter details in the database after submission

#### iv) Delete Chapter
- Pop-up box to confirm deletion
- Remove chapter from database

#### v) View List of Chapters
- Display list of chapters available for a subject
- Options to view, edit, or delete

### Reflection Journal

#### i) Add
- Allow students to write their reflection on what they have learned
- Form to enter reflection details based on topic selection
- Save reflection to the database
- Display the new reflection in the list

#### ii) Edit
- Allow students to edit existing reflection details
- Form to edit reflection details
- Update reflection details in the database

#### iii) Delete
- Pop-up box to confirm deletion
- Remove reflection from the database

#### iv) View
- Display list of reflections written for every topic
- Options to view, edit, or delete

### Profile

#### i) View Profile Details
- Fetch student’s details from the database
- Display student’s details
- Options to edit or delete information

#### ii) View Achievements
- Allow students to see their achievements based on interactions with the platform
- Fetch achievements from the database
- Display list of achievements 

#### iii) View Registered Subjects
- Fetch registered subjects from the database
- Display list of registered subjects


## 4.0 ER Diagram

## 5.0 Sequence Diagram


## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## Acknowledgments

- Thanks to the Laravel framework community for providing extensive documentation and support.
- Special thanks to all the educators and students who provided valuable feedback during the development of this platform.

