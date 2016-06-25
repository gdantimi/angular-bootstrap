# angular-bootstrap
Angular + Boostrap UI tutorial


Add https://angular-ui.github.io/bootstrap/ to the project and create a dashboard like UI
Example: https://wrapbootstrap.com/theme/angle-bootstrap-admin-template-WB04HF123


## Installation
Since this project is using npm for the dev tools (serving, testing, building), and bower for the frontend libraries, it's better to stick to this division and install `bootstrap` and `ui-bootstrap` depedencies with bower as well.

If you don't want to install bower globally (as the `package.json` instructs to), I've added a new `bower: bower` npm script, so you can run `npm run bower install <package> <options>` to install dependencies from within the project folders. Otherwise you could just install bower globally `npm install -g bower` and then run bower commands from anywhere in the system.

To instruct bower to save the dependency in the `bower.json` file, just add the `--save` flag at the end. Example: `[npm run] bower install boostrap --save`.

Once you have installed `bootstrap` and `ui-bootstrap`, you can include the boostrap css file right into index.html, before you include `app.css`:
```
<link rel="stylesheet" href="bower_components/bootstrap/dist/css/bootstrap.min.css">
```
and then go on with the tutorial.
