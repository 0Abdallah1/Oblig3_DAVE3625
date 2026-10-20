# Oblig3_DAVE3625

# Studyline

Study planner for students: track deadlines, count down to exams and log study time.

**Live demo:** https://0abdallah1.github.io/Oblig3_DAVE3625/

**Purpose:** Students juggle exams, assignments and study time across many courses. Studyline puts all of it in one simple page, so it is always clear what is due next and how much time has gone into each course.

## Features

- **Exam countdown:** a large banner shows the days left to your next exam.
- **Deadlines:** add exams, assignments and other items with a course and date. The list sorts by date, shows "Tomorrow" or "3 days overdue", lets you tick items done or delete them, and has filter tabs.
- **Study timer:** pick 25, 45 or 60 minutes for a course and use Start, Pause, Finish and log, or Reset. It beeps when time is up.
- **Weekly study log:** totals your minutes per course this week with small bars.
- **Saving:** everything is stored in your browser's localStorage. A "Load example data" button fills the app with demo content.

## Testing
I opened the app in the browser and tried these cases:

- [ ] ✏️ Add an exam and check the countdown banner updates
- [ ] ✏️ Add a deadline with a date in the past (it should show "overdue")
- [ ] ✏️ Try submitting with an empty field (the form should not submit)
- [ ] ✏️ Tick a deadline as done, then delete one
- [ ] ✏️ Run the timer, press "Finish and log" and check the weekly log
- [ ] ✏️ Refresh the page and check that the data is still there
- [ ] ✏️ Open the live demo on my phone and check the layout

## Limitations / future ideas

- Data is saved in the browser only, so it does not sync between devices.
- Ideas: editing existing deadlines, custom timer length, a calendar view, and weekly plan suggestions based on upcoming deadlines.

<img width="1467" height="884" alt="image" src="https://github.com/user-attachments/assets/26bbefdb-7601-4177-8950-a806e84532d4" />
