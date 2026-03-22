# Fetch and push 2 remotes

Push to two remotes with one command:

```bash
# push an existing repository to 2 remote

git init
git add .
git commit -m "Transfer to new repository to 2 remote"
git remote add origin git://original/repo.git
git remote set-url --add --push origin git://original/repo.git
git remote set-url --add --push origin git://another/repo.git
git branch -M main
git push -u origin main

```

## [~]
