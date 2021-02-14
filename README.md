# Commonly used Git Commands

### Adding an existing project to GitHub using the command line

```bash
git init -b master
git add .
git commit -m "First commit"
git remote add origin  <REMOTE_URL>
# Sets the new remote
git remote -v
# Verifies the new remote URL
git push -f origin master
# Pushes the changes in your local repository up to the remote repository you specified as the origin
```
