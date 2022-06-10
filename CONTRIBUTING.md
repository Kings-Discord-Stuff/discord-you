# Looking to help contribute? Awesome!
### Here's how you can

NOTE:
We make use of [Gibbu's bd-scss](https://github.com/Gibbu/bd-scss) package for compiling our SCSS to CSS for use with better discord.

## What you'll need:

* Access to PNPM 
* Basic Knowledge of SASS/SCSS
* Basic knowledge of Git/GitHub

## Install the packages:
using your prefered terminal interface run: `pnpm i` in the `discord-you` directory

## Developing:
This theme follows [Google's Material Design 3 guidelines](https://m3.material.io/)

This theme should work on Better Discord, Powercord and Vizality.

If you are developing on Better discord, run: `pnpm dev` this will automatically compile saved changes in `./src` for you into the `./dist` directory.

## Deploying:
Simply push your changes to the main branch and make a pull request.
If everything checks out you PR will be accepted and merged with the main branch.

This will then trigger an action to compile the /src/main.scss to the deploy branch.
