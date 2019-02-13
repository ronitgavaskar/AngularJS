# AngularJS
Just a collection of simple AngularJS applications to learn the language

## Project 1:
Goes through a "Hello World" program and takes in your input as a name and then uses that in a `<p>`  tag

### Learned:
`ng-app` defined the entire project as an angular app
`ng-model` defines the model that can be referenced later via `{{}}` as seen in the case of the variable `name`

--------
## Project 2:
Looks at `ng-if` statements and if it's set to `true` then prints out "Good Morning" and if set to `false` prints out "Good Night"

### Learned:
`ng-if` statements that are just like if-else statements in other languages to decide which branch to look at

---------
## Project 3:
Initialized a variable `hour_of_day` to a certain value and depending on time of day, prints out "Good Morning" or "Good Evening"
if hour_of_day is less than 12: prints Good Morning
if hour_of_day between 12 and 17: prints Good Afternoon
if hour_of_day between 17 and 22: prints Good Evening
If hour_of_day greater than 22: prints Good Night

### Learned:
`ng-init` to initialize a variable 
`example: <body ng-init="time=12"> `

---------
