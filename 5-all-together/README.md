# Battle Ship: Human vs Machine

You've made it!  Almost.   Before moving on you will review everything you've learned so far in this monster of a project.  Finishing this Battle Ship game won't be easy, so do yourself a favor and keep it as simple as possible.  Everytime you have two choices, choose the simplest. The main objective of this project isn't to build the best game ever, it's to practice breaking down large projects and to review the main learning objectives covered so far:
* User centered development 
* Project planning
* Algorithmic challenges
* Testing
* Reading and documenting code
* Separation of Concerns
* Organization and presentation of source code


This is by far the largest project you've made yet, but there is also nothing totally new.  As long as you take it slow, keep organized, and refer back to your old projects for guidance you will be fine.

Feel free to work alone or in small groups.

### Index
* [Learning Objectives](#learning-objectives)
* [Requirements](#requirements)
* [Resources](#resources)

---

## Learning Objectives

* Managing larger projects
* Tracking your development process
* User/Logic interactions
* Front -> Back development
* Flow charts

### Front -> Back development

Following this process will help you build what you intended to build, keep track of your progress, and reinforce 3 key skills:
* User focus development
* Feature-based development
* 3 layered architecture

Here's how it works:
1. Plan your development process and get your HTML/CSS prepared. (There is more information on these steps in the template repo):
    a. Select user stories (we've already done this for you)
    b. Analyze user story dependencies
    c. Choose a development schedule
    d. Build a wireframe
    e. Code the wireframe with simple HTML/CSS

2. Go through your development schedule one feature at a time.  For each feature you will complete these steps in this order:
    a. Make sure the HTML/CSS is in place to support this user story
    b. Write an event listener that gathers user input and updates the DOM
    c. Write specs and tests for this user story's logic
    d. Write the logic to pass those tests  (like a kata)
    e. Connect the logic to it's event listener
    f. Test the user story in the browser (by hand is fine)
    g. Document your new code
    h. Update your README
    i. Git tag, git push. (More on tags in Resources)
    j. Continue on to the next user story 



[TOP](#index)

---

## Requirements

We will provide you with puser stories and a finished repository structure.  A starting point and en ending point.  Your task is to go from point A to point B along the straightest and most organized path you can.


### User stories (in no particular order):
* A human can:
    * know when the game is over
    * see two empty boards
    * know who won
    * place a guess against the machine
    * know if their guess was a hit or a miss
    * place ships on their board
    * know when a single ship is sunk
    * hide ships and begin game
* The machine can:
    * place ships randomly on their board
    * fire randomly against the human
    * _challenges:_
        * place ships strategically
        * fire strategically
        * know if it hit or missed
        * mock the human
        




### Finished Repository

When you are finished you should have a beautifully organized repository with version tags that communicates your intentions, implementation, and how to use your application.  The finished directory structure will look like this:
```
Battle Ship Version Finished
├── README.md
|    * Overview of your project
|    * Link to live gh-pages demo
|    * How to play the game
|    * How to run the tests
|    * How the project is structured
├── index.html
├── /tests
|   ├── testing.html
|   ├── tests-logic-1.js
|   ├── tests-logic-...js
|   ├── tests-logic-x.js
|   └── tinytest.js
├── /public
|   ├── /js
|   |    ├── /version-1
|   |    |   ├── event-listeners.js
|   |    |   └── logic.js
|   |    └──/version-...
|   |        ├── event-listeners.js
|   |        └── logic.js
|   └── /styles
|       └── styles.css
├──  specs.md
|       * Complete specs for your JS, organized by version
├── dev-planning.md
|       * This wil be just like the README's from last project
└── ux-flow-chart
        * How a user interacts with your application over time
```

(You can see two examples here of well-organized repositories here - [Cleancalc](https://github.com/radovandelic/cleancalc), [Tictactoe](https://github.com/elewa-student/tic-tac-toe/tree/master). Both are great, but neither is exactly like yours should be.)

[TOP](#index)

---

## Resources

Agile Development:
* [12 Points](https://www.agilealliance.org/agile101/12-principles-behind-the-agile-manifesto/)
* [Agile Manifesto](http://agilemanifesto.org)

Flow Charting:
* [Overview & Vocab](https://uxplanet.org/ux-glossary-task-flows-user-flows-flowcharts-and-some-new-ish-stuff-2321044d837d)
* [Guide](https://www.startuprocket.com/articles/how-to-create-a-user-experience-flow-chart-ux-flow-chart)


Presenting your work:
* [Semantic Versioning](https://semver.org)
* [Git Tags](https://githowto.com/tagging_versions)
* [Releases on GitHub](https://help.github.com/articles/creating-releases/)
* [A Perfect Cleancalc Repo](https://github.com/radovandelic/cleancalc)
* [A Perfect Tictactoe Repo](https://github.com/elewa-student/tic-tac-toe/tree/master)



[TOP](#index)

---

## Challenge

A user can save their game:
* [cookie.js](https://github.com/florian/cookie.js)
* [strg.js](https://github.com/fend25/strg.js)
* [Local Storage](https://developer.chrome.com/apps/storage)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>

