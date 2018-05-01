*poly-on-fire* is a collection of proof-of-concept projects using [Polymer](https://www.polymer-project.org/) and [Firebase](https://firebase.google.com/)

|[**_Pete Carapetyan_**](http://appwriter.com)|  [TL;DR? blog](https://betterologist.net/2018/04/poly-on-fire-polymer-on-firebase/) |[TL;DR? _video:_](https://youtu.be/P9DwkqqUxNs)|
| --- | --- | --- |
|<a href="http://appwriter.com"><img class="style-svg" src="https://betterologist.net/wp-content/uploads/2016/05/pete-300x297.jpg" alt="pete" width="116" height="115" /></a>|<a href="https://betterologist.net/2018/04/poly-on-fire-polymer-on-firebase/" ><img class="style-svg" src="http://docs.datafundamentals.com/txt.png" alt="jammazwanPhotoSmall" width="200" height="116" /></a>|<a href="https://youtu.be/P9DwkqqUxNs"><img class="style-svg" src="https://betterologist.net/wp-content/uploads/2016/05/jamzVid1.png" alt="about" width="115" height="115" /></a>|


##### A project for learning an aspect of developing a Polymer app, deployed on Firebase hosting.

The idea is to prove out an approach or component in the simplest project first, before combining it with other code in a real project.

----

# \<poly-on-fire-redux\>

## What it does:

This is a polymer2 app modeled somewhat after polycast 61 by rob, which is a polymer1 demo.

## Here is what it looks like when it is running

[demo](https://youtu.be/weDucpaEAac)

shown with dev tools open in chrome. If it fills with red you might check if you've run bower install

## How I Install and Run It

from my bash shell:

```
git clone git@github.com:poly-on-fire/poly-on-fire-redux.git
cd poly-on-fire-redux/
source refresh_npm.sh
cd public/
bower install
polymer serve
```

then run it from the browser

## Pre-requirements

You will need to have nvm installed, or else modify refresh_npm.sh accordingly to use your current version of npm

## Notes

This app arbitrarily uses a hide function to do it's demo.

There are better ways to do this hide, but since that isn't the core of the functionality, doesn't matter here.

This demo barely touches the redux api. When I did a real implementation after this demo app, I had to do a lot more experimentation, specifically within the reducer.
