# Modus Angular Components

## About
This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.0
The components in this library were programmatically generated using the [StencilJS](https://stenciljs.com/) [Angular Framework Integration](https://stenciljs.com/docs/angular).

## Installation
* Install the Modus Angular Components Library and its Modus Web Component dependency
`npm install @trimble-oss/modus-web-components @trimble-oss/modus-angular-components --save`
  

* Add the following snipped to your `app.module.component` (or any similar module)
  ```typescript
  import { defineCustomElements } from "@trimble-oss/modus-web-components/loader";

  defineCustomElements()
  ```

* Use a modus button in your `app.component.html`

  ```angular2html
   <modus-button color="danger" [disabled]="false" (click)="onClick()">Cancel</modus-button>
  ```

## Contributing
To contribute to the Modus Angular Components library please see the Modus Web Components contributing readme

## Build

* From the stencil (root project) directory run
`npm run build`

* From the angular-workspace directory run
`npm run build`
