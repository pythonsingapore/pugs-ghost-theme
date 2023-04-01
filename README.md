# PUGS Ghost Theme

This repo has the theme that use on the ghost.org instance that hosts
https://pugs.org.sg

# Local development

* Install ghost: `npm install ghost-cli@latest -g`
* Clone this repo
* `cd ghost && ghost start`
* Visit `http://localhost:2369/ghost/` and login with
  * `contact@pugs.org.sg` and `test123123`
* In another terminal:
  * `cd wave`, `yarn`, `yarn dev`
  * This starts watchers that recompile the theme assets when you make changes

Now you can edit the files in the `wave` folder. You don't need to touch
the `ghost` folder.