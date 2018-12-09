# Senior React interview questions

## What we will cover

* Interview questions that I would ask a mid to senior level React developer

## Notes

Before we start it is important to note that interview questions for juniors and seniors have a different goal.

In the junior case we are interested in figuring out if there is a potential in the candidate to become productive and in the senior case we are looking for experience.

The following questions are aimed to figure out how much experience a candidate has and if they know what it means to work on big projects.

## Questions

* What tools suite do you use for your project and why?
  * Bad: "Parcel, NextJS and JS++"
  * Good: "Webpack, React router and TypeScript"

* What testing strategy do you use?
  * Bad: "I mostly do manual testing/TDD"
  * Good: "I use TDD for logic and automated UI tests for the rest"

* How do you handle component reuse?
  * Bad: "I always try to write generic components"
  * Good: "I refactor when I see duplication but some components are generic"

* When do you use server side rendering and why?
  * Bad: "I always use it because it speeds up the loading time"
  * Good: "I haven't used it because I don't work in Node"

* What tasks do you run and how?
  * Bad: "I mostly use Webpack loaders"
  * Good: "I try to use a task runner and Webpack for bundling"

* When do you use component based testing and why?
  * Bad: "I use Enzyme and I try to test all my components"
  * Good: "I use Enzyme but only for generic components since I use UI testing mostly"

* Do you use TDD and how?
  * Bad: "I use TDD as much as I can"
  * Good: "I find it hard to use TDD for components so I use it for logic"

* What state do you put where and why?
  * Bad: "I always put my state on the store"
  * Good: "I only put shared data on the store and private data on the state"

* Whats more important, clean code or good enough?
  * Bad: "Clean code"
  * Good: "I try to write clean code but sometimes I need to hack things together"

### The following questions will indicate how big the projects the candidate has been involved in are

* How do you handle bundling performance?
  * Bad: "What do you mean?"
  * Good: "There are loaders for it but mostly I try to reduce the bundling process"

* How do you handle multiple component variants in the same codebase?
  * Bad: "I try to refactor them in to generic components"
  * Good: "I raise awareness in the company and take action after that"

* How do you handle feature toggling?
  * Bad: "What do you mean?"
  * Good: "I use a config file or similar"

* How do you avoid component duplication?
  * Bad: "I write generic components and put them in Storybook"
  * Good: "It is hard to solve this so I talk to the teams and use good names"

* How do you handle A/B testing?
  * Bad: "What do you mean?"
  * Good: "I create a temporary component in isolation"

* How do you handle branding/themes?
  * Bad: "I use Material ui themes"
  * Good: "I try to avoid them / I use a variant prop in the components"

* How do you handle translations?
  * Bad: "I have never worked with them / we use translation files"
  * Good: "We get them from a external tool"
  