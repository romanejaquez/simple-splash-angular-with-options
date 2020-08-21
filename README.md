# Simple Splash Angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.0.

This is a Simple Angular-based splash screen to use in your web apps and PWAs.
This version has a few simple options to display the Splash Screen:

- Adding it tho the `app.component.ts` file provides default behavior (slide left, 3-second loading with a 0.5-second animation):
  
```
<splash-screen></splash-screen>
<router-outlet></router-outlet>
```

- Adding values to the following properties:
  - animationType: one of three options: SlideLeft, SlideRight or FadeOut
  - duration: in seconds, the duration of the loading while showing
  - animationDuration: in seconds, the duration of the sliding or fading animation.

```
<splash-screen 
    [animationType]="'slide-left'"
    [duration]="2"
    [animationDuration]="0.5"
    ></splash-screen>
<router-outlet></router-outlet>
```

Please refer to [Medium Article](https://itnext.io/simple-splash-screen-for-your-angular-web-apps-and-pwas-f4fbf897540b) for more info.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
