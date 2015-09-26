# Blue Diamond Awards
This project was created by Tech Talent South students in the 2015 spring full time code immersion program, as an effort to respond to requests for changes to the 2015 Blue Diamond Awards website and prepare it for 2016 launch.

The requested changes can be found here:
http://bit.ly/1NX4OPT

Students produced initial UX mockups and discussion and considered different implementation approaches (using the original Middleman code and Slim templating language, 'straight' HTML/CSS/JavaScript, and Wordpress).  The original site repo can be found in this organization.

Mockup and intial thoughts on UX can be found here:
http://bit.ly/1OC0FCy (thanks Andrew!)

This repo contains an initial effort using HTML/CSS/Javascript and gulp to automate build and deploy to Github pages. Additional work included replacement of custom forms with Google forms and investigation of custom forms in Mailchimp.

The original student repo name was 'blue_diamond_awards' but has been renamed and stored under this master It-ology Github organization for archive.
This repo is published on Github pages at: http://bluediamondawards.github.io/TTS-project-2015

To work with and publish this repo using gh-pages under your own github account:
- 1. Fork the repo
- 2. Clone it locally
- 3. Install gulp and associated gulp add-ins (see gulpfile.js)
    * npm install --global gulp
    * npm install browser-sync gulp --save-dev
    * npm install gulp-sass --save-dev
    * npm install --save-dev gulp-plumber
    * npm install --save-dev gulp-autoprefixer
    * npm install --save-dev gulp-gh-pages
- 4. Make sure you can run/view the site locally 
    * gulp
- 5. If you make changes, ensure your master branch is committed and pushed to your fork
- 6. Set up your local repo for gh-pages deployment (working from master)
    * git checkout --orphan gh-pages
    * git rm -rf .
    * git checkout master
- 7. gulp deploy

Your fork should be visible in a few moments at [your github account].github.io/TTS-project-2015/

Enjoy!

Thanks to all the students who forked the original 2015 site, and to the gang who did some heavy lifting
and learning on this project:
- Andrew Lichtenhan
- Joeseph Margolis
- Lee McCormick 
- Carlos Medina

And, thanks to Tech Talent South and IT-ology for the opportunity!

