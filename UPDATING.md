How to update to latest upstream repo:

Only once:

- git remote add public https://github.com/DustinBrett/daedalOS

Then:

- git pull public main --no-commit
- git commit -am "Merged updates from upstream repo"
- git push origin main
