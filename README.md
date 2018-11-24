# MEAN - Azure
![mean](http://i.imgur.com/7j43Fzf.jpg) 

![azure](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Microsoft_Azure_Logo.svg/500px-Microsoft_Azure_Logo.svg.png)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.3.

This is a boilerplate for creating MEAN apps and connecting them for CosmosDB on Azure. It is based on John Papa's [tutorial](https://docs.microsoft.com/en-us/azure/cosmos-db/tutorial-develop-mongodb-nodejs) and updated for the latest version of Angular.

## How to install
1. Clone this repository to your system.
```
git clone https://github.com/ImedAdel/mean-azure.git
```
If you want to clone it to a folder name `myapp` , use 
```
git clone https://github.com/ImedAdel/mean-azure.git myapp
```
2. Cd to the created folder
```
cd mean-azure
```
3. Run
```
npm install
```
or
```
yarn
```

## Configuration
Open `mean-azure/src/server/env/environment.js` and configure it. All the information you need is found in the Connection String tab.

## How to use
Simply follow the pattern of the app. You can copy existing files or edit them according to your needs.

## About Angular CLI

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
