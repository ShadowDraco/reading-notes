# Node, Express, NPM, TDD, CI/CD

## [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

- Explain middleware, answer as though I were a non-technical recruiter.

  - Middleware is code that runs before or after a process in the server happens. When a user visits a specific link on a website the middleware does a task like checking if a user is logged in, before showing the user's profile.

- Express the most popular _web framework_.

- Express is “unopinionated.” What does that mean?

  - express is being an unopinionated framework means that you can write code in practically any order to solve many various problems. There is no specific structure for files, middleware, or components.

- What is a module and why is modularity useful to us as developers?

  - a module is a piece of code that is 'exported' and then 'imported' into another place. A calculator object may export its functions like

  ```javascript
  export const add = (num1, num2) => {
    return num1 + num2;
  };
  ```

  - this code can then be imported from the calculator to simplify another task. Modules are important because they help developers write clean code that is reuseable, creating modules is important to keep complexity down, and make a namespace with organized and reusable tools.

## [What is NPM?]()

Npm is a _software registry_

- What version of npm are you running on your machine?

  - npm version: 8.15.0

- What command would you type to install a library/package called ‘jshint’ into your node project?

  - `npm i jshint`

## [What is TDD?](<https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1)>)

- Explain why tests are important. Please explain as though I were your non technical elder.

  - Test Driven Development is the process of defining a problem that needs to be solve and writing the code to test if that problem _has_ been solved. Then the developers write the code to solve the problem and check it using the code they wrote to test it. Tests are simply a way of testing if code does what its supposed to. Writing code to make the tests pass is an excellent way of making sure that features are working.

- What are three expected benefits of testing

  - Expected benefits of testing are a significant reduction in code defects and errors, great reduction in the project's final phases, and improved design qualities in the code.

- Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

  - writing too many tests at once, and writing tests that are too large will become unhelpful for the individual. Not bringing the whole team in on the TDD and abandoning the test suite is poor for the team.

## [CI/CD](https://circleci.com/continuous-integration/?utm_source=google&utm_medium=sem&utm_campaign=sem-google-dg_acq-2022q3-uscan-en-initialUseNqtoIncident-maxClick-auth_qsu-nb&utm_term=g_p-what%20is%20ci%20cd_c__rsa1_&utm_content=sem-google-dg_acq-2022q3-uscan-en-initialUseNqtoIncident-maxClick-auth_qsu-nb_keyword-text_rsa-gettingStartedCICD_v1&gclid=CjwKCAjw04yjBhApEiwAJcvNofjeLwmcou7cws3M6yYQXtA2UTAbtY07GVFphTUTLoOJYZzTdAhsohoCIiUQAvD_BwE)

What are three benefits of Continuous Integration?

- Continuos integration allows a team to work in small portions to push working code, test it, and verify if the code is ready for deployment. Fix small errors very quickly and then move on. Its efficient and

What is the difference between Continuos Delivery and Continuous Deployment?

- Continuous delivery keeps code ready to deploy, while continuous deployment automates the process of building, testing, and deploying when tests pass with every push.

Explain how GitHub fits into this process assuming the listener comes from a non-technical background

- Github is a system that allows developers to track changes big and small in code, it allows automatic testing of this code before adding it to the old code (CI) and 'actions' like automatically deploying the new changes to a website when those tests pass (cd)

## Goals

im excited about learning TDD!

## Things I want to know more about

CI/CD
