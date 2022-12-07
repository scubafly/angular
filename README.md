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

### Run the project:
`ng serve` and visit localhost:4200

### String Interpolation
in html file like twig: {{ <propertyOrFunction> }} value must return a string like output. 

### Property binding in a component:
[disabled]="<propertyname>"

### Event binding in a component:
(click)="<functionName()>"

### Console.log the element to see the properties and events to bind to.
