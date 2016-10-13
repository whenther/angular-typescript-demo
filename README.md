angular-typescript-demo
=======================

A demo Angular 1 TypeScript app, for the [2016-10-13 Angular JS
Santa Barbara Meetup](https://www.meetup.com/AngularJS-Santa-Barbara/events/233258540/)
 
See a demo [here](https://whenther.github.io/angular-typescript-demo/)
Associated [slide deck](https://docs.google.com/presentation/d/1zYEvIgKL_lT_uLBDSbEcP0EpjcgCZknqm4FjGQPQgAc/edit?usp=sharing)

setup
-----
```
npm install
```

development
-----------
```
npm start
```
Then open the served app at `localhost:9966`

production
----------------------
```
npm run build
```
GitHub pages will automatically pick up the built pages from the `docs` dir.

That does mean the built files are under source control, which is weird.

testing
-------
```
npm test
```
There aren't any tests right now :-(