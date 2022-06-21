# Add a new project

* create a `project.scss` file
* copy and paste any variables from `_custom_variables.scss` you want to
override, remove any `!default` markers
* add an import statement at the bottom of the file (after the overrides):

    @import "node_modules/bootstrap/scss/bootstrap";

* run:

    $ sass --style=compressed project.scss > bootstrap5_project.min.css
