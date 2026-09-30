# Pharmacology test plan (installable checklist)

Plain files, no build step: index.html, manifest.webmanifest, sw.js, icon-180.png, icon-192.png, icon-512.png.

## Host it (pick one)
- GitHub Pages: create a public repo, upload all these files to the root, then Settings > Pages > Deploy from a branch > main / (root). Your link will be https://YOUR-USERNAME.github.io/REPO-NAME/
- Netlify Drop: unzip, then drag the folder onto app.netlify.com/drop.

## Put it on your phone
Open the link on your phone (online, once), then:
- Android (Chrome): menu > Install app / Add to Home screen
- iPhone (Safari): Share > Add to Home Screen

After that it opens like an app and works offline. Ticks are saved on that phone only.

## Updating
Replace the files in your repo or drop the folder again. The app picks up the change the next time you open it with internet.
