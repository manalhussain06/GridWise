# GridWise website + app

- `index.html` is the company website (all 7 required sections).
- `app/index.html` is the GridWise app. It opens at `/app` and the site's "Launch app" buttons link to it.
- `img/` holds the app screenshots and the architecture diagram.

## Edit the team details
Open `index.html` and search for `const TEAM`. For each member, change the name, ID, email, skills, responsibilities and vision. To add a photo, put it in `img/` (e.g. `img/ali.jpg`) and set `photo:"img/ali.jpg"`.

## Deploy on Vercel
1. Create a new GitHub repo and upload everything in this folder ("Add file → Upload files", drag the files and folders in, then Commit).
2. On vercel.com: **Add New → Project → Import** the repo, keep Framework **Other**, click **Deploy**.
3. The website is at `https://<project>.vercel.app` and the app is at `https://<project>.vercel.app/app`.

## App logins
| Role | Email | Password |
|---|---|---|
| Facility Manager | manager@gridwise.pk | demo123 |
| Customer | customer@alnoortextiles.pk | client123 |
| Admin | admin@gridwise.pk | admin123 |
