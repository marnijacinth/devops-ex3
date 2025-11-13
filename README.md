git status


git checkout -b feature-demo
git add app.py
git commit -m "Add demo feature to app.py"
git push origin feature-demo
git checkout main
git pull origin main
git merge feature-demo
git push origin main
