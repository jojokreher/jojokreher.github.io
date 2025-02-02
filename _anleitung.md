# Anleitung

1. Text verändern
2. In Terminal (tab neben Console): quarto render, oder **Strg + Shift + K**
3. Änderungen überprüfen
4. In Terminal
    * git add -A
    * git commit -m "Beschreibung"
    * git push

# Docs:

* quarto websites: https://quarto.org/docs/websites/
* website options: https://quarto.org/docs/reference/projects/websites.html
* about page formats: https://quarto.org/docs/websites/website-about.html

# Updates:

1. Make Changes to Your Website Locally
Edit your .qmd files, styles, or other content in your Quarto project.

2. Render Your Website
Run the following command in your project folder:

quarto render

This updates the _site/ folder with the latest version of your website.

3. Commit and Push Changes to GitHub
Add and commit your changes:

git add .
git commit -m "Updated website content"
git push origin main

4. Publish the Updated Website

quarto publish gh-pages

This will update the gh-pages branch and refresh your website.

5. Check Your Website

Wait a few seconds, then go to your website URL (https://USERNAME.github.io/REPO-NAME/) to see the updates!

