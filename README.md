# Team Nihhhhhh

UX & UI Assignment

## Website and App design

### Team Proposal 

Team will Develop/Revamp the EIT App and Website with additional features (to the current design) that will bring a more pleasant UX interaction to amthat are currently enrolled at EIT. The new design will consist of students from all campuses based around New Zealand with a more vast and simplistic approach to the current EIT App and Website improving the layout design and enhancing the current features with additional features for the EIT App and Website for students. 

### List of improvements and additional features (Website/App)

1. **Login/ Register**

- **Register** - First Name, Last Name, Phone Number etc
- **Login** - Login with User Name, Email or Phone Number then enter Password  

2. **Campus Select feature where any student enrolled with EIT from around the country can Login and have features (Once Logged in) such as:**

- **Campus Select** - Select what campus you're attending e.g Auckland, Taradale Gisborne etc.

3. **Once inside your selected Campus**

- **Select Subject and level** - Select subject you are going to take e.g Computers, Nursing, Fashion etc. then the level of that subject e.g Level 1, Bachelors, Diploma etc.

**Note: The above process is only for first timers logging in or registering**

4. **Home Page- once you’ve completed the above it will take you to the Home Page. Home Page features would include:**

- **My Courses** - My Courses will show you the course information, the course you are doing, the subjects you are taking in that course and the tutors running the course
- **My Timetable** - Timetable showing your class times, due dates, location of classes and lecturer
- **My Grades** - Previous course grades done in the past and current course grades
- **My Campus Map** - Campus map that will show you where your classes are located
- **My Campus Events** - Campus Events displaying upcoming course events, event dates and event times.
- **My Calendar** - Adding Campus events, assessment due dates, course goals, and notes.

### Functional vs Non-Functional 

Before we begin with exemplars about functional and non-functional requirements, we must understand the concept of those terms.  

Functional - In simple words, It describes what the system should do.

Non-Functional - Where Functional requirements explain what the system should do, Non-Functional requirements describe how the system should operate. 

For example, a music speaker should play sound. How? Through sound waves of n length and decibels of x frequency, allowing us to fluctuate low or high frequency of sound.

Relating this to the EIT website and App, we will have two Functional requirements for Website and App, respectively. Summing up of four functional requirements.

### Functional

1. **Login (App)** - The App Login menu must be able to Register or Login via Username, Email or Phone number and Password. This will be connected to the EIT login database.

2. **My Timetable (App)** - Timetable showing your class times, due dates, location of classes and lecturer on campus.

3. **Campus Map (App)** -  Campus map will provide details of class location and if you have classes present that day, classes will be active with colour code.

4. **Overall Grade System (App)** - OGS will show grades from all programs and courses and will also show your current percentage of the year.

5. **My Campus Map (Website)** - Campus map that will show the user (student) where your classes are located. 

6. **My Courses (Website)** - will show you the course information, the course you are doing, the subjects you are taking in that course and the tutors running the course. (Revamp!)

7. **My timetable (Website)** -  My timetable will show classes, times and locations on campus.

8. **My Grade System (Website)** - MGS will show grades overall with one click.

### Non-Functional

1. **Login (App)** - This non-functional requirement will provide user interaction via text input boxes for username/email and password. Login/Register displays success or an error message within 3 seconds or less of confirmation. This will synchronize with the MyEIT website so when Login credentials and other necessities are updated, the app will be updated.

2. **My Timetable (App)** - Timetable will synchronize with MyEIT website everys 10 minute refresh rate.

3. **Campus Map (App)** - Campus Map will synchronize with MyEIT database and refresh every 10 seconds or done so by the user and will update the map in real-time.

4. **Overall Grade System (App)** - OGS will show current grades from real-time and synchronize with MyEIT server.

5. **My Campus Map (Website)** - Campus map will show the user (student) where your classes are with a refresh rate of 60 seconds.

6. **My Courses (Website)** - My Courses will have a Loading rate of 10 seconds after interaction

7. **My Timetable (Website)** - The user will interact with the timetable button and this will display the timetable of the current user (Student) within a few seconds.

8. **My Grade System (Website)** - MGS will syncrhonize with the EIT database and provide current grades to students. This will then provide DATA to the EIT App when in synchronization mode. 

## Evaluation - Cognitive Walkthrough vs Heuristics

### Website Example - 

#### Auckland Uni Login - Displays user input credentials

<img src = "Images/login.png" Width = "1080">

*User searches URL then inputs student credentials and signs in. The process is a simple, easy and quick approach. The design is yet appealing and useable at that. Placing the login right in the centre allows the user to just focus on that part of the UI, instead of multi-tasking. This provides a user-friendly enviroment as it is a quick and simple processs.*

User logs in with username or Email address followed by password input and sign in button function once username and password has been entered. user could also login with other exisiting accounts such as facebook, Google, Linkedin, and Realme accounts. login menu also has hyperlinks for the website related to Auckland uni through sources such as:

- **facebook**
- **Instagram**
- **YouTube**
- **Linkedin**
- **Twitter**
- **And many more**

#### Auckland Uni Dashboard - Shows current classes, due dates and able to see class grades through one click.

<img src = "Images/Dashboard.png" Width = "1080">

*Once the user has signed in, they are allocated to the dashboard which again is an easy, yet simple process. The dashboard is consistant with managing your frequent, must do and Up-to-Date classes. If a class was opened a few days ago it will show on the users most frequent class activation and also "must do" classes will be notified on the side of the dashboard with color code. This simple design allows the user to see which class is more important to focus on through colour code and frequeny rates.*

Once login is successful user will be directed to the Dashboard home menu. Dashboard home menu would include menu features such as: 
- **Account** 
- **Dashboard**
- **Courses**
- **Calendar** 
- **Inbox** 
- **Help menu** 

#### Auckland Uni Calendar - Shows timetable, classes, class time, due dates, campus events, location.

<img src = "Images/Calendar.png" Width = "1080">

*The user has many options to chose from, but this image shows the calendar interaction which is just clicking on the calendar icon and the calendar appears with all the associated events to the individual and also Campus events. That can be classes, class times, class locations etc... Classes on the UI will be displayed with colour code, that shows wich class is currently on going or on that day. User is able to access the next day, week, month events or class times/dates when they want given that the website allows it. In terms of user control and interation this is by far the most accessible. Also if the user is linked up via email, they will be notified immediately when events are updated, changes, removed or coming up.*

**Calendar**
User can access Calendar in the calendar menu displaying classes, class location and class times. calendar can be customized suitable for students classes in real time displaying current classes and upcoming classes via daily, wekkly or monthly.

### App Example - Cognitive Walkthrough

#### Auckland Uni Files - Deisplays the users current files on the online database

<img src = "App Images/login1.jpg"><img src = "App Images/login2.jpg"><img src = "App Images/login.3.jpg">

*The login process is quite complex and particularily annoying.*

#### Auckland Uni Calander - Displays the users calender related social events

<img src = "App Images/Calendar.jpg" Width = "270">


#### Auckland Uni Edit dashboard - User is give permission rights to edit or delete classes

<img src = "App Images/dashboard3.jpg" width = "270"><img src = "App Images/dashboard2.jpg" width = "270"><img src = "App Images/EditDashboard.jpg" Width = "270">







