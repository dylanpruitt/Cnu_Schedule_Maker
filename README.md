# CNU Course Charter

### Tech Stack
HTML5/CSS/JavaScript

### Purpose
When I was in college at Christopher Newport University, it was difficult to visualize course schedules when planning for registration. After talking with another student who was creating an app for students to see their exam schedules, I realized that there was a lot of potential for a similar app, but to help people plan for their classes. Some students used Excel/Google Sheets, but it was time consuming to set up, and still had the same problem of being difficult to visualize schedules. I wanted to create a program using knowledge from personal projects and computer science courses to help solve these issues.

I modeled the UI for the schedule planner after Google Calendar - students frequently used Google Calendar, and the CNU website displays class schedules in the same format, so it would be familiar to students. I also wanted the program to be web-based, to make it as easy as possible for students to access (no download required). The program on Github now is a quick prototype to see if the planner idea would work - the UI was made to be barebones, so I could focus on just getting the functionality done.

![Schedule planner demo](https://github.com/dylanpruitt/Cnu_Schedule_Maker/assets/8081069/81780a0e-2d7c-4844-8635-c78cfa564fe1)

### Testing and Feedback
My partner and I planned to eventually show the prototype to faculty at CNU, in the hopes that this could become an official university project. Before showing the program to faculty, I wanted to see feedback from potential users, to address issues with the program first. With the help of the Honors and Leadership programs, a demo of the schedule planner was advertised in weekly bulletin emails, and over 20 students responded with feedback on the program.

In general, there was a positive response to the program - many students liked the Google Calendar format; however, one student mentioned that a similar program already existed called Coursicle, and it already had CNU’s schedule integrated into the app, so students could make schedules without going through the extra step of uploading a .CSV file.

![Coursicle Screenshot](https://github.com/dylanpruitt/Cnu_Schedule_Maker/assets/8081069/c3029a0c-54a1-42f7-9b83-cc19fa462823)

Unfortunately, we were never able to show the schedule planner to the computer science faculty at CNU because of time constraints and COVID. However, even though we were unaware of Coursicle, I still think that this was a solid project in its own right. Aside from the one respondent who mentioned it, no one else at CNU knew about Coursicle, and having the program made for CNU students by CNU students makes it easier to modify for the university’s needs than Coursicle. Additionally, I think some of the weaknesses of the program can allow other students an opportunity to learn/get experience working on projects. CNU doesn’t have a computer science fully dedicated to web development, so a program like this could help introduce students to web development. I have some ideas for improvements below:

### Future Ideas
The most glaring weakness of this program is the requirement for a user to upload a .CSV schedule of classes, which is awkward and complicates the process of planning a schedule.
- *Solution*: use Selenium to scrape the schedule of classes, keeping the program up to date without needing the user to find a schedule of classes

I also didn’t have as much experience with front-end development when creating this project; although a visual overhaul could certainly help the project.
- *Solution*: use better HTML design (e.g. using grid and flexbox for the calendar view instead of hardcoding position, more padding)
Responsive design also could be very useful to implement, and a great learning experience for students.


