# Learning Plan for Test Driven Development (TDD)

These learning resources primarily focus on Test Driven Development (TDD).

- There is an emphasis on learning using PHP, Laravel and PHPUnit.
- All these resources are free (at the time of writing)

<!-- vscode-markdown-toc -->

## Table of Contents

- [1. Videos](#Videos)
- [2. Blog Posts](#BlogPosts)
- [3. Books, manuals and websites](#BooksManualsAndWebsites)
- [4. Tooling](#Tooling)
- [5. Three Laws of TDD](#ThreeLawsOfTDD)
- [6. Examples & Code Kata](#ExamplesCodeKata)
- [7. Project with Tests](#ProjectWithTests)
- [8. Conclusion](#Conclusion)
- [9. Other Learning Plans](#OtherLearningPlans)
- [10. License](#License)


## 1. <a name="Videos"></a>Videos

- [ ] [TDD: The Good Parts](https://vimeo.com/110388553) - Adam Wathan: A talk I recently gave at the Laravel Toronto meet up.
- [ ] [APIs in Laravel Using TDD](https://www.youtube.com/playlist?list=PL3ZhWMazGi9KGG64X_HJlZ_sQuvyFGoMo) - TDD course by Devlob [Notes (Gist)](https://gist.github.com/Pen-y-Fan/665cc7a6b86bbaaff1071af9747e82ee)
- [ ] [PHPUnit Testing](https://www.youtube.com/playlist?list=PLe30vg_FG4OTsFRc1eWppZfYwZdMlLuhE) - TDD course by Bitfumes Webnologies [Notes (Gist)](https://gist.github.com/Pen-y-Fan/6da65bf4c35976379a8458894159841c)
- [ ] [The Three Laws of TDD (Featuring Kotlin)](https://www.youtube.com/watch?v=qkblc5WRn-U) - A hand-on demo of Test Driven Development using the Kotlin language, by Uncle Bob
- [ ] [Chasing "Perfect" - Adam Wathan - Laracon EU 2015](https://youtu.be/5DVDewOReoY) - Real time coding clean code, using tests at every step of the process.
- [ ] [geepawhill.org - TDD & The Lump Of Coding Fallacy](http://geepawhill.org/tdd-and-the-lump-of-coding-fallacy/)
- [ ] [PHP UK Conference 2017 - Anna Filina - Unit Testing by Example](https://youtu.be/ESl-ncXA4G0) - PHP UK Conference 2017. Presentation giving realistic and pragmatic examples.
- [ ] [Jeffrey Way - Laravel Testing Tips, Techniques and Pitfalls](https://youtu.be/vmeh8XgrC2U) - Presentation from Laracon EU Oct 2013
- [ ] [Is TDD Dead?](https://martinfowler.com/articles/is-tdd-dead/) - A series of conversations between Kent Beck, David Heinemeier Hansson (DHH), and Martin Fowler on the topic of Test-Driven Development (TDD) and its impact upon software design.
- [ ] [Is TDD dead? Of course not! But what´s all the fuzz about then? Emily Bache](https://youtu.be/PCEHRFHKZSk) - Emily Bache talks about DHH's blog
- [ ] [Laravel 5.8 Tutorial From Scratch - e49 - Testing 101 Using PHPUnit](https://youtu.be/RJ_iXzdSpT0) - Testing is an integral part of modern PHP development. Let's work to get our customer controller under test. [Notes (Gist)](https://gist.github.com/Pen-y-Fan/215b72e1e2abe3a4b90f730360503a58)
- [ ] [YouTube - Test Driven Laravel](https://www.youtube.com/playlist?list=PLpzy7FIRqpGAbkfdxo1MwOS9xjG3O3z1y) - TDD in Laravel by Coder's Tape [(Notes (Gist)](https://gist.github.com/Pen-y-Fan/bb3eea45e71ab066787bdf472741374f)
- [ ] [Test Driven Laravel from Scratch](https://vimeo.com/151390908) - Adam Wathan: walk through using outside-in TDD [Notes (Gist)](https://gist.github.com/Pen-y-Fan/e3a0393c00965d663d74f1a7d7c5eb35)

## 2. <a name='BlogPosts'></a>Blog Posts

- [ ] [Devlob blog - 7 TDD Advantages with Real Life Examples](https://devlob.com/blog/7-tdd-advantages-with-real-life-examples)
- [ ] [Devlob blog - 7 Reasons to NOT Use TDD](https://devlob.com/blog/7-reasons-to-not-use-tdd)
- [ ] [The Clean Code Blog by Robert C. Martin (Uncle Bob)](https://blog.cleancoder.com/uncle-bob/2014/12/17/TheCyclesOfTDD.html)
- [ ] [geepawhill.org TDD](http://geepawhill.org/categories/tdd/) - 57 categories on TDD
- [ ] [Start testing your Laravel applications (Jason McCreary)](https://jasonmccreary.me/articles/start-testing-laravel/)
- [ ] [Lowering the time cost of testing existing Laravel applications (Jason McCreary)](https://jasonmccreary.me/articles/lower-time-testing-existing-laravel-application/)
- [ ] [What is Software Testing and Why do we Test Software?](https://www.eviltester.com/blog/eviltester/2019-03-06-what-is-testing-and-why-do-we-test/) eviltester.com - 9 min read with 9 min video.

## 3. <a name='BooksManualsAndWebsites'></a>Books, manuals and websites

- [ ] [butunclebob.com - TheThreeRulesOfTdd](http://butunclebob.com/ArticleS.UncleBob.TheThreeRulesOfTdd)
- [ ] [PHPUnit Manual](https://phpunit.readthedocs.io/en/8.0/)
- [ ] [wikipedia.org Test driven development](https://en.wikipedia.org/wiki/Test-driven_development)
- [ ] [MartinFowler.com testing culture](https://martinfowler.com/articles/testing-culture.html)
- [ ] [Simple TDD in Laravel with 11 steps](https://medium.com/@jsdecena/simple-tdd-in-laravel-with-11-steps-c475f8b1b214) - Medium by Jeff Simons Decena
- [ ] [Repository pattern with Laravel](https://medium.com/@jsdecena/refactor-the-simple-tdd-in-laravel-a92dd48f2cdd) - Medium by Jeff Simons Decena
- [ ] [Practical Php Testing is here](https://www.giorgiosironi.com/2009/12/practical-php-testing-is-here.html) Siorgio Sironi (2009) - although an old book, it is still a good guide to testing.. Only 61 page PDF.

## 4. <a name='Tooling'></a>Tooling

- VS Code
  - Extension: Better PHPUnit ([video](https://laracasts.com/series/visual-studio-code-for-php-developers/episodes/10))
    - Configure CTRL + T to run tests, CTRL SHIFT + T to rerun
- PHPUnit ([doc 8.0](https://phpunit.readthedocs.io/en/8.0/installation.html))
  - Recommended to install per project:
    - `composer require --dev phpunit/phpunit ^|version|`
    - e.g. `composer require --dev phpunit/phpunit ^8`
    - Included with dev dependencies on the laravel framework.
  - Install globally, configure **phpunit.bat** and add to path (not recommended but useful for running from the command line).

## 5. <a name='ThreeLawsOfTDD'></a>Three Laws of TDD

> Over the years I have come to describe Test Driven Development in terms of three simple rules. They are:
>
> 1. You are not allowed to write any production code unless it is to make a failing unit test pass.
> 2. You are not allowed to write any more of a unit test than is sufficient to fail; and compilation failures are failures.
> 3. You are not allowed to write any more production code than is sufficient to pass the one failing unit test.

Uncle Bob's full article: [Source](http://butunclebob.com/ArticleS.UncleBob.TheThreeRulesOfTdd)

## 6. <a name='ExamplesCodeKata'></a>Examples & Code Kata

- [ ] [An introduction to Test-Driven Development (TDD)](https://github.com/daylerees/test-driven-development-example) - Representation of a complete application at a different points in TDD.
- [ ] [Starting code for the GildedRose Refactoring Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata/tree/master/php)
- [ ] [Starting code for a Refactoring Code Kata on the Tennis rules](https://github.com/emilybache/Tennis-Refactoring-Kata/tree/master/php)
- [ ] Use Adam Wathan's Test Driven Laravel from Scratch video above as a guide and practice this method.

## 7. <a name='ProjectWithTests'></a>Project With Tests

- [ ] [October CMS](https://github.com/octobercms/october) - Based on Laravel, on setup there is a full set of tests to run. (Runtime ~10 min - with xdebug on), turn xdebug off if not generating reports
  - [ ] October has been installed and run, examine the tests in more detail, what are they testing, etc.
- [ ] [Laravel Boilerplate](http://laravel-boilerplate.com/) - Tests take 10 min to run (with xdebug on), turn xdebug off if not generating reports
  - [ ] Laravel Boilerplate has been installed and run, examine the tests in more detail, what are they testing, etc.

## 8. <a name='Conclusion'></a>Conclusion

Notes are still ongoing and may not necessarily make sense out of context.

- TDD, when used correctly are good.
- Documentation can be created from well named tests.
- Test behaviour not implementations.
- Testing is an art, there isn't a right way for everything.
- Testing takes practice
- Try to use real objects rather than mock data.
- Tests should be trustworthy.
- Anna Filina (Recap)
  - Write a test to prove what is being tested works.
  - Write tests when you see a bug
  - Write test when you improve code
  - Write tests as you write new code
  - Write tests before you write code
  - Text unexpected scenarios
  - Testing = Pre-emptive Debugging
- Google
  - Small - like unit testing
  - Medium
  - Large - acceptance testing
- Mocking can cause dependencies or coupling.
- Ensure that both success and failure cases are covered by appropriate unit tests
- There's a lot of value in reading books on good coding and design practices even if they don't focus on unit testing
- TDD is recommended for any long lasting project which may need new features in the future.

## 9. <a name='OtherLearningPlans'></a>Other Learning Plans

The next plan from TDD was [Learning Plan for Design Patterns and Principles of Good Design](https://gist.github.com/Pen-y-Fan/c99a94102fee9fd132265578b20885a1)

## 10. <a name='License'></a>License

Copyright (c) 2019 [Pen-Y-Fan](https://github.com/Pen-y-Fan)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this learning plan and associated documentation files (the "Plan"), to deal
in the Plan without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Plan, and to permit persons to whom the Plan is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Plan.

Content copied from [Wikipedia.org](www.Wikipedia.org) is available under the [Creative Commons Attribution-ShareAlike License](https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License); additional terms may apply.
