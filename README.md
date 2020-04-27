# studee-login
## Assumptions
I've tried to implement the spirit of the design over an exact recreation (i.e. exact spacing of elements, roundness of corners etc.) I've used Bootstrap to get started quickly with the layout. I've purposely left the unused scripts in so as not to hide that I've used their starter template.

It's only browser tested in Chrome + device simulation.

In practice I would componentise the layout, probably using a JS framework like React, and use SCSS in order to create reusable variables for styling to speed up development.

### Any other observations
There are a few tiny usability improvements that could be made. The input labels could be visible instead of placeholder text as it can get confusing what the field is once you start typing. 'Sign in with Google' may be more descriptive button text than simply 'With Google'.

#### Further JavaScript example
For an example of unit and e2e tested Javascript code please see https://github.com/richiesteadman/store, which is simple store UI built with Angular. To run, clone the repo, run `npm i` to install packages, `ng serve` to view, `ng test` to run unit tests and `ng e2e` to run browser tests.
