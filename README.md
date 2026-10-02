# 90 Days to Become an AI Engineer
Developed and updated by **Mahendra Singh** · Medium: https://medium.com/@mahendraa1188

One file: `index.html`. No server, no API key, no build step.

## Set your batches (teacher)
Open `index.html`, search for `TEACHER SETTINGS` and edit the list:

```js
const BATCHES=[
  {id:"oct-2026",name:"October 2026 batch",start:"2026-10-01"},
  {id:"nov-2026",name:"November 2026 batch",start:"2026-11-01"}
];
const JOIN_WINDOW_DAYS=14;   // how long after Day 1 students can still join
```

- Students can only join one of these batches, so nobody can type their own dates.
- Give each batch its own link: `https://your-site.vercel.app/#oct-2026`
  A student opening that link sees only that batch.

## Deploy
Upload this folder to Vercel, Netlify or GitHub Pages.

## How students use it
1. Enter name, join their batch. Weeks, ship dates, tables and the 92-day tracker all follow the batch calendar.
2. Progress is saved in their own browser. "Progress code" moves it to another device.
3. Ask AI tutor opens the question in the student's own Claude account (no API key needed).

Note: because there is no login, a student can still open the site in incognito and join a different
listed batch. A true one-time lock per student needs a login and a database (see suggestions).
