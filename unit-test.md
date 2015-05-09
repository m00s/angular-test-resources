## What is a unit test?
> A unit test is an automated piece of code that invokes a unit of work in the system and then checks a single assumption about the behavior of that unit of work.

### The AngularJS way
> Angular is written with testability in mind, but it still requires that you do the right thing. We tried to make the right thing easy, but if you ignore these guidelines you may end up with an untestable application.

> Angular comes with [dependency injection](https://docs.angularjs.org/guide/di) built-in, which makes testing components much easier, because you can pass in a component's dependencies and stub or mock them as you wish.

### Tools

![Unit testing tools](http://i62.tinypic.com/2cdtqfa.png)

Tool         | Description
------------ | -------------
[Karma](http://karma-runner.github.io/0.12/index.html) | Test runner
[Jasmine](http://jasmine.github.io/) / [Mocha](http://mochajs.org/) / [UnitJS](http://unitjs.com/)| Unit test frameworks

I tried every test framework listed above and I definitely agree with [the JS guy](http://thejsguy.com/2015/01/12/jasmine-vs-mocha-chai-and-sinon.html)

### Articles
* [Full-Spectrum Testing with AngularJS and Karma (yearofmoo)](http://www.yearofmoo.com/2013/01/full-spectrum-testing-with-angularjs-and-karma.html)
* [Unit Testing Best Practices in AngularJS (Andy Shora)](http://andyshora.com/unit-testing-best-practices-angularjs.html)
* [AngularJS Unit Testing Best Practices (Manuel Weiss)](https://blog.codeship.com/angularjs-tdd/)
* [Testing Promises with Jasmine (Bluescreen)](http://ng-learn.org/2014/08/Testing_Promises_with_Jasmine/)
* [Advanced Testing and Debugging in AngularJS (yearofmoo)](http://www.yearofmoo.com/2013/09/advanced-testing-and-debugging-in-angularjs.html)
* [Testing Services, Controllers & Providers (Rabi Kiran )](http://www.sitepoint.com/unit-testing-angularjs-services-controllers-providers/)

### Presentations
* [JavaScript TDD with Jasmine and Karma](http://www.slideshare.net/cebartling/javascript-tdd-with-jasmine-and-karma)
* [TDD Basics with Angular.js and Jasmin](http://www.slideshare.net/iquark/tdd-basics-with-angular-and-jasmine)
* [Testing JavaScript with Jasmine](http://www.slideshare.net/timtyrrell/testing-javascript-with-jasmine-8998985)

### Examples
* [AngularJS unit testing demo](https://github.com/nirkaufman/angularjs-unit-testing-demo)

### Fiddles
* [Testing a controller w/ Jasmine](http://jsfiddle.net/eitanp461/XrJMr/)
* [Testing promises w/ Jasmine](http://jsfiddle.net/eitanp461/vjJmY/)

### Books
* [AngularJS Test driven Development (Tim Chaplin)](http://www.amazon.com/AngularJS-Test-driven-Development-Tim-Chaplin/dp/1784398837)
* [AngularJS Testing Cookbook (Simon Bailey)](http://www.amazon.com/Angu/larJS-Testing-Cookbook-Simon-Bailey/dp/1783983744)
* [JavaScript Testing with Jasmine (Evan Hahn)](http://www.amazon.com/JavaScript-Testing-Jasmine-Behavior-Driven-Development/dp/1449356370)

### Media
* [Introduction to AngularJS Unit Testing](https://www.youtube.com/watch?v=UDB-jm8MWro)
* [Testing Strategies for Angular JS](https://www.youtube.com/watch?v=UYVcY9EJcRs)
* [AngularJs Unit Testing with Jasmine (playlist)](https://www.youtube.com/playlist?list=PLw5h0DiJ-9PDbh2i6knU4FybWA63PPbVi)

### Helpful links
* [How to unit test isolated scope directive in AngularJS](http://stackoverflow.com/questions/17371836/how-to-unit-test-isolated-scope-directive-in-angularjs)
