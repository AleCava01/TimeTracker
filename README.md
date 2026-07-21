# TimeTracker
Lil vibecoded timetracker for studying. Thanks to Gemini / Claude Code.

## Features

- **⏱️ Three-state session timer**
Start a study session with separate tracking of study time, pause time, and total session duration.
- **☕ Pause/Resume studying**
Within an active session you can toggle between "studying" and "on break" without stopping the session: both times are tracked separately.
- **🏁 Session-end modal with score and notes**
When you end a session, a popup asks for the grade you think you'd get on the exam right now (0-30, optional) and free-form notes about the session (optional).
- **✏️ Manual timer editing**
You can manually correct both study time and pause time (hours/minutes/seconds), even mid-session: the session resumes exactly where it left off.
- **🔄 Timer reset**
A dedicated button to fully reset study, pause, and the current session.
- **📅 Exam countdown**
Shows today's date, total days left until the exam, and effective study days (net of planned days off).
- **🎯 Category-based goals**
Customizable categories (e.g. questions, essays, videos) with counters, editable targets, and a percentage progress bar.
- **🚦 "Ahead/on track/behind" status indicator** 
For each category, a colored badge shows whether you're ahead, on track, or behind the pace needed to hit your goal.
- **🏖️ Planned days off**
You can set how many rest days you have planned before the exam, recalculating your effective study days.
- **📊 Daily status save**
A button that saves/updates today's aggregate progress in the history log.
- **➕ Manual record entry**
From the History Log you can add a past session by hand (date, study/pause time, score, notes, category progress) via a dedicated popup.
- **📋 Session history log**
A table with every logged session: date, study, pause, total session, score, notes, and category progress, with inline edit (✏️) and delete (🗑️) for each row.
- **📥 CSV export**
Download the entire history as a CSV file, including all fields (times, score, notes, categories).
- **⚙️ Customizable settings**
A dedicated tab for setting the exam date, adding/removing goal categories, and editing their overall targets.
- **🗑️ Full app reset**
A button to wipe all saved data and restore the app to its initial state.
- **💾 Persistent local storage**
All data is automatically saved in the browser (localStorage), so everything is still there after you close and reopen the page.

## New features

- **Persistent Widget**
- **Tasklist**

## To add

- Consistent text formatting, sizes
- Different palettes in settings
- New name
- Widget changing background color when switching from break to studying
- Eliminate Save Today's Progress button (no more necessary)
- Possibility to automatically merge sessions of the same day.
- A session belongs to a day if it starts in that day, no matter if it ends after midnight
- Light / Dark mode switch on top right corner
- Climber Animation with as the number of days passes, and reaches the mountain?