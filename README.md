## Developing

```bash
git clone git@github.com:react-rally/www.git react-rally
cd react-rally
npm install
npm start
open http://127.0.0.1:8080
```

## Deploying

```bash
# Once your changes have been commited
npm run deploy

# Next three lines only needed if developing on branch other than gh-pages
git branch -D gh-pages
git checkout -b gh-pages
git push
```
