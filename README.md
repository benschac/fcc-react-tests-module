# Free Code Camp React/Redux Challenge Development

### This repository contains the code for the Alpha version of the Free Code Camp React/Redux Curriculum Expansion.

### Overview:

* [**Link to the Challenges**](http://hysterical-amusement.surge.sh/)
* [**Link to Curriculum Map**](https://github.com/bonham000/fcc-react-tests-module/blob/master/CHALLENGE_MAP.md)
* **50 React Challenges, 18 Redux Challenges, 10 React-Redux Challenges**

The now [live Beta Version of Free Code Camp's expanded curriculum](http://beta.freecodecamp.com/en/) redirects campers to the link above while we work on merging these challenges into the FCC platform. Eventually the goal is for all of these challenges to be moved directly into the [FCC codebase](https://github.com/freeCodeCamp/freeCodeCamp).

**Currently, we have finished the initial QA and review of all of these challenges and are quite happy with them. There is still a possibility that there are bugs or typos we have not found yet. If you find something you think needs to be fixed, or have a suggestion for any of the challenges, please open an Issue here first so we can discuss it.**

---

To run this project locally, clone the repository, install the dependencies, and run `npm start`. Now you can view all the finished challenges live in the browser.

This project is running tests against React components, ES6 code, and plain JavaScript which users write directly into an in-browser code editor. To accomplish this we are using the [Babel standalone package](https://github.com/babel/babel-standalone) to transpile JavaScript and the testing library [Enzyme](http://airbnb.io/enzyme/) to conduct tests. At a basic level the tests we're writing for React components generally look like this:

```javascript
assert.strictEqual(shallowRender.type(), 'div', 'The component renders a div element');
```

***

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).
