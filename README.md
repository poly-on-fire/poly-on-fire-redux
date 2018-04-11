# \<poly-on-fire-redux\>



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

This is a polymer2 app modeled somewhat after polycast 61 by rob, which is a polymer1 demo.

This app arbitrarily uses a hide function to do it's demo.

There are better ways to do this hide, but since that isn't the core of the functionality, doesn't matter here.

This demo barely touches the redux api. When I did a real implementation after this demo app, I had to do a lot more experimentation, specifically within the reducer.
