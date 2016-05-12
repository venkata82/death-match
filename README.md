# Installation:

* npm install
* npm install -g phantomjs@1.9.8


# Run visual tests:

1. Start a local web server that servers the index.html file (try using something like Serve - http://get-serve.com/)
2. Make sure that the url on line 3 of tests/visual/index.spec.js is correct
3. Start the SASS watcher from a command line propmt:   **sass --watch scss:css**
4. Run this command from a command line prompt:  **casperjs test tests/visual/index.spec.js**

# tags

* v1.0 - app with visual diff example
* v1.1 - app with module loader added and main.js created
* v1.2 - knockout and text plugin implemented, app divided into high level components
* v1.3 - all components created, scss files split into either component or separate file
* v1.4 - viewmodel created for warrior component, component helper created to register all components
* v1.5 - adding karma to run unit tests, warrior.spec.js file created
* v1.6 - create appModel with mock data, and pass it through components
* v1.7 - create matchup viewmodel, random oponents functionality
* v1.8 - increment scores on click and choose new oponents
* v1.9 - sort leaderboard decending by wins