# javascript for architects
a guide to learning javascript and web development geared towards architects and designers.

## why javascript
Javascript is not likely anyone's first recommendation. It's an incredibly frustrating language to learn. There's a lot of answers that being with 'it depends...' However, javascript provides the unparalleled ability to design interactive experiences that can be delivered across any device. It's complexity, messiness, and internal disagreements is both a blessing and a curse. There's a wide variety of tools, frameworks, and philsophies to be found in the JS community, so while dauntingly large, gives you more ability to shape your javascript experience.

Personally, the beauty of javascript comes from its general lack of respect for a perscriptive way of doing things. The modern frameworks have well designed documentation and a very prolific tutorial community. Javascript's downfalls are mitigated by it's accessibility to end users. With some node module magic and and choice coding decisions, you can build accessible solutions at an incredible pace.

## how to use this guide

This guide is loosly structured by difficulty and then by topic. I'm no expert in javascript, so like any good yoga instructor would say, these are merely suggestions, never instructions... These are major resources and topics I felt in retrospect would be the most important things to go after if I were starting over. Think of this as a bookmarking page with descriptions

## where to start?

Picking a project is the best way to start. Since javacsript can be used almost anywhere, it's probably not too hard to find a project. Go with something small, using it for small scripting automations or build a single page local website. While learning to code, I feel it's better to pick something close to what you do on a day to day basis. This makes it easier to keep the project on your mind and go back to it.

[the codeburst map](https://codeburst.io/the-2018-web-developer-roadmap-826b1b806e8d) provides a good overview and pathway through the web developer landscape. CSS, HTML, and JS work in close cohort to produce the incredible web effects you witness in the browser. Here are some other avenues that I would suggest for beginners.

### Codeacademy

[intro-to-js](https://www.codecademy.com/learn/introduction-to-javascript)
Code academy's free courses is a great place to start. The excercises are short and can be done in the browser. Getting a good lay of the land in the back of your head is great when you start encountering roadblocks.

### Single Page HTML

[HTML](https://www.w3schools.com/htmL/)
[CSS](https://www.w3schools.com/css/default.asp)
[JS](http://javascript.info/)
Keeping it simple and going with vanilla JS/HTML/CSS is essential for understanding the basics of how they interact with each other. As complex as things can get, it should still boil down to the relationship between these three things.

### Google Apps Scripts

[guides and docs](https://developers.google.com/apps-script/overview)
A small bit of apps scripts goes a long way. Gsuite is a powerful toolset. Apps Scripts allows you to extend and connect that toolset with each other and other services. Building office automations and more readable spreadsheet formulas is a breeze. [This quickstart](https://developers.google.com/apps-script/quickstart/custom-functions) is a great starting point.
NOTE: APPS SCRIPTS IS USING ES2013 (more on this later)

## where to continue?

### Tools and Frameworks

#### Git and Github

[guides and docs](https://guides.github.com/)
git is essential to learn. learn it, practice it, use it, be happy.

#### Node, NPM, Yarn

[Node](https://nodejs.org/en/)

Node is instrumental in broading javascript's scope from manipulating the DOM into a dizzying array of applicable use cases. Working with node is a different (and arguably more fun). If you see a `package.json` then you know to 

[NPM](https://www.npmjs.com/) install - or -

Node Package Manager gives you a dizzying number of other people's awesome modules to play with. You'll be importing fun stuff in no time.

[Yarn](https://yarnpkg.com/en/)

Yarn is the result of a collaboration between some big tech companies as an alternative to NPM. It's got cool watercolor branding.

#### Eslint

[guide and docs](https://eslint.org/docs/user-guide/getting-started)

Eslint will be your pal. After being used to it's help, going without it feels cumbersome and lonely. (like Google Apps Scripts in the webIDE). I personally like the `airbnb` config. Following someone else's eslint config was really helpful through my learning, highlighting good practices and particularities I was not aware of.

#### Vue

What sets Vue apart from React and other front end frameworks is it's flexibility and gentle learning curve. I would advocate using vue over jQuery. Beyond simple drop-in use, Vue has an increasingly large and documented ecosystem of modules, component libraries, traspiliers, etc.

[vuejs](https://vuejs.org/)
[vuex](https://vuex.vuejs.org/)
[vue-router](https://router.vuejs.org/)

#### underscore/lodash/ramda

[underscore](https://underscorejs.org/)
[lodash](https://lodash.com/)
[ramda](https://ramdajs.com/)

These libraries assist a ton in composing code. You should never need all three, and each has a slightly different style in how they are used. Depending on you needs, you can write the utility functions you need in vanilla javascript, but where's the fun in that? Slapping one of these in and you're off to the races.

#### D3

D3 is a fair bit of black magic I don't understand. It's mostly used as a data visualization library, but as the website says "D3 allows you to bind arbitrary data to a DOM, then apply data-driven transformations to the document". D3 has a featureset that includes functionality you can get from jQuery, Vue, or the utility libraries, which sometimes makes mixing D3 with others a little wonky. D3 is powerful in it's ability to manipulate SVG and canvas, and provides great vector rendering capabilities.

[d3](https://d3js.org/)

#### Three

Click around on the demos and you'll see all the amazing things people have done with threejs. With capabilities for VR/AR and support for a wide array of 3D formats, this library can make your web dreams a digital reality.

[threejs](https://threejs.org/)

### Concepts and Good Reads



