MODES Lab static site package

Files included:
- index.html
- research.html
- methods.html
- projects.html
- publications.html
- team.html
- news.html
- contact.html
- style.css
- images/

How to deploy on GitHub Pages:
1. Open your repository: wellerd2.github.io
2. Delete or replace the existing HTML files and style.css
3. Upload every file from this package, keeping index.html in the repo root and the SVG files inside images/
4. In GitHub, go to Settings > Pages
5. Set Source to "Deploy from a branch"
6. Set Branch to "main" and Folder to "/ (root)"
7. Save and wait a minute or two, then open https://wellerd2.github.io/

How to replace the placeholder portrait later:
- Upload your real file into images/
- Update team.html so the img src points to that filename

The package avoids broken local image links by including SVG placeholders that already work.