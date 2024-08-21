just gonna put my plans here :)

so i want to have the following in my app:
- names of students i teach
- subject i teach each student
- days and times i teach each student
- hourly rate of each student
- canvas login info of each student
- keep track of pay periods for each student
- keep track of attendance
- set up reminders for upcoming sessions or payment due dates
- customizable dashboard for upcoming sessions

implementation steps:
1. student management (names, subjects, contact info)
- core of the app where i'll store and manage essential info for students
- *need to set up `Students` model and create basic UI to add and edit student info
2. scheduling (days and times i teach each student)
- fundamental for tracking sessions and will tie into other features like attendance tracking and reminders
- *need to implement `Schedule` model and create basic UI to set up and view each student's schedule
3. attendance tracking
- can start tracking attendance which is important for student progress and billing
- *need to create `Attendance` model and integrate attendance tracking into schedule views
4. billing and hourly rate management
- with attendance tracking in place, i can calculate how much each student owes based on hourly rate and attendance
- *need to add `hourlyRate` field to `Students` and set up basic billing functionality
5. reminders
- will help ensure that students stay on track with sessions and payments
- *need to create `Reminders` model and integrate reminder creation and notif features
6. canvas login info
- essential but not urgent; can be added after core functionality is in place. security considerations could make this more complex tho
- *need to add fields for storing canvas login info and ensure they are encrypted; create secure UI for managing this
7. customizable dashboard
- will bring everything together and provide an overview to most important parts of app
- *will start with simple dashboard that displays upcoming sessions and reminders