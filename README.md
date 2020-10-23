/*Problem Statement:

Project Takeaway Assignment
Minimum Requirements (Level 0)
In the following assignment, we are going to build an adaptive learning platform, leveraging gamification to engage users
There are two types of user roles in this application.
● Teachers
● Students
A teacher is supposed to add, remove, edit, delete courses. For each course, they will be able to create one quiz only, based on a set of questions and their respective answers (Choice based Questions only). Teachers should also be able to add/edit/delete questions and answers to a quiz for a course.
A quiz can contain multiple questions, and each question may have multiple correct answers. Teacher must set the points (positive integer with max value 10) for each question that the student must receive by answering the question correctly.
A teacher must also specify the passing points for the overall course quiz that a student must obtain. While taking a quiz if a student has achieved a passing score, they can choose to continue to earn more points or leave the quiz.
Based on the time availability, you may choose to add additional features as stated below to increase your chances of being shortlisted.
These features of application can be divided into levels:
1. Level 0 (Basic) :-
a. All features that are mentioned above as minimum requirements.
2. Level 1 (Beginner) :-
a. Recording points scored by the students in a particular course.
b. Student Profile which shows the history of course quizzes taken and total points earned for all courses quizzes and each course quiz separately.
c. Each answers need to have sub-answers (segmented by topics)
3. Level 2 (Intermediate) :-
a. There should be a time limit for completing every quiz, which teacher should mention while creating the quiz.
b. Each question will have multiple concepts tagged to it. For example - A question related to algorithms can have multiple concepts such as sorting, time and space complexity and so on.
4. Level 3 (Advanced) :-
a. Introduce another scoring metric called the experience point for a specific course, which would be based on the total number of correct questions answered in a course quiz by a student. Thus, there would now be two types of points in the application for the students, points earned using answering questions as mentioned in Level 0 and experience points (XP).
b. The points earned by answering the questions can be used to skip other questions. A question can only be skipped if the student has previously earned the minimum points needed for a concept that are tagged to the question. For every skipped question , the points that question holds will be deducted from the total points earned by the user across all quizzes.
c. Each course will have a leaderboard, which enlists students based on their experience points.
d. Students can spend points to chat with other students
e. Adaptive test based on question difficulty, i.e., the teacher would set the difficulty level for each question and then all students taking the test would be presented with questions in the following manner:
i. If a student is able to answer a question, then the next question will have difficulty level above or equal to the answered question
ii. If a student fails to answer a question, then the next question will have a difficulty level less than or equal to the answered question
Assignment Submission ● Deploy this application on any cloud provider Heroku, Zeit, Runkit, etc. Send us the link to test the application along with a Postman collection documenting all exposed endpoints. ● Git history is paramount important. Upload the source code on Github for us to review. Make sure you follow all the best practices while using git as you would do on any production application.
Focus on getting the entire flow working - edge cases are important. We are mainly trying to understand how you would architect it, the best practices you follow, and any foresight you display while making design decisions. So please keep a note of these as you proceed with this exercise.
For submission, send us an email at hr@navigus.in with subject line as LPU Campus Hiring 21 with the following details:
1) Link to Github / Bitbucket (ensure repository is public) or deployed app 2) Name 3) Registration Number
All the best!
*/

Approach:
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The backend is implemented using NodeJs, ExpressJs, MongoDB, and the front end is implemented using React. Have created to schema one for the user/ teacher and the other for courses. First a teacher have to create a user and for that particular user we can create a test with the added functionality of duration and date of creation.
The database is implemented using MongoDB. Postman is used to verify the codes.
