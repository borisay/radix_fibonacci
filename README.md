# Radix Fibonacci subtheme for Drupal 8/9 based on Radix theme

## Installation

### Dependencies

1. Radix
2. Components

composer require drupal/radix drupal/components

or

https://ftp.drupal.org/files/projects/radix-8.x-4.10.tar.gz

https://ftp.drupal.org/files/projects/components-8.x-2.4.tar.gz

### Radix Fibonacci theme uses [Webpack](https://webpack.js.org) to compile and bundle SASS and JS.

#### Step 1
Make sure you have Node and npm installed. 
You can read a guide on how to install node here: https://docs.npmjs.com/getting-started/installing-node

If you prefer to use [Yarn](https://yarnpkg.com) instead of npm, install Yarn by following the guide [here](https://yarnpkg.com/docs/install).

#### Step 2
Go to the root of radix_fibonacci theme and run the following commands: `npm install` or `yarn install`.

#### Step 3
Update `proxy` in **webpack.mix.json**.

#### Step 4
Run the following command to compile Sass and watch for changes: `npm run watch` or `yarn watch`.
