cd ~/polytech-git-lab

git switch -c feature-contact

echo "<h1>Contact</h1>" > contact.html
git add contact.html
git commit -m "Add contact page"

git push -u origin feature-contact
