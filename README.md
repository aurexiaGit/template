# Aurexia Social Token

@ Copyright Aurexia - All Rights reserved

<!-- Table of Content -->

- [Template Minible](#Template-Minible)
  - [Introduction](#Introduction)
  - [Prerequisites](#Prerequisites)
  - [Installation](#Installation)
  - [Tips](#Tips)
  - [Getting Started](#Getting-Started)
  - [Support](#Support)
- [Github Pages](#Github-Pages)

<!-- End Table of Content -->

## Template Minible

Minible Theme by Themesbrand.

### Introduction

We are using gulp which allows having complete automation for build flow. In case if you don't know Gulp then it's easy to use it. Gulp is a toolkit for automating painful or time-consuming tasks in the development workflow, so you can stop messing around while building any project. You can read it more about it here. Please follow below steps to install and setup all prerequisites:

### Prerequisites

Please follow below steps to install and setup all prerequisites:

- **Yarn**

    Make sure to have the [Yarn](https://classic.yarnpkg.com/en/) installed & running in your computer. If you already have installed Yarn on your computer, you can skip this step. We suggest you to use Yarn instead of NPM.

- **Nodejs**

    Make sure to have the [Node.js](https://nodejs.org/) installed & running in your computer. If you already have installed Node on your computer, you can skip this step if your existing node version is greater than 10.

- **Gulp**

    Make sure to have the [Gulp](https://gulpjs.com/) installed & running in your computer. If you already have installed gulp on run command ```npm install -g gulp``` from your terminal.

- **Git**

    Make sure to have the [Git](https://git-scm.com/) installed globally & running on your computer. If you already have installed git on your computer, you can skip this step.

### Installation

To setup the admin theme, follow below-mentioned steps:

- **Install Prerequisites**

    Make sure to have all above prerequisites installed & running on your computer

After you finished with the above steps, you can run the following commands into the terminal / command prompt from the root directory of the project to run the project locally or build for production use:

Command |   Description
:-: | :-
yarn install | This would install all the required dependencies in the node_modules folder.
gulp | Runs the project locally, starts the development server and watches for any changes in your code, including your HTML, javascript, sass, etc. The development server is accessible at http://localhost:3000.
gulp build | Generates a /dist directory with all the production files.

### Tips

SCSS: We suggest you to do not change any scss files from the assets/scss/custom folders because to get new updates will might be break your SCSS changes if any you have made. We strongly suggest you to create new custom.scss file and use that instead of overwrite any theme's custom scss files.

### Getting Started

The steps to compile and get started with development are covered in detail above, but the summary is:

- npm install
- gulp

### Support

Themesbrand is happy to provide support for issues. Shoot us an email at support@themesbrand.com and we'll get you squared away.

## Github Pages

The webpage is available at https://aurexiagit.github.io/template/ .

All content of this page is on the branch gh-pages.

To push changes on this branch, launch command :

```command
gulp deploy
```
