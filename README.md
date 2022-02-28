# AngularRouting

<p align="center">
    <img src="src/logo.png">
</p>

This is an Angular project for Routing. The project page contains basic routes and Wild card routes.

_WildCard Routes_

The Wildcard Route is basically used to handle the invalid URLs. Whenever the user enters some invalid URL or if you have deleted some existing URL from your application, then by default 404 page not found error page is displayed.

_Lazy loading_

You can configure your routes to lazy load modules, which means that Angular only loads modules as needed, rather than loading all modules when the application launches. Additionally, you can preload parts of your application in the background to improve the user experience.

_Preventing unauthorized access_

We use route guards to prevent users from navigating to parts of an application without authorization.


# Install the following dependencies 

[Bootstarp Widgets](https://ng-bootstrap.github.io/#/home)

```
ng add @ng-bootstrap/ng-bootstrap
```


[Angular-fontawesome](https://github.com/FortAwesome/angular-fontawesome)

```
ng add @fortawesome/angular-fontawesome
```

<hr>

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
