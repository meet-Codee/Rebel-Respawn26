NEON SHADOW — DEPLOYMENT GUIDE (WINDOWS / NETLIFY)

This folder is READY TO PUBLISH. index.html contains its own JavaScript and CSS. There is NO npm build step.

1. Right-click NEON_SHADOW_NETLIFY_READY.zip -> Extract All.
2. Open the extracted folder and verify index.html is directly inside it.
3. Open https://app.netlify.com/drop in your browser.
4. Drag the EXTRACTED FOLDER (not the .zip file) into the drop zone.
5. Wait until Netlify reports Published. Click the generated .netlify.app link.

To UPDATE AN EXISTING NETLIFY SITE:
1. Netlify dashboard -> choose the existing site -> Deploys.
2. Locate the manual deploy drop zone, drag the extracted NEON_SHADOW_NETLIFY_READY folder.
3. Wait until Published, then refresh the existing site.

If using GitHub-based deployment: commit index.html, netlify.toml and _redirects to the repository ROOT. On Netlify use an empty Build command and '.' as Publish directory. DO NOT upload a ZIP as a repo file.

If the game opens to Not Found: confirm index.html is in the published root folder.
If blank screen: open browser Developer Tools (F12) -> Console, copy the first red error and send it for debugging.

To play locally without deployment, double-click index.html in the extracted folder.
