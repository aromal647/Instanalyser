Pending Request Cleaner

A small static website that generates a browser-console script for cancelling your pending (sent) Instagram follow requests in small batches.

Live site: https://yourusername.github.io/your-repo-name

How it works

This site does not connect to Instagram and never sees your login. Browsers do not allow one website to control another, so the page only builds a script for you. You copy it and run it yourself in the console of Instagram's own page, while logged in on your device.

Usage
Open the live site.
Set Requests per run and Min delay (seconds). The script updates as you type.
Click Copy script.
Log in to Instagram on a desktop browser and open your pending requests list (Settings, then Friends and followers, then Follow requests, then Sent).
Press F12 (or Ctrl+Shift+J) and open the Console tab.
If your browser blocks pasting, type allow pasting and press Enter.
Paste the script and press Enter. Progress is logged in the console.
Wait a few hours before running another batch.
Deploy your own copy
Create a new Public repository on GitHub. Name it yourusername.github.io for a main site, or any name for a project site.
Upload index.html and this README.md, then commit.
Go to Settings → Pages.
Under Build and deployment, set Source to Deploy from a branch, choose main and / (root), then save.
Visit your site after a minute or two.
