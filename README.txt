Talent Hunters LK — Job board (static files)
Files included:
- index.html      -> Public job board (reads jobs from browser localStorage)
- admin.html      -> Admin interface (username: Admin9, password: J@n258)
- styles.css      -> Styles for the site
How it works:
- This is a simple static implementation (no server).
- Jobs are stored in the browser's localStorage (key 'th_jobs') so they persist in the admin user's browser.
- Admin page requires the credentials above; once signed in, you can add, edit, delete, export and import jobs (JSON).
- Apply button uses a mailto: link to talenthunters.lk@gmail.com — candidates must attach their resume in their mail client.
Notes & suggestions:
- For production, host these files on GitHub Pages or any static host. To make admin secure and shared across users, add a server-side backend (Node/Python) + database.