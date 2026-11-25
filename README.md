# Task Tracker — interactive demo

A live demo of a team task tracker I built: one HTML file, no server, no accounts.

**Try it:** `https://sebas56825.github.io/task-tracker-demo/`

## What you can try
- **Dashboard, Timeline, Calendar and Tasks** views, with sub-tasks, priorities, statuses and effort in hours.
- **Today**: a daily agenda with planned hours, overdue items and upcoming days off.
- **Weekly summary** per person or for the whole team, ready to copy.
- **Bulk edit** of several sub-tasks at once.
- **Holidays and absences** that show up in the calendar and the daily agenda.
- Spanish / English and light / dark themes.

## How it works
The real app talks to Google Sheets through Apps Script. This demo replaces that backend with a small
simulator inside the page, so nothing leaves your browser:

- All data is sample data, generated relative to today's date.
- Your changes are stored only in your own browser (`localStorage`) and reset every day.
  There is also a **Reset demo** button at the top.
- File attachments and team-name editing are turned off in the demo.

## Credits
Created by Sebastian Mayor & Aquile Sanchez.
