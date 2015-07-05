# pr-web-app

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.12.0.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

## NOTES
Had to add this script to Gruntfile.js to get project to build
http://stackoverflow.com/questions/31166376/yeoman-error-launching-project-with-grunt-command  
// Automatically load required Grunt tasks
require('jit-grunt')(grunt, {  
  useminPrepare: 'grunt-usemin',  
  ngtemplates: 'grunt-angular-templates',  
  cdnify: 'grunt-google-cdn'  
});  

