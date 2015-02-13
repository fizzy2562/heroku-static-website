# heroku-static-website
A boilerplate to deploy a static website on heroku.

#### Useful for what?
Heroku offers up to 100 free tiers (dynos in heroku lang). This way you can use them for hosting you're personal website, landing pages for your projects, the cat gallery, etc.

#### Usage
Clone the repo, put an index.html in */public* and files in given /public subfolders, as you would do on any hosting service. Than deploy. Yay!

Note that no apache indexes-like feature is available (That's safer!).

#### Customization
If you want/need to use different folders in */public*, edit *config.ru*.

#### Any demo?
Sure! [This page](http://static-demo-1.herokuapp.com/) and its companion stuff are running on heroku.