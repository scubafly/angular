# angular
how to set up an angular project

## go to a folder and run
`ng new <project name>`

## Add bootstrap:
`npm install --save bootstrap@3`

## Add bootstrap to the angular.json
project -> architecht -> build -> options -> styles:
```
"styles": [
              "node_modules/bootstrap/dist/css/bootstrap.min.css",
              "src/styles.css"
            ],
```
