Boilerplate for Backbone, React and Firebase apps

Based on the Universal JS Boilerplate Created By Matt Keas (https://github.com/matthiasak)


Getting Started
Start your own project folder with a git clone, and if you plan to push this clone to GitHub, you'll need to change your origin:

cd ~/Github\ Projects/
git clone git@github.com:boazblake/boilerplate.git NEWPROJECT
cd NEWPROJECT
git remote remove origin
git remote add origin YOUR_SSH_ADDRESS
Install prerequisites

npm install
Start your server:

npm start

# Alternatively, if doing server-side work
# npm run start:n
Ready to push your code to heroku?

git commit -am "Let's do this"
heroku create <my app name>
git push heroku HEAD:master
Or are you pushing to gh-pages instead?

npm run publish:gh-pages
Or are you using surge.sh?

npm run publish:surge
# you may be prompted to login or signup,
# and then you'll be asked what URL to push to on surge.sh
Note: you can teardown a surge.sh URL with npm run teardown, which will prompt you for the URL to bring down
Want to generate your own documentation with esdocs?

# build docs and open locally
npm run docs
open dist/esdoc/index.html
# or build AND publish to gh-pages or to surge
npm run docs:gh-pages
npm run docs:surge
Need shields?

http://shields.io/

License
MIT.