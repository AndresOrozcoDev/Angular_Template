# Angular Template

This repository has the template (setup and architecture) for Angular projects. Angular version 13 is being used with LAZY LOADING.

## Setup

The project configuration is based on Lazy Loading, the whole project is in the 'src' folder which consists of the following folders and files:

- App: Folder where the main component that renders the application is located, the 'pages' folder where the pages that have their own routes will be placed and the 'shared' folder, which is a module where all the elements, components and shared styles will be placed .

For the management of good practices in CSS, the BEM methodology and the SMACSS methodology are being used.


## Installation

Run project:

```bash
  ng serve
```

Generate page and module:

```bash
  ng generate module pages/[name_component] --route page/[name_component] --module app.module
```
## Authors

- [@AndresOrozcoDev](https://github.com/AndresOrozcoDev)
