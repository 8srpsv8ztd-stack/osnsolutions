# Updated company website

This version identifies OSN Solutions Limited, its Cedar Hill, Texas location, small-business IT consulting work, and two app projects in development. App names and detailed features are intentionally not invented.

## Update your existing GitHub repository

Extract this ZIP, open your existing 8srpsv8ztd-stack.github.io repository, and choose Add file → Upload files. Upload ALL files inside the osn-solutions folder, replacing existing files and adding about.html and services.html. Do not upload the enclosing folder or the ZIP. Commit the changes to main.

Keep your existing Pages and DNS settings. Wait for the Pages deployment to finish, then open the live site and check all pages. Confirm the support mailbox receives mail. Test both osnsolutions.com and www.osnsolutions.com using another network before resubmitting enrollment.

This revision is not a guarantee of Apple approval. Use the exact legal organization name in your enrollment and corresponding organization records.

---

# OSN Solutions — GitHub Pages setup

1. Create a PUBLIC repository named `8srpsv8ztd-stack.github.io` under your GitHub account. If you created `osnsolutions.github.io`, rename it in Settings → General.
2. Extract the ZIP. Upload the CONTENTS of the osn-solutions folder (not the folder itself) using Add file → Upload files, then commit to main. index.html must be at the repository root. Include CNAME. The optional .nojekyll file may be hidden on your computer; these plain HTML files also work without it.
3. Go to Settings → Pages. Choose Deploy from a branch, main, /(root), then Save.
4. In Pages → Custom domain, enter osnsolutions.com and Save before changing DNS.
5. At your domain DNS provider, set these records:

| Type | Name | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | 8srpsv8ztd-stack.github.io |

Replace conflicting website records for @ and www. Keep email MX and verification TXT records. Remove stale/conflicting AAAA records or configure GitHub's documented IPv6 values. DNS may take up to 24 hours to update.
6. Once GitHub's DNS check and certificate finish, enable Enforce HTTPS in Settings → Pages.
7. Open https://osnsolutions.com and test every navigation link on a phone and computer.

## Before using this for app support

Support and privacy inquiries link to help@osnsolutions.com. Confirm that this mailbox receives email before publishing. GitHub Pages does not provide email hosting.

The privacy page covers this static website only. Create an accurate app-specific policy when each app's data practices are known. The website is not a guarantee of Apple Developer organization enrollment approval.

## Editing

Edit the HTML files directly in GitHub and commit. GitHub Pages republishes your changes automatically. No build system or paid service is required.

## Official instructions

https://docs.github.com/en/pages/quickstart
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
