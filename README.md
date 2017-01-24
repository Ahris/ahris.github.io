Visit my personal website at [ahris.github.io](ahris.github.io)!

## Usage

To test and deploy, run the following:

```
jekyll build --safe
jekyll serve --watch
git push origin source # Commit and push to "source" branch

# ignore this rakefile
rake generate # Generates /_site

jekyll build
cp /_site ../tmp
cd ../tmp/_site
git init
git add .
git commit -m "SOME MESSAGE"
git remote add origin git@github.com:Ahris/ahris.github.io.git
git push origin master --force
cd ../../
rm -rf ./tmp
```
