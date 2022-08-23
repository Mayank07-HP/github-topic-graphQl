# GitHub Topic Explorer

## Assignment:

Your task is to build a React web application that displays all the "[topics](https://docs.github.com/en/free-pro-team@latest/graphql/reference/objects#topic)" related to the term "react", using the GitHub GraphQL API.

The application should display how many "[stargazers](https://docs.github.com/en/free-pro-team@latest/graphql/reference/objects#stargazerconnection)" each topic has. A click on a topic should display the topics related to that topic, and how many stargazers they have. And so forth. There should also be Search capability to search/query on any term or topic. You should implement best practices with the UI.

To interact with the Github GraphQL API you'll need to have

- a [Github API key](https://docs.github.com/en/free-pro-team@latest/graphql/guides/forming-calls-with-graphql#authenticating-with-graphql)
- You'll want to make use of the key in the .env file within your application

You may use whatever React framework or library you find useful. URL routing is optional.

## Evaluation:

- We will pay particular attention to the way the code is organized, and to the overall readability
- Unit tests will be greatly appreciated
- Design will be ignored, however usability and accessibility will be taken into consideration
- Remember to update this README with instructions on how to install, run and test your application
- Your first goal is to have a working app, but feel free to improve the application however you see fit
- We hope that you can complete the assignment within 2 hours but don't set any time constraints
- Please reach out per email or by opening an issue if anything is unclear or blocking you

Best of luck

## Dev Notes

- I have used Apollo Client as through manage the state of the application
- Ant Design to use predefine component for UI
- React-testing-library to create test cases for the application.

### How to run app & test

- Run `npm install` to get all required dependencies installed.
- Then run `npm start` to run project on localhost, i.e. *localhost:3000*
- To run test cases, run `npm run test`, it will execute the unit tests on the terminal screen.
  - It will show the results of the test when the test process get finished.

### Future Improvements

Feel free to elaborate on how you would improve any of the following topics

- Code Structuring:

  - Adding Error handing code in order to different error which can encounter the system
  - Improving code Structure .

- Refactoring:

  - Make component for error text
  - Component for loader .

- Additional Features:
  - Using typescripts in order to Tightly couple everything with graph ql.
  - Adding unit testing for test case

### UI Result

- https://github.com/Mayank07-HP/github-topic-graphQl/blob/master/Screenshot%202022-08-20%20at%204.35.06%20PM.png
