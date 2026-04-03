# Since I'm using this only for myself I did everything in the index.html.

##I started by creating the basic HTML structure:
- (.container)
- Countdown cards (KPSS & University)
- A study tracker section
- A calendar grid

##Layout
- CSS Grid → for responsive card layout
- Flexbox → for alignment and spacing
- Clamp() → for responsive typography

##The visual theme is based on a cosmic aesthetic

##Countdown System
- Convert dates into Date objects
- Normalize today's date (remove time)
- Calculate difference in milliseconds
- Convert to days
- Progress bars
- Dynamic percentage calculation based on start/end dates

##Study Tracking System
- getStudyData() → retrieves stored data
- saveStudyData() → saves data
- todayStr() → formats current date

##Streak Calculation
- Iterates backwards from today
- Stops when a "missed day" is found
- Counts consecutive true values

##Calendar Visualization

##Daily Interaction System
- "Did you study today?" prompt
- Two buttons: Yes / No

##State Synchronization
- renderCalendar()
- checkTodayStatus()
- updateCountdowns()

##Canvas Animation (Universe Background)
- Animated stars (twinkling effect)
- Nebula gradients
- Responsive canvas

##localStorage
- Stored locally in browser
- Survives page refresh
- Simple and efficient

##Technologies Used
- HTML5
- CSS3 (Grid, Flexbox, Variables, Glassmorphism)
- Vanilla JavaScript
- Canvas API
- localStorage API
