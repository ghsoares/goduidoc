# Workflow

## Github

Feel free to contribute to Godui, it's free and open-source, you can view the source code, open issues, pull requests and more at the [Github repository](https://github.com/ghsoares/godui).

### Pull request

Before making any changes to Godui's source code, you must fork the Godui's repository into your Github's profile, clone it to your machine and make changes from there.

After making changes to Godui's source code, you can submit a pull request at [Github repository's pull request](https://github.com/ghsoares/godui/issues) which will be evaluated and merged if possible.

### Issues

You can open issues at [Github repository's issues](https://github.com/ghsoares/godui/issues) for the problems or bugs you've encountered when using Godui.

## GDExtension

Godui is made using Godot's GDExtension, which provides a more direct access to the game engine's API from C++ without recompiling the entire engine. All the source code for the extension can be found at `gdextension/src/` folder.

Instructions about compiling the GDExtension can be found at "[compiling](contributing/compiling.md)" page.

## Documentation

Godui's online documentation uses [Docsify](https://docsify.js.org/) to easily generate html at runtime using markdown, the source code can be found [here](https://github.com/ghsoares/goduidoc).

To install docsify CLI install it with npm: `npm i docsify-cli -g`

### Class reference

For the Godui's custom classes references, I've made a Node script which transpiles the class .xml reference at `classes/` folder into static markdown, the .xml files follows the same structure from Godot's class reference files.

To transpile the class reference files into documentation markdown, firstly you need to install the npm dependencies: `npm install` inside the repository then run the script with `node gen.js`.

For new classes added, you must change `gen.js:CLASS_REFERENCE` object with the name of the class and the path inside the documentation.

To see the changes, start a docsify live server with `docsify serve docs` and go to `localhost:3000` at your web browser.