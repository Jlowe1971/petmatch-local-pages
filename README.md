# PetMatch Local Public Pages

Use this folder for the public URLs Apple asks for in App Store Connect.

## What to Replace

Before publishing, replace this placeholder in `privacy.html` and `support.html`:

```text
YOUR-SUPPORT-EMAIL@example.com
```

Use an email address you can actually receive, such as a Gmail address created for the app.

## Free Publishing Option: GitHub Pages

1. Go to `https://github.com`.
2. Create a free account if you do not already have one.
3. Create a new public repository named `petmatch-local-pages`.
4. Upload the files from this `public_site` folder.
5. Open the repository's `Settings`.
6. Click `Pages`.
7. Under `Build and deployment`, choose `Deploy from a branch`.
8. Choose the `main` branch and `/root`, then save.
9. GitHub will give you a public website link.

Your App Store Connect URLs will look like this:

```text
Support URL: https://YOUR-GITHUB-USERNAME.github.io/petmatch-local-pages/support.html
Privacy Policy URL: https://YOUR-GITHUB-USERNAME.github.io/petmatch-local-pages/privacy.html
```

Replace `YOUR-GITHUB-USERNAME` with your actual GitHub username.
