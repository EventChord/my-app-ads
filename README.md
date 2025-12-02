# Bodes DevOp Developer Website

This is a simple developer website created with the HTML5 UP Forty template that hosts the app-ads.txt file for AdMob verification.

## Files Included

- `index.html` - The main website page with developer information
- `app-ads.txt` - The AdMob authorization file with your publisher ID
- `assets/` - CSS, JavaScript, and web fonts for the website
- `images/` - Sample images from the HTML5 UP template

## Deployment to GitHub Pages

1. Create a new GitHub repository named `Bodes`
2. Push all files to the repository:
   ```bash
   git init
   git add .
   git commit -m "Add developer website with app-ads.txt"
   git remote add origin https://github.com/BodesDevOp/Bodes.git
   git branch -M main
   git push -u origin main
   ```
3. Enable GitHub Pages in the repository settings:
   - Go to Settings > Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)"
   - Save and wait for deployment

## Accessing Your Files

After deployment, your files will be accessible at:
- Main website: https://BodesDevOp.github.io/Bodes/
- App-ads.txt: https://BodesDevOp.github.io/Bodes/app-ads.txt

## Updating the Website

To make changes to the website:
1. Edit the files locally
2. Commit and push the changes:
   ```bash
   git add .
   git commit -m "Update website"
   git push origin main
   ```

The website will automatically update within a few minutes of pushing changes.