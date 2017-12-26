# Myfirstapp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

//////// ADDED BY VIKAS /////// 

This is the first sample angular app developed by cli and edited to include ngModel input box 
// 1 TO 6 sample initial program to create sample angular app and edit it with ngModel input text and display it 

//Updating npm
npm install -g npm
//updating CLI
npm uninstall -g angular-cli @angular/cli
npm cache clean

Just to refer go here https://cli.angular.io/
Install latest current NodeJS  https://nodejs.org/en/ 
// Go to cmd and navigate to directory where you want to create project and run below to install angular cli globally : 
npm install -g  @angular/cli
this will create new myfirstapp
ng new myfirstapp
this will open the little server for provising our angular app to understand http protocol
navigate to directory myfistapp by cd myfistapp and run below command
ng serve
http://localhost:4200/
your first sample app is running

Install IDE any of below to get started 
webstorm/sublime/atom/Microsoft visual studio Code
Let we start with webstorm and open the project myfirstapp 
Now edit the app.component.html and add below in div 
<input type="text" [(ngModel)]="name">
<p>{{name}}<p>

Specify name property in app.component.ts as below in class
name = '';

To work with ngModel need to import FormsModule 
Just under import section add  FormsModule section in app.module.ts


or create a new repository on the command line
echo "# ANGULAR-WORK" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/vikky225/ANGULAR-WORK.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin https://github.com/vikky225/ANGULAR-WORK.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
