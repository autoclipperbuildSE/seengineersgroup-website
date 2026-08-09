AUTO CLIPPER WEBSITE — COMPLETE GITHUB PACKAGE
================================================

This ZIP contains the complete website. It is designed so you can delete the
old website files from the website repository and replace them with these files.

IMPORTANT
---------
Upload the CONTENTS of this folder to the repository root. Do not upload the
outer folder as an additional subfolder.

The repository root must contain:
- index.html
- privacy.html
- terms.html
- contact.html
- styles.css
- script.js
- vercel.json
- CNAME
- assets/  (complete folder)

Git commands after copying the files:

  git add -A
  git commit -m "Replace website with complete Auto Clipper branding update"
  git push origin main

Then wait for the Vercel/GitHub deployment and open:
- https://www.seengineersgroup.com/
- https://www.seengineersgroup.com/privacy
- https://www.seengineersgroup.com/terms
- https://www.seengineersgroup.com/contact

Use Ctrl+F5 or an incognito window to bypass the old browser cache.

Do not delete the GitHub repository itself. Only replace its website content.
