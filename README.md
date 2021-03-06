# UnderArmourClone

#### Angular project for Epicodus

_Published_ **April 5, 2019** <br>
_Author_ **Kim McConnell**

1. [Description](#description)
1. [Learning Objective](#learning-objective)
1. [Product Requirements](#product-requirements)
1. [Planning](#planning)
1. [Completed Features](#completed-features)
1. [Stretch Goals](#stretch-goals)
1. [Installation](#installation)
1. [Known Bugs](#known-bugs)
1. [Technologies Used](#technologies-used)
1. [License](#license)

### Description
A clone of the Under Armour website using the Angular framework and sass for styling.

### Learning Objective
To practice using the Angular framework with components to style a clone site. To use routing to navigate to different pages.


### Product Requirements
* The clone site must look and function the same way as the original site.
* Angular implemented with the MVC model (where C = component)
* Data is passed down to child components
* Actions are passed up to parent components

## Planning
Below is the core plan for the project. Each box represents a component. Components may be repeated multiple times, as necessary.
![Component Plan](./src/assets/plan.jpg)

### Completed Features

As of March 29, 2019:
* 9 separate components with functionality
* A main page that displays the content of the components
* A data file to hold the text data
* Property binding to pass data to child components
* Models for various sets of data
* Some responsive layout features, including an image grid and a HostListener for listening for window resizing

As of April 5, 2019:
* Multi-page functionality with an angular router (one route)
* Moving some of the data to a firebase database
* Use a product API to get placeholder data for products
* Header styled with most elements from original site. (Partially responsive)
* Footer component, content and styling. (Partially responsive)
* Nav drop down functionality (partially styled but incomplete)
* Use a product API to get placeholder data for products


### Stretch Goals
* Deployment to Firebase
* Moving some of the data to a firebase database


### Installation
* Clone from https://github.com/kimmcconnell/under-armor-clone.git either directly from GitHub or running `git clone https://github.com/kimmcconnell/under-armor-clone.git` in your terminal
* Run `$ npm install` in your terminal after navigating to the under-armor-clone directory
* If you do not have the angular CLI package already installed on your computer, run `npm install -g @angular/cli@1.6.5`
* FOR PRODUCTS PAGE TO WORK you will need an API key. 
* Run `ng serve --open` to open the project in a browser window


### Known Bugs
* None identified

### Technologies Used
* Angular framework with Typescript
* Sass with variables and mixins

### License
[MIT](./LICENSE.txt)

Copyright (c) Kim McConnell














This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.

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
