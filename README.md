#Lessons in impress.js for IMT4003 2014
Lesson material for HiG students

## Folder structure
Seminar and slider folders
```
\seminar_N\slides
```




## Build and dev dependencies
The project is dependent on the following applications:
* NodeJS
* NPM - Node Package Manager
* Bower

These have to be installed prior to building the code

## Configuration / build procedures

### Installation of project dependencies


NPM-dependencies are installed from the command line
```
npm install
````


Bower-dependencies are installed from the command line
```
bower install
```

### Build and serve procedure
Automated build procedure is provided with Grunt. Grunt will be installed when running the commands above.
Automatic build and serve is initiated with the following command from one of the slider-folders:
```
grunt server
```
