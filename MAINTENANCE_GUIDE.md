# Portfolio Maintenance Guide

Congratulations on deploying your portfolio! Here is how to keep it updated.

## Updating Your Website

Whenever you make changes to your files (HTML, CSS, JS, or images), follow these steps to update your live site:

1.  **Save your changes** in your editor.
2.  **Open your terminal** (User `Control + ~` in VS Code).
3.  **Run the following commands:**

```bash
# 1. Stage your changes
git add .

# 2. Commit your changes with a message describing what you did
git commit -m "Update project section" 
# (You can change "Update project section" to whatever you want)

# 3. Push to GitHub
git push
```

## What happens next?
- GitHub will receive your new code.
- GitHub Pages will automatically detect the push and start rebuilding your site.
- In **1-2 minutes**, your live link will update with the new changes. You usually need to refresh your browser to see them.

## Troubleshooting
- If changes aren't showing up after 2 minutes, try opening your site in an **Incognito/Private window** (sometimes browsers cache old versions).
- Check the "Actions" tab in your GitHub repository to see if the deployment passed or failed.
