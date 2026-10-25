# EduSpark B.Ed. ECA Website
Three pages: Home, ECA Subjects, Activities & Practice.
Built with HTML, CSS, JavaScript and Bootstrap.
Open index.html to preview. Bootstrap is loaded from a CDN.
To publish, install Git and GitHub CLI, run `gh auth login`, then run:
git init
git add .
git commit -m "Create B.Ed. ECA site"
git branch -M main
gh repo create bed-eca-learning --public --source . --remote origin --push
Then open GitHub repository Settings > Pages and select main branch, /(root).
