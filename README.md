# No-Zero-Days / 100DaysOfCode #

The log of my progress inspired by #NoZeroDays challenge and #100DaysOfCode challenge. 

## Log

### Day 01 - 11.8.2018 (Sat) +
**Today´s Progress:** Continue working on my _Product Landing Page project_ from FCC - it´s css (nav-bar, background, text-colors, paddings, margins,...)

**Thoughts:** For not repeating background used "fixed". 

Can´t manage to center the text in "Tips". :-(

**Link:** [Product Landing Page](https://codepen.io/mmajam/full/PBBoeg)

### Day 02 - 12.8.2018 (Sun) +
**Today´s Progress:** Continue working on my _Product Landing Page project_ from FCC - responsivity (video, map), media queries. Finially finished it! ;-) 

**Thoughts:** ```<iframe>``` elements are not responsive, so we need to wrap them with an other element (```<div>```). (Web Design Blueprints - p.29)

**Link:** [Product Landing Page](https://codepen.io/mmajam/full/PBBoeg)

### Day 03 - 13.8.2018 (Mon) +
**Today´s Progress:** Began the project _Technical Documentation_ (basic html, basic structure)

**Link:** [Technical Documentation Page](https://codepen.io/mmajam/full/VBRyma/)

### Day 04 - 14.8.2018 (Tue) +
**Today´s Progress:** Went through materials to Gulp, NPM, SCSS. Done small responsive website using these. 

**Thoughts:** All those things are great!!!

### Day 05 - 15.8.2018 (Wed) +
**Today´s Progress:** Continue with the project _Technical Documentation Page_ (content, basic css)

**Link:** [Technical Documentation Page](https://codepen.io/mmajam/full/VBRyma/)

### Day 06 - 16.8.2018 (Thu) +
**Today´s Progress:** Finished the project _Technical Documentation Page_ (layout, media queries)

**Link:** [Technical Documentation Page](https://codepen.io/mmajam/full/VBRyma/)

### Day 07 - 17.8.2018 (Fri)
**Today´s Progress:** Read the documentation of _Bootstrap_ [(link)](https://getbootstrap.com/docs/4.1/getting-started/introduction/), which I want to use for my Personal Portfolio Page.

**Thoughts:** Flexbox-bugs: ```<button>``` and ```<fieldset>``` don´t work as flex-containers! (Solution: use ```<div>``` or other flex-supporting-element as immediate child of the ```<button>``` or ```<fieldset>``` (info: [Flexbugs](https://github.com/philipwalton/flexbugs#flexbug-9)).

### Day 08 - 18.8.2018 (Sat) +
**Today´s Progress:** Continue reading the documentation of Bootstrap [(link)](https://getbootstrap.com/docs/4.1/getting-started/introduction/). Done part of the Basic JavaScript Challenges from FCC. 

### Day 09 - 19.8.2018 (Sun) +
**Today´s Progress:** Finished _Basic JavaScript Challenges_ from FCC.

### Day 10 - 20.8.2018 (Mon) +
**Today´s Progress:** Did _ES6-JS Challenges_ from FCC

**Thoughts:** 

*Destructuring assignment to assign variables from objects* challenge - didn´t understand at first, but helped me especially explanation from randelldawson [here](https://forum.freecodecamp.org/t/es6-use-destructuring-assignment-to-assign-variables-from-objects-question/206730/6):  ```const { length : len } = str; ```  can be understood as ```const {objectPropertyName : newDelcaredVariableName } = object; ```

*IIFE (Immediately Invoked Function Expression)* - nice explanation [here](https://stackoverflow.com/questions/8228281/what-is-the-function-construct-in-javascript)

*Destructuring assignment to pass an object as a function´s parameters* - the explanation of alhazen1 [here](https://forum.freecodecamp.org/t/use-destructuring-assignment-to-pass-an-object-as-a-functions-parameters/194816/14) was nice: ```const person = {name:"Bob", age:23, occupation:"Defender of the Universe"};

// destructing assignment in function arguments
function whoIsThisDude({name,occupation:job}){
  console.log(`Hi! I'm ${name}. I'm a ${job}`);
}
whoIsThisDude(person);

// destructuring assignment inside function
function whoIsThisDude2(someDude){
  const {name, occupation:job} = someDude;
  console.log(`Hi! I'm ${name}. I'm a ${job}`);
}
whoIsThisDude2(person);```

and also explanation of vytautas-pilk was great: ```function half({min, max}) return (min + max) / 2.0;``` is the same as writing ```const {min, max} = stats;
console.log((min + max) / 2.0);```

### Day 11 - 21.8.2018 (Tue) +
**Today´s Progress:** Finished the section of _ES6 Challenges_ from FCC

**Thoughts:** 
*Use getters and setters to access to an object* challenge - for understanding helped explanation of JM-Mendez [here](https://forum.freecodecamp.org/t/es6-use-getters-and-setters-to-control-access-to-an-object/195489/11): 
```class SomeClass {
  constructor() {
      this.value = 'my initial value'
  }
  
  get value() {
      return this.value
  }
  
  set value(val) {
      this.value = val
   }
}
```
Then later you can use it like a regular object:

```console.log(SomeClass.value) // 'my initial value'
SomeClass.value = 'new value'
console.log(SomeClass.value)  // 'new value' 
```

If it was regular object, it would look like this:
```const SomeClass = {
   value: 'my initial value'
}

console.log(SomeClass.value) // 'my initial value'
SomeClass.value = 'new value'
console.log(SomeClass.value)  // 'new value'
```

### Day 12 - 22.8.2018 (Wed)
**Today´s Progress:** Started [CSS: The Complete Guide](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) course on Udemy. Had a meeting with an IT-professional to consult some techniques, practical uses,... - it boosted my eagerness for learning. 

### Day 13 - 23.8.2018 (Thu) +
**Today´s Progress:** Learned about the real project workflow on my in-person course (processes with npm, gulp, sass...) and how to create a collapsible menu using only css ([basics](https://css-tricks.com/the-checkbox-hack/)).

### Day 14 - 24.8.2018 (Fri)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/)

### Day 15 - 25.8.2018 (Sat)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Positioning.

**Thoughts:** 
*Percentages:* are related to "containing block" - it´s dependent on the position of our element (fixed: context is viewport / absolute: context is ancestor with position other than static (its content+padding) / relative: context is block-ancestor (only content)

### -- Day off - 26.8.2018 (Sun) --

### Day 16 - 27.8.2018 (Mon)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Background Images&Images, Sizes&Units

### Day 17 - 28.8.2018 (Tue)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part JavaScript&CSS

### Day 18 - 29.8.2018 (Wed)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _Responsive Web_

**Thoughts:** RWD - converting "hardware pixels" to "software pixels": ```<meta name="viewport" content="width=device-width, initial-scale=1.0">```

Conversion: 1 inch = 96px.

### Day 19 - 30.8.2018 (Thu) +
**Today´s Progress:** Practiced working with Git on my in-person course.

### Day 20 - 31.8.2018 (Fri)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Adding & Styling Forms.

**Thoughts:** *Outcome:* after border, not part of block-size. 

*Input, select:* They use default settings (e.g. font) of the browser. To change this and set it same as our "normally set" style, we must use ```font: inherit```. 

*:valid / :invalid pseudo-selectors:* can have other styling (e.g. ```.signup-form :invalid {....}```

*Disabled button:* Example styling: ```.button[disabled] {cursor: not-allowed; border: #a1a1a1; background: #ccc; color: #a1a1a1; }```

### Day 21 - 1.9.2018 (Sat)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Text & Fonts. 

**Thoughts:** For importing a font-family to our project it´s better to use @import directly to our .css file. (```@import url("https://fonts.googleapis.com/css?family=Roboto");```

### Day 22 - 2.9.2018 (Sun)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _Flexbox_. 

**Thoughts:** *Flex-basis:* if the ```flex-basis``` is set to ```auto``` and at the same moment the element´s ```width/height``` is set, the ```auto``` is used. If the ```flex-basis``` is set in ```px or %```, the ```width/height``` is overwritten by the ```flex-basis``` value.

### Day 23 - 3.9.2018 (Mon) +
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _CSS Grid_. Started the _Portfolio Page_. 

**Thoughts:** *CSS Grid:* used for 2-D positioning xxx *Flexbox:* used for 1-D positioning. 

*Wrapper of the whole content:* for better positioning of all elements use wrapper with ```min-height: 100%; position: relative;```. 

### Day 24 - 4.9.2018 (Tue) +
**Today´s Progress:** Worked on my _Portfolio Website_ (decided NOT to use Bootstrap) - header, welcome part.

### Day 25 - 5.9.2018 (Wed) +
**Today´s Progress:** Continue working on my _Portfolio Website_ - parts About me, Portfolio, Contacts, Footer (just the drafts).  Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part CSS Transforms. 

**Thoughts:** Source for CSS-3D-Transforms: [https://3dtransforms.desandro.com/](https://3dtransforms.desandro.com/)

### Day 26 - 6.9.2018 (Thu)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _Transitions, Animations_. Learned to work with _StyleLint_ and _Autoprefixer_ on my in-person course.

### Day 27 - 7.9.2018 (Fri)
**Today´s Progress:** Finished the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _Sass_.


### Day 28 - 8.9.2018 (Sat)
**Today´s Progress:** Started the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/).

### Day 29 - 9.9.2018 (Sun) 
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with section _JS Basics_.

### Day 30 - 10.9.2018 (Mon) 
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section _JS Basics_.

**Thoughts:**  *JS-Expressions:* pieces of code which always produce a value.   *JS-Statements:* they perform an action (they don´t produce immediate results).

### Day 31 - 11.9.2018 (Tue)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section _JS Behind The Scenes_.

**Thoughts:** 

*Hoisting of functions:* - works only with *function declarations*:
```calculateAge(1965);
function calculateAge(year) {console.log(2018-year); }     // =====> It works!
```
*Function expressions* are NOT hoisted!! It causes a TypeError!!!
```retirement(1996);
var retirement = function(year) {console.log(65-(2018-year));}     // =====> Causes a TypeError.
```

*Scope and **this**:* the default object of *regular functions* is the *window object* (so *this* points to the *window object*). It´s true even when the regular function is written inside of a method!!!! **this** in a *method of an object* refers to the *object* itself.

### Day 32 - 12.9.2018 (Wed)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section _JS DOM Manipulation and Events_.

### Day 33 - 13.9.2018 (Thu)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section _Advanced JS: Objects and Functions_.

### Day 34 - 14.9.2018 (Fri)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - First part of The _Budget App_ Project.

**Thoughts:** 

*Event Listener on the Enter keypress:*  
```
document.addEventListener("keypress", function(event) {
      if (event.keyCode === 13 || event.which === 13) {
      ctrlAddItem();
      }
   })
```

### Day 35 - 15.9.2018 (Sat)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with The Budget App Project.

**Thoughts:** 

*Changing two classes (represented by "DOMstrings.....") in the DOM:* 
```
var fields = document.querySelectorAll(DOMstring.inputDescription + ", " + DOMstrings.inputValue);
// This returns a List. To be able to use an Array-method on the List, we need to use the call method:
var fieldsArray = Array.prototype.slice.call(fields);
```

### Day 36 - 16.9.2018 (Sun)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with The Budget App Project.

**Thoughts:** 

*DOM Manipulation examples and explanation:* [blog.garstasio](https://blog.garstasio.com/you-dont-need-jquery/)

*Splice x slice:* ```splice``` - used to remove elements (from what index, how many) x ```slice``` - used to create a copy

*Event bubbling, event delegation:* used in 2 cases: 1. When we have an element with lots of child elements that we are interested in; 2. When we want an event handler attached to an element that is not yet in the DOM when our page is loaded.

### Day 37 - 17.9.2018 (Mon)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished The _Budget App_ Project section.

**Thoughts:** 

*Map method:* returns something and stores it in a variable. *ForEach method:* only loops through the array and does something with it (but doesn´t return anything)

### Day 38 - 18.9.2018 (Tue)
**Today´s Progress:** Revised the _Budget App_ Project in detail. 

### Day 39 - 19.9.2018 (Wed) +
**Today´s Progress:** Added responsivity to my previous projects at FCC: [Tribute page](https://codepen.io/mmajam/full/xJPeXq/), [Build a Survey Form](https://codepen.io/mmajam/full/QBxyBQ/), [Product Landing Page](https://codepen.io/mmajam/full/PBBoeg/), [Technical Documentation Page](https://codepen.io/mmajam/full/VBRyma/). 

**Thoughts:** I see that I moved forward a lot in one month - when I looked at those project, I can see my not-so-good-solutions, I would do these better now. First I thought that I will re-do them, but then I decided not to do so now, but to continue with other things instead - future projects will be better (as I hope). :-D

### Day 40 - 20.9.2018 (Thu) +
**Today´s Progress:** Went back to the [Portfolio Website projects](https://codepen.io/mmajam/full/BOyNdN/) (until Day25 I did draft of parts About me, Portfolio, Contacts, Footer) and did small changes regarding things I learned in the meantime. Learned about the Keep-Aspect-Ratio for photogallery (resources: [Aspect Ratio Boxes - CSS-Tricks](https://css-tricks.com/aspect-ratio-boxes/), [Keith Grant´s explanation](https://keithjgrant.com/posts/2017/03/aspect-ratios/) and [MadeMyDay.de examples and explanation](http://www.mademyday.de/css-height-equals-width-with-pure-css.html).

### Day 41 - 21.9.2018 (Fri) +
**Today´s Progress:** Finished my [Portfolio Website project](https://codepen.io/mmajam/full/BOyNdN/). 

**Thoughts:** Struggled with implementing of the toggle-menu for mobile-version (used the solution from [codeburst](https://codeburst.io/how-to-make-a-collapsible-menu-using-only-css-a1cd805b1390)). 

### Day 42 - 22.9.2018 (Sat) +
**Today´s Progress:** Fixed some bugs on mobile-version of my [Portfolio Website project](https://codepen.io/mmajam/full/BOyNdN/). Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Part of the _ES6/ES2015_ section. 

**Thoughts:** 

Variables declared with ```var``` are *function-scoped*. Variables declared with ```let``` or ```const``` are *block-scoped*.

*Template literals:* to use them, we must use backticks (not single/double quotes)!

### Day 43 - 23.9.2018 (Sun)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - ES6/ES2015 section (arrow functions, destructuring, spread operator, rest parameters, maps.

### Day 44 - 24.9.2018 (Mon)
**Today´s Progress:** Finished the section _ES6/ES2015_ of the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - classes + subclasses. Did the final challenge (trees/streets).

### Day 45 - 25.9.2018 (Tue)
**Today´s Progress:** Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - section _Asynchronous JavaScript_ (Event loop, Promises, Async/await). 

### Day 46 - 26.9.2018 (Wed)
**Today´s Progress:** Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - finished section _Asynchronous JavaScript_ (Fetch), started section _Modern JavaScript_ (node.js, webpack - installing and configuring (webpack, webpack-cli, webpack-dev-server, html-webpack-plugin). 

**Thoughts:** I find the shown processes similar to those which we used in my in-person course with Gulp (at least for this moment; I look forward for learning more and for working with it!

### Day 47 - 27.9.2018 (Thu)
**Today´s Progress:**  Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - installing and configuring _Babel_. Started the final project "Forkify" (planning using MVC architecture, modules).

### Day 48 - 28.9.2018 (Fri)
**Today´s Progress:**  Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with "Forkify" project (start working with API, installing Axios)

### Day 49 - 29.9.2018 (Sat)
**Today´s Progress:** Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with "Forkify" project (working on the Search model, Search controller)

### Day 50 - 30.9.2018 (Sun)
**Today´s Progress:** Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with _"Forkify" project_ (part Search view, loading spinner)

### Day 51 - 1.10.2018 (Mon)
**Today´s Progress:**  Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with _"Forkify" project_ (part Recipe model, Recipe controller)

**Thoughts:** I came across the book _Maintainable JavaScript_ by Nicholas C. Zakas several days ago and I am reading it in free moments during the day. The concepts there are exactly those which used Maximilian in his projects (the CSS course on Udemy, which I took recently). I really like it! (I wish I had more time for coding and learning!)

### Day 52 - 2.10.2018 (Tue)
**Today´s Progress:**  Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with _"Forkify" project_ (changing the amount of servings and ingredients)

**Thoughts:** I look forward to my own programming! But I decided to finish the JS-course first (hopefully tomorrow) and than I´ll continue with the projects of FCC. 

### Day 53 - 3.10.2018 (Wed) +
**Today´s Progress:**  Finished the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/). Did the challenges on _Regular Expressions_ at FCC. 

**Thoughts:** _LocalStorage API:_ stores only strings (To store data: ```localStorage.setItem("likes", JSON.strigify(this.likes));```, to get back data: ```const storage = JSON.parse(localStorage.getItem("likes"));``` 

### Day 54 - 4.10.2018 (Thu) +
**Today´s Progress:** Did the challenges on _Debugging_ at FCC, began the challenges on _Basic Data Structures_ at FCC (processing of arrays).

**Thoughts:** _Greedy matching (default):_ on string "titanic" matches "titani" using ```/t[a-z]*i/```. 
_Lazy matching:_ on string "titanic" matches "ti" using ```/t[a-z]*?i/```

### Day 55 - 5.10.2018 (Fri) +
**Today´s Progress:** Did the challenges on _Object Oriented JavaScript_ at FCC.

**Thoughts:** If we set a prototype of an object, we must set also its constructor (otherwise is undefined!) - 
```
Bird.prototype = {
  constructor: Bird,
  numLegs: 4,
  eat: function() {
    console.log("nom nom")
  }
};
```

### Day 56 - 6.10.2018 (Sat) +
**Today´s Progress:** Did the challenges on _Functional Programming in JavaScript_ at FCC.

**Thoughts:** When we don´t know all the arguments at once:
```
function impartial(x,y,z) {
   return x + y + z;
}

var partialFn = impartial.bind(this, 1, 2);

partialFn(10);    => 13
```

### Day 57 - 7.10.2018 (Sun)
**Today´s Progress:** I want to get the overview of the connection between front-end, back-end, databases, and so on. So I bought the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). Since the first parts are just repeating, I went through these quickly: today I did the sections _How the Internet Works, History of Web, HTML, CSS_. 

**Thoughts:** Some resources: https://unsplash.com/ (free images), http://paletton.com/ (color palette), https://css-tricks.com/ (overview of css properties and values), https://specificity.keegan.st/ (specificity calculator), https://robots.thoughtbot.com/transitions-and-transforms (transitions and transforms overview), https://philipwalton.github.io/solved-by-flexbox/ and www.flexboxpatterns.com/ (flexbox).

Resources for the course: https://zero-to-mastery.github.io/resources/, and one other: https://github.com/zero-to-mastery/complete-web-developer-manual

### Day 58 - 8.10.2018 (Mon)
**Today´s Progress:** I went through the parts _Bootstrap, Career of Web Dev., JavaScript_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** Resources: https://mailchimp.com/ (email marketing and similar), animate.css (animating of elements), templates of websites (www.creative-tim.com, https://mdbootstrap.com/freebies/ (!!!), http://www.mashup-template.com/templates.html, https://startbootstrap.com/template-categories/all/).

### Day 59 - 9.10.2018 (Tue)
**Today´s Progress:** I went through the parts _DOM Manipulation, Advanced JS_ (part) of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** _Conversion of ES6_ to ES5 (online): https://babeljs.io/repl/

_Currying:_ 
```
const multiply = (a,b) => a * b;
const curriedMultiply = (a) => (b) => a*b;
const multiplyBy5 = curriedMultiply(5);
```

_Compose:_
```
const compose = (f,g) => (a) => f(g(a));
const sum = (num) => num + 1;
compose(sum,sum)(5);     =====> 7
```

### Day 60 - 10.10.2018 (Wed)
**Today´s Progress:** I continued with sections _Advanced JS_ (second part - reduce, classes, ES7, ES8, Asynchronous JS), Command Line, Dev.-Environment of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** Some links: [You don´t know JS](https://github.com/getify/You-Dont-Know-JS), [javascript.info](http://javascript.info/), [JavaScript: The Core, 2nd Ed.](http://dmitrysoshnikov.com/ecmascript/javascript-the-core-2nd-edition/), [How To Think Like A Programmer](https://medium.freecodecamp.org/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2), [ES Modules: A cartoon deep dive](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/).

### Day 61 - 11.10.2018 (Thu)
**Today´s Progress:** I continued with the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/) - sections _Git and GitHub, A day of a Web Developer, NPM_. 

**Thoughts:** Some useful links: Commands for Cmd for Windows (https://www.thomas-krenn.com/en/wiki/Cmd_commands_under_Windows). Some useful _npm packages:_ live-server, lodash. 

Check _A developer´s morning routine_ (in the section A day of Web-Dev.)!!!! Good tips!!!

### Day 62 - 12.10.2018 (Fri)
**Today´s Progress:** I started the section _React.js_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). Began with the React application "Robofriends".

**Thoughts:** I´m totally excited about React! :D

### Day 63 - 13.10.2018 (Sat)
**Today´s Progress:** I continued with the section _React.js_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). Began the part of Redux and applied some of the principles to "RoboFriends" app. 

### Day 64 - 14.10.2018 (Sun)
**Today´s Progress:** I finished the section _React.js + Redux_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** I got lost in the Redux part. :( I´ll go back later to this part (or perhaps read/watch more about Redux from other sources too and then come back). 

### Day 65 - 15.10.2018 (Mon)
**Today´s Progress:** I did the section _HTTP / JSON / AJAX / Asynchronous JS_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** I like Promises more than Async-Await. 

### Day 66 - 16.10.2018 (Tue)
**Today´s Progress:** I did the sections _Backend Basics and APIs_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** Sources for various APIs: https://apilist.fun/ 

### Day 67 - 17.10.2018 (Wed)
**Today´s Progress:** I started the main project (code-along) _Face Recognition App_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/) - setting the parts using React.

**Thoughts:** I like React. ;-) Some other useful resources: _tilt.js_ (```npm install --save react-tilt```), _particles.js_ (```npm install react-particles-js```). 

### Day 68 - 18.10.2018 (Thu)
**Today´s Progress:** I finished the front-end part (coded along) of the main project _Face Recognition App_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** Interesting API (recognition of faces, colors, things,...): https://clarifai.com/

### Day 69 - 19.10.2018 (Fri)
**Today´s Progress:** I started the part _Node.js & Express.js_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

### Day 70 - 20.10.2018 (Sat)
**Today´s Progress:** Today I coudn´t do anything on my PC, so instead I started reading the book _The Road To Learn React_ by Robin Wieruch. I find it great in connection to the topic of the course Complete Web Dev...

### -- Day off - 21.10.2018 (Sun) --

### Day 71 - 22.10.2018 (Mon)
**Today´s Progress:** I finished the part _Node.js & Express.js_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). Challenge Santa´s node helper ([puzzle](https://adventofcode.com/2015/day/1)). 

**Thoughts:** Nice [article](https://medium.freecodecamp.org/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2) about _problem solving._ 

### Day 72 - 23.10.2018 (Tue)
**Today´s Progress:** I started the back-end (server) part of the main project _Face Recognition App_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** _Postman:_ (www.getpostman.com) - great for testing my server before I connect it to the front-end. 

_Body-parser:_ used for accessing the body of the request (```npm install body-parser```).

_Timer:_ For testing how long did some task take: ```console.time("myTask");``` on the beginning, and then ```console.timeEnd("myTask");``` on the end.

### Day 73 - 24.10.2018 (Wed)
**Today´s Progress:** I did the section _Databases_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** I already learned about databases before (CodeCademy and two one-day in-person courses), but now (with this course) it goes sooo clearly together with the other parts as a puzzle! I really missed this junction!! 

_Training the database-commands:_ https://www.khanacademy.org/computing/computer-programming/sql

### Day 74 - 25.10.2018 (Thu)
**Today´s Progress:** I went through the section about _Production & Deployment_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** The course was great! I really like the way, how all the pieces click together! Now I look forward to my own code! My plan is to use plain HTML/CSS/JavaScript first, and after some time to study React in more detail and use this. 

Some resources: [Environment Variables in windows](http://www.dowdandassociates.com/blog/content/howto-set-an-environment-variable-in-windows-command-line-and-registry/), [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)...

 ### Day 75 - 26.10.2018 (Fri) +
**Today´s Progress:** I made a wireframe for a small app for showing only selected videos suitable for kids. Made the basic structure.

**Thoughts:** When starting from scratch, I´m really very unsure and forgot so much things which I already knew before! I´m totally demotivated. :-( 

### -- Day off - 27.10.2018 (Sat) --

 ### Day 76 - 28.10.2018 (Sun) +
**Today´s Progress:** I started re-building of the main page of the uHost (project from the CSS-course, which I did earlier) just according the result html-page. 

**Thoughts:** The start was not easy, but as I went further, it was much better. ;-)

### Day 77 - 29.10.2018 (Mon) +
**Today´s Progress:** I continued with re-building of the main page of the uHost (project from the CSS-course, which I did earlier) just according the result html-page. Got stuck at mobile-version. :-/

### Day 78 - 30.10.2018 (Tue) +
**Today´s Progress:** I continued with re-building of the uHost website - the Package-page. 

### Day 79 - 31.10.2018 (Wed) +
**Today´s Progress:** I re-builded the Customers-page of the uHost website. 

### Day 80 - 1.11.2018 (Thu) +
**Today´s Progress:** I continued with re-building of the uHost website. I rewatched some parts of the CSS-course. 

### Day 81 - 2.11.2018 (Fri) +
**Today´s Progress:** I continued with re-building of the uHost website. I repeated some parts of the CSS-course. 

### Day 82 - 3.11.2018 (Sat)
**Today´s Progress:** I went again through the positioning- and background-topics of the CSS-Course on Udemy. 

**Thoughts:** If an img is inside of an _inline element_: it´s 100%-width refers to the 100%-width of the image itself. I an img is inside of an _inline-block element_: it´s 100%-width-size refers to the size of the surrounding element. 

### Day 83 - 4.11.2018 (Sun)
**Today´s Progress:** I went again through the Sizes & Dimensions-topics of the CSS-Course on Udemy. 

### Day 84 - 5.11.2018 (Mon) +
**Today´s Progress:** I started again from the beginning (just with html-template) with re-creating the main page of the uHost (from the CSS-course).

**Thoughts:** It´s much better now after revising some parts of the course! I achieve the output using different features in the css than they did in the course, but I´m happy about having solved it! However, I have to solve some minor issues and improve responsivity.

### Day 85 - 6.11.2018 (Tue) +
**Today´s Progress:** I continued with re-creating the customer-page and plan-page of the uHost (from the CSS-course).

**Thoughts:** I´m excited, that I make progress with the site really much better now! Last week the stuff I wrote didn´t work and I felt deprived, but now after refreshing the material from the course it´s much more easy!!! I like this CSS-course because Max mentions there various dependencies and under which conditions a feature doesn´t work. It´s really useful!

### Day 86 - 7.11.2018 (Wed) +
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course).

### Day 87 - 8.11.2018 (Thu) +
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course) - changed the units to responsive ones (rem, %), did the Start-Hosting-page.

**Thoughts:** I didn´t succeed with designing the hamburger-menu using css. :-( I will come to it tomorrow again. 

### Day 88 - 9.11.2018 (Fri) +
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course) - styled the modal, backdrop, added eventListeners  to the buttons on the main-page. 

### -- Day off - 10.11.2018 (Sat) --

### Day 89 - 11.11.2018 (Sun) +
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course) - added mobile-nav-menu, improving responsivity.

### Day 90 - 12.11.2018 (Mon) +
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course) - eventListeners, added responsivity.

### Day 91 - 13.11.2018 (Tue)
**Today´s Progress:** I wanted to learn more about transforms and animations, so I started the course which I bought already more than month ago at Udemy - [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/).

**Thoughts:** __Clip-path:__ for clipping background or image to different shapes (using polygon() ). __Centering:__ Using ```position: absolute; top: 50%; left: 50%;``` (% is relative to the positioned ancestor) in combination with ```transform: translate(-50%, -50%);``` (% is relative to the element itself).

### Day 92 - 14.11.2018 (Wed)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - using ```::after``` pseudoclass, using _animation_, _transition_, _transform (translate, scale)_.

**Thoughts:** I don´t do the code-along, but instead I watch the whole video on a topic first and after finishing it I try to re-do it (so that I must try to remember and recall the things from the video). I find this approach much better! 

### Day 93 - 15.11.2018 (Thu)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - section How CSS Works: A Look Behind The Scenes. 

**Thoughts:** 
_percentage of lengths:_ (height/padding/margin/... expressed in %) - the reference is always the parent-element´s _width_!!!

_em for fonts:_ the reference is the parent-element font-size. _em for lengths:_ the reference is the current element´s computed font-size!

_Inheritance:_ Inherited are the _computed values_ in px (not the declared values - e.g. in %)!

### Day 94 - 16.11.2018 (Fri)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - started with Sass / SCSS, auto-compiling and auto-reload of the page. Created _fluid-grid_. Began using _Emmet_. Learned about _utility-classes_ and started using them in the project.

**Thoughts:** _auto-compiling:_ used node-sass together with nodemon, for _auto-reload:_ used live-server.

### Day 95 - 17.11.2018 (Sat)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - created another section (with images reacting on hover).

**Thoughts:** _Line around an image:_ using _outline_: ```outline: 1rem solid rgb(0,0,0,);``` on element:hover; and ```outline-offset: 1rem;``` on element itself. 

_Icons:_ [linea.io](linea.io) - for downloading and free to use.

_Skew the background-image:_ use ```transform: skew(-7deg);``` on the section; and ```transform: skew(7deg);``` on all the section´s direct children (using ```>```). 

### Day 96 - 18.11.2018 (Sun)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - beginning creating another section (with cards flipping on hover).

**Thoughts:** When I make all element´s children to ```position: absolute;```, the element itself collapses (as with floats) => We must set the same height to element itself and to the child.

_linear-gradient:_ works with ```background-image:....``` (not ```background-color```!!)

_perspective:_ when higher numbers (as 150rem) - looks more natural as flipping. For mozzilla needed the prefix! (```-moz-perspective:...```)

### Day 97 - 19.11.2018 (Mon)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - finished the section from yesterday, made the section Stories. Used ```background-blend-mode, box-decoration-break, shape-outside, filter, object-fit...```

**Thoughts:** 

_Background-blend-mode: screen;_ - used for adjusting the colors/hues of an image (adjusting the color to a specific color). (Not supported in some browsers!)

_Box-decoration-break: clone;_ - used for maintaining of the padding even after splitting of the row.

_Flexible images in responsive web sites:_ must have always specified _width_!

_Shape-outside: circle(50% at 50% 50%);_ - surrounding text is in the shape of the circle (the element must be floated and must have specified width and height!)

_Video in the background:_ for fitting: ```height: 100%; width: 100%; object-fit: cover;```

### Day 98 - 20.11.2018 (Tue)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - made the form-section. Used solid-color gradients, general ```~``` and adjacent ```+``` sibling selectors, ```:invalid, :focus, :checked```.

**Thoughts:**

_Radiobuttons:_ To be considered as the same group, the input must have the same ```name="..."``` attribute. Radiobuttons can´t be styled in CSS - we must build our own instead (and the original make ```display: none;```.

_Forms:_ We must use ```button``` (not the ```a```) - because the form understands the button as the submit. 

_Button:_ By default have a border. They have ```focus``` - we can remove this by adding ```outline: none;``` to the ```button:focus``` (but there must be some other way how it´s clear that it´s active!).

### Day 99 - 21.11.2018 (Wed)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - Finished the section Natours-project: Using advanced CSS and Sass. Learned how to use _checkbox-hack_ and _popup-window_. Using ```radial-gradient, :target, display: table-cell, column-count, hyphens```.

**Thoughts:**

_cubic-bezier helping-tools:_ cubic-bezier.com, easings.net

### Day 100 - 22.11.2018 (Thu)
**Today´s Progress:** I finished the Natours project in the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) (last sections: _Responsive Web.-Design_ (esp. _responsive images_), _Browser-support, npm_ and _automation._ Used ```backdrop-filter, ::selection,...```

**Thoughts:** _To influence only touch-devices + mobile-phones:_ ```
@media only screen and (max-width: 56.25em),
       only screen and (hover: none) {........}```


### **********************************************************************
### ******************* !!! WOWWW !!!  It´s Day 100!!! *******************

**Let´s sum up:** During those 100 days I did some coding or I learned some new stuff (approximately 3 hours a day - sometimes just 1-2 hours, sometimes 5-6 hours, as much as was possible). I missed just 4 days (after days 15, 70, 75, 88 - but of course I didn´t count those skipped days, so it took me 4-days longer than planned.)

**I feel much more confident in:** _CSS, Sass (SCSS), Responsive websites, JavaScript, Command-line, Git, npm, connection of the page with a database,..._

**My plans:** 
// - Create a website (using BEM, Sass, Resp. design,...). -
// - Recreate my projects at FCC. -
// - Participate in the monthly-challenges of Zero-To-Mastery. -
// - Contribute to non-profit (probably through Zero-To-Mastery). -
// - Push my projects to GitHub (or elsewhere). -
// - Learn React in more detail. -
// - Learn Node.js in more detail. -

### ********************************************************************** 


### Day 101 - 23.11.2018 (Fri) +
**Today´s Progress:** I started a new project _Quotes For Every Day_ (functionally similar to the one at FCC, which I did more than 1 year ago).  I decided to use Sass+BEM, so I did the basic setup for the project. I used the command line for creating the project folders/files. 

**Thoughts:** For creating a new file in Git Bash (in Windows): ```> base.scss```.

### Day 102 - 24.11.2018 (Sat) +
**Today´s Progress:** I continued with the project _Quotes For Every Day_ - finished the layout, added responsivity. 

**Thoughts:** I had problem animating the button (releasing the pressed button) - it helped to make it an ```a``` element (instead of ```button``` element). 
Again, I have a problem with positioning the footer - so that it sticks to the bottom of the viewport if there is not enough content, but when making the viewport smaller (and so the content can´t fit to the viewport anymore), I want the footer to be completely at the bottom.  I know that I can solve it using flexbox, but I wanted to try some other solution. 

### Day 103 - 25.11.2018 (Sun) +
**Today´s Progress:** I finished the project _Quotes For Every Day_ (except JS which I want to do later). I searched and tried several solutions for the footer-issue, but I wasn´t really satisfied with any of them (I wanted to have it really responsive - without fixed height of the footer), so I finally decided to use flexbox for it. ;-)

### Day 104 - 26.11.2018 (Mon) +
**Today´s Progress:** I did some improvements in the project _Quotes For Every Day_. I started a new project (similar to the one which I did more than 1 year ago as a FCC project) - Local Weather App. I did the setup and basic layout of the project. I want some refresher about the details regarding Flexbox, so I started the Flexbox-section in the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/). 

### Day 105 - 27.11.2018 (Tue)
**Today´s Progress:** I continued with the Flexbox-section in the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/). Learned about _CSS variables_, using _SVG icons_ and using ```fill: currentElement;``` to change the color to the same as the parent, and about changing the color/font-weight/... of the _placeholder text_ (using ```&::-webkit-input-placeholder { ..... };```

### Day 106 - 28.11.2018 (Wed)
**Today´s Progress:** I finished the Flexbox-section (Trillo project) in the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/). Learned how to put _SVG into CSS_ and how to change its color using ```mask-image```, how to do an _infinite animation_, _multicolumn list_,... and added responsivity to the whole project using @media queries.

**Thoughts:** To find all the _npm packages which are installed globally:_ ``` npm list -g --depth 0```

### Day 107 - 29.11.2018 (Thu)
**Today´s Progress:** I revised the new features of JavaScript - I went through my notes and some parts of [The Complete JavaScript Course](https://www.udemy.com/the-complete-javascript-course/), and then I did the section A Quick Refresher: JavaScript in the [Node.js: the Complete Guide course](https://www.udemy.com/nodejs-the-complete-guide/).

**Thoughts:** I understood better the _arrow functions_, _spread_ and _rest operator_, _destructuring_ and _asynchronous JS (promises)_.

### Day 108 - 30.11.2018 (Fri) +
**Today´s Progress:** I added the JavaScript functionality to the project _Quotes For Every Day_ - display a random quote from API (used _async JS - fetch_) after pressing the new-button,  _tweet the quote_ after pressing the tweet-button.

**Thoughts:** I´m excited that I was able to do it quite quickly and it works as intended! I like the ES6 syntax! 

### -- Day off - 1.12.2018 (Sat) --

### Day 109 - 2.12.2018 (Sun)
**Today´s Progress:** I did the _Node.js Crash Course_ at the [The Complete JavaScript Course](https://www.udemy.com/the-complete-javascript-course/) - I learned more about _Node.js_, _server creating_, _routing_, and creating _HTML using templates_. 

### Day 110 - 3.12.2018 (Mon)
**Today´s Progress:** I learned about the _Basics of Node.js_ at the course Node.js: The Complete Guide. (In more detail: _Starting a server, routing, redirecting,..._

### Day 111 - 4.12.2018 (Tue)
**Today´s Progress:** I did the challenge of the _Node.js_ course, Section Basics of Node.js - I started my own server and processed two scenarios/routings. I learned about _reading and writing files_ in an app using Node.js.

### Day 112 - 5.12.2018 (Wed) +
**Today´s Progress:** I learned using the _Express.js_ in the course Node.js: _adding middleware, routing, creating and serving html files, serving files statically._ I did the challenge No2 - create an app with two routes and serving a file statically. 


### Day 113 - 6.12.2018 (Thu) +
**Today´s Progress:** I learned about _adding dynamic content_ and using _templating engines: EJS, Pug, Handlebars_ (with EJS I worked more). Learned how to _loop in ejs_, how to use _partials/include_ in ejs and using _conditional adding of a class to an element_.

**Today´s Progress:** I got stuck with the challenge - I need more practice... I wish I had more time to learn and practice during the day! :-(

### Day 114 - 7.12.2018 (Fri) +
**Today´s Progress:** I did the challenge from yesterday - I feel I understand more of the topic now! I learned about using _MVC_ (_modules-views-controls_). Also, I learned how to _load data from a file_ and _save data to a file_. 

### Day 115 - 8.12.2018 (Sat)
**Today´s Progress:** I finished the section _Dynamic Routes & Advanced Models_ of the _Node.js_ course. Learned how to use _dynamic parameters_ (using _:name_ -  ```router.get("/products/:productId");```, extracting it using _req.params_ - ```const prodId = req.params.productId;``` ). Read [The Node.js Handbook](https://nodehandbook.com/) for better understanding. Read the documentation about [Express Routing](https://expressjs.com/en/guide/routing.html) and [Using Express Middleware](https://expressjs.com/en/guide/using-middleware.html).

### Day 116 - 9.12.2018 (Sun)
**Today´s Progress:** I started the section about _Databases (SQL and NoSQL)_ of the Node.js course. I spent a long time trying to install the [MySQL](https://www.mysql.com/) on my Windows 7 PC, googled various advice but didn´t succeed. So I tried installing it on the other PC with _Linux_ Mint, which is not supported by the installations, I was partly successful, but got stuck again after starting it. :-( I´m disappointed that after so much time spent I don´t have the things working, but I try to take from it the better part - I _learned to use linux_ a bit. :-D 

### Day 117 - 10.12.2018 (Mon)
**Today´s Progress:** Today I couldn´t be at my computer, so I started reading a book _Web Development with Node & Express_ (by Ethan Brown) - It´s great for further explaining the stuff from the Node.js-course! 

### -- Day off - 11.12.2018 (Tue) --

### Day 118 - 12.12.2018 (Wed)
**Today´s Progress:** I was successful with solving all the problems regarding non-functioning MySQL (on my Windows PC) and I continued with the section on _MySQL_ of the Node.js course. 

### Day 119 - 13.12.2018 (Thu)
**Today´s Progress:** I continued working with the _MySQL database_ using sql-queries (now my previous knowledge from the SQL courses and workshops are great!). I started the section about _Sequelize_ at the Node.js course. 

### Day 120 - 14.12.2018 (Fri)
**Today´s Progress:** I continued with _Sequelize_: how to connect Sequelize with MySQL, how to create new table through Sequelize, use the table...

**Thoughts:** I think I´m doing only small progress, I´m learning and improving so slowly! I wish I had more time to learn and code!!! :-/

### Day 121 - 15.12.2018 (Sat)
**Today´s Progress:** I finished the section about _MySQL_ and _Sequelize_: how to create new items in tables, delete the items, how to create connections (associations) between tables.

**Thoughts:** Now it seems everything clear, but I must practice it on my own project (and then use especially the [Sequelize-docs](http://docs.sequelizejs.com).

### Day 122 - 16.12.2018 (Sun)
**Today´s Progress:** Today I had less time to code/learn. :-( However, I learned at least the basics about _MongoDB_ and its settings. Also, I continued reading the book _Web Development with Node & Express_.

### Day 123 - 17.12.2018 (Mon)
**Today´s Progress:** I continued working with _MongoDB_ (at Node.js course).

### Day 124 - 18.12.2018 (Tue)
**Today´s Progress:** I learned in more detail about _Asynchronous Requests_, _REST APIs_, _CORS errors_ and its server-side solution, and _Async Await_. 

### Day 125 - 19.12.2018 (Wed)
**Today´s Progress:** I learned about _Sessions_ and _Cookies_. I learned in more detail about _CSS Grid_ (The first part of the CSS-Grid in the Advanced CSS course).

### Day 126 - 20.12.2018 (Thu)
**Today´s Progress:** I continued with the _CSS Grid_ - it´s usage in practice (nested CSS-grids, combination of css-grids and flexbox,...).

### Day 127 - 21.12.2018 (Fri)
**Today´s Progress:** I finished the _CSS Grid_ part of the Advanced CSS and Sass course on Udemy. I learned basics about _Web Design_ (quick course Web Design for Web Developers: Build Beautiful Websites - on Udemy).

### Day 128 - 22.12.2018 (Sat) +
**Today´s Progress:** I did the CSS of my Weather-App project. 

### Day 129 - 23.12.2018 (Sun) +
**Today´s Progress:** I worked on the functionality of the Weather-App (JavaScript part).

### -- Day off - 24.12.2018 (Mon) --

### Day 130 - 25.12.2018 (Tue) +
**Today´s Progress:** I continued on working on my _Weather-App_ (getting the weather-info from the openweatherma API). Read through my notes about JavaScript. 

### Day 131 - 26.12.2018 (Wed) +
**Today´s Progress:** Working on my _Weather-App_ (added finding the position using http://ip-api.com). Came to a problem with fetch-then-catch, so I searched for more detailed info about this topic).

**Thoughts:** Should I use _fetch()_? Its support is about only 87% now. Its use seems to be easy, but there are some "problems" and when we consider these, it´s not so straightforward. (Described in ([Why I still use XHR instead of the Fetch API](https://gomakethings.com/why-i-still-use-xhr-instead-of-the-fetch-api/) and in [Using Fetch (on CSS-Tricks)](https://css-tricks.com/using-fetch/). Summary also here: [Understand Fetch API](https://flaviocopes.com/fetch-api/).

Great for trying projects with fake _REST API _: https://jsonplaceholder.typicode.com/ 

### Day 132 - 27.12.2018 (Thu)
**Today´s Progress:** I would like to use the API in "nicer" way, use _axios_ (instead of pure fetch) and use the MVC for my Weather-App, but because I´m not sure how to implement it, so I revised the final section of the Complete JavaScript course (forkify project), where all these were used.

### Day 133 - 28.12.2018 (Fri)
**Today´s Progress:** I revised the parts of the forkify-project (how the state is stored, how a controllers and views are implemented in practice). 

### Day 134 - 29.12.2018 (Sat) +
**Today´s Progress:** I´m going to create my own app: _Plan-App_. I did planning of the parts, functionalities and connections (on paper), and then I did the setup of the whole folder, installed the npm-packages (babel,..., node-sass, nodemon, webpack...). I would like to use MVC architecture (so I want to use webpack for bundling) and I´d like to use Sass (using node-sass for compiling). I tested the setting and there is some bug - the compilation of scss to sass doesn´t work. :-(

### Day 135 - 30.12.2018 (Sun) +
**Today´s Progress:** I read more about _Webpack_ and its setting, and also about using it together with _Sass_. [This article about Webpack 4 setting at hackernoon](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1) helped a lot: Finally the whole setting works! 

### -- Day off - 31.12.2018 (Mon) --

### -- Day off - 1.1.2019 (Tue) --

### Day 136 - 2.1.2019 (Wed)
**Today´s Progress:** I finished the book _Web Development with Node & Express_ (by Ethan Brown). 

### Day 137 - 3.1.2019 (Thu) +
**Today´s Progress:** I reviewed using Git (I want to use it when working on my Plan-App/Plan-Up project.). I created _new repository for my Plan-Up project on_GitHub_ and pushed the project-structure there. I did the basic HTML structure of the project. 

### Day 138 - 4.1.2019 (Fri)  +
**Today´s Progress:** I continued with my _Plan-Up project_ (its css).

### Day 139 - 5.1.2019 (Sat) +
**Today´s Progress:** I added JavaScript to my _Plan-Up project_. I tried to implement the MVC-architecture. It´s not complete yet, but I hope that I manage to make it all work...

### Day 140 - 6.1.2019 (Sun) +
**Today´s Progress:** I worked on my _Plan-Up project_ and its JavaScript part: _Add-btn_ is working! (You can add a new task and after add-btn-click it´s added to the to-do list.) _Delete-btn_ is also working! (You can delete individual tasks from the to-do list.) 

### Day 141 - 7.1.2019 (Mon)  +
**Today´s Progress:** I continued working on my _Plan-Up project_: set and display _dates from/until_ and _compute days remaining_. (The dates are stored in the form of timestamp.)

### Day 142 - 8.1.2019 (Tue) +
**Today´s Progress:** I added _SVG icons_ (from icomoon.io) and had to re-do the html and css to be positioned as I intended. 

### Day 143 - 9.1.2019 (Wed)  +
**Today´s Progress:** I worked on the css of the taskList in my _Plan-Up project_. (But didn´t solve what I intedended. :-( )

### Day 144 - 10.1.2019 (Thu) +
**Today´s Progress:** I did some changes to JS, but the result wasn´t satisfactory, so I wanted to revert all the changes. So I read the documentation and posts regarding _Git & undoing changes_ (e.g. on [atlassian](https://www.atlassian.com/git/tutorials/resetting-checking-out-and-reverting)).  

### Day 145 - 11.1.2019 (Fri) +
**Today´s Progress:** I discarded changes to my files of _Plan-Up_ to the last commit. I found out, that there is a bug even in this version! I´m completely stuck - I´m trying to find the bug, but it´s still not working! :-/

### Day 146 - 12.1.2019 (Sat) +
**Today´s Progress:** I continued with my _Plan-Up project_. It´s working now: I can add items to todo-list, when checkbox is checked, the item moves to done-list. When it´s unchecked, it gets back. However, I found out that the _state_ is working correctly, but the view is not correct. I continue working on this issue.

### Day 147 - 13.1.2019 (Sun) +
**Today´s Progress:** I continued with my _Plan-Up project_. I fixed the problem with moving/deleting the correct item (both in state and in view). I shortened my code (changed the functions to accept arguments and to be more universal - in order to "DRY".)

**Thoughts:** Array.find() - returns the value of the first element in an array that passes a given test. Array.slice() - returns the part of the array (in form of other array!). 

### Day 148 - 14.1.2019 (Mon) +
**Today´s Progress:** I added button & function for deleting both lists (from view & state). I merged the "shortening" branch with the "master". I created a new branch ("sorting") and worked on the sorting-functionalities. During this, the complete project got broken and doesn´t start at all. I wanted to go back to my previous commit, but it´s not working neither! (I´d bet that it worked before! How is it possible?) So I´m trying to find some working solution (and learning more about GIT, Webpack,...)....

I went back in my git, searched for problems, and when I switched back to newer commits, these worked again! :-( (That´s true that I deleted and re-installed all the dependencies from package.json again - perhaps here was a problem?? However it seems to work again... (But I lost my most recent changes regarding sorting items in the list.)

**Thoughts:** For better visualisation of commits these scripts can be useful:

```
git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(auto)%d%C(reset)'

and

git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%C(auto)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)'
```

### Day 149 - 15.1.2019 (Tue)  +
**Today´s Progress:** I continued with work on my _Plan-Up Project_ (JavaScript): deleting of individual lists feature added, icons at both lists added (will be used for sorting lists). 

### Day 150 - 16.1.2019 (Wed) +
**Today´s Progress:** I worked on my _Plan-Up Project_ - I fixed the reaction to delete-list-btn click for cases, when there is no such list yet. I did some changes to my JS-code in order to make my code shorter.

### Day 151 - 17.1.2019 (Thu) +
**Today´s Progress:** I shortened the code of the whole _Plan-Up Project_ (created functions for repeating code, united more things to one function using more arguments passed to the function,...) 

### Day 152 - 18.1.2019 (Fri) +
**Today´s Progress:** I worked on the sorting of items after pushing relevant icon (urgency, name, tag): it´s working for state-lists now.

### Day 153 - 19.1.2019 (Sat) +
**Today´s Progress:** I continued on my _Plan-Up Project_: I set the default until-date to today and disabled picking past dates.

**Thoughts:** For setting today´ date: 

```
let today = new Date().toISOString().substr(0, 10);
document.querySelector("#today").value = today;
```

 or

```
document.querySelector("#today").valueAsDate = new Date();
```

### Day 154 - 20.1.2019 (Sun) +
**Today´s Progress:** I continued on my _Plan-Up Project_: added animation on hovering sort-icons, fixed reaction after clicking sort-icon when there is no list yet.

### Day 155 - 21.1.2019 (Mon) +
**Today´s Progress:** I tried to add view-sorting to my _Plan-Up Project_ (state-sorting works already), but there was still an error and I didn´t find out how to do it now. I see that my project structure could be different from the beginning (and perhaps better in broad context), but that´s what I learned for future projects.

### Day 156 - 22.1.2019 (Tue) 
**Today´s Progress:** Based on some articles I understood that perhaps my complete idea of the _Plan-Up Project_ would be much better to do in _React_ (which was on my to-do list for longer time), so I decided to start the [React course](https://www.udemy.com/react-the-complete-guide-incl-redux/) which I bought on Black Friday Sale :-D. I went through the intro section and the section revising ES6 JavaScript. 

### Day 157 - 23.1.2019 (Wed) +
**Today´s Progress:** I revised array methods and especially the form of arrow functions (on MDN and others). I tried to refactor the syntax of my class in Plan-Up Project, but it seems that webpack doesn´t support this form ("doesn´t support experimental syntax"). So I went back to my previous syntax.

### Day 158 - 24.1.2019 (Thu) +
**Today´s Progress:** I learned the _Base Syntax_ of _React_ (in the Reacto-course on Udemy). I did the assignment after watching the section (created two components (userInput & userOutput), added input-handler, added state,...). 

**Thoughts:** Tomorrow I´m going to intro to my first _Hackaton_! I´m looking forward to it, because I think it could help me in finding some ideas and advice for finishing my _Plan-Up Project_!

### Day 159 - 25.1.2019 (Fri) +
**Today´s Progress:** I worked on my _Plan-Up Project_. The view-update after sorting todo-list is working. I refactored some code (extracted some functions, got rid of one which I didn´t find that useful and solved it other way,...).

### Day 160 - 26.1.2019 (Sat) +
**Today´s Progress:** Today I attended a _Hackathon_ organized by [Czechitas](https://www.czechitas.cz/en/). I learned how it´s difficult to work in a team, learned how to solve _merge problems_ with _Git_ and _GitHub_, implemented charts to our project using _Chart.js_... I found that it´s much easier to work on a project myself, even when the project is more difficult (especially because I can use my own ideas and don´t need to change the way how I solve a problem because of other complexities.) Our 3-member team managed to join the website (HTML/CSS/JS) with a database on PostgreSQL. I´m not happy about our result project at all, but this event was a great experience and taught me a lot!

### Day 161 - 27.1.2019 (Sun) +
**Today´s Progress:** I did the challenge at the [React course](https://www.udemy.com/react-the-complete-guide-incl-redux/), section _Working with lists and conditionals_: Create an app with input, the input-text is shown below + each letter in an individual box. After clicking on any box the letter is deleted (box disappears and letter is deleted from the text). 

### Day 162 - 28.1.2019 (Mon) +
**Today´s Progress:** I went through the sections _Styling components_ and _Debugging_ in the React course. 

### Day 163 - 29.1.2019 (Tue) 
**Today´s Progress:** I started the section about _Lifecycle of components_ in the React course. It looks quite clear for me until now. When I tackled this topic earlier, I didn´t understand it, but now it´s much more clear. ;-)

### Day 164 - 30.1.2019 (Wed) 
**Today´s Progress:** I finished the section _Diving Deeper Into Components & React Internals_ of the _React_ course. I look forward to trying and practicing it in some apps! 

### Day 165 - 31.1.2019 (Thu) +
**Today´s Progress:** I did the basic structure and basic functioning of the Burger-App from the React course (code-along). 

**Thoughts:** _Styling trhough modules:_ the files must be named e.g. Layout.module.css or Button.module.css. (From React 16 the modules are in-built, earlier it was needed to do the "eject"). 

### Day 166 - 1.2.2019 (Fri) +
**Today´s Progress:** I continued with the Burger-App: added the modal, backdrop, buttons for cancel/continue, count price... (code along). I like React!!!

### Day 167 - 2.2.2019 (Sat) +
**Today´s Progress:** I finished the first section buildind the Burger-App (code along). I did the section on _HTTP-requests and AJAX in React_ (learned about _Axios_, _instances_ and _interceptors_). 

### Day 168 - 3.2.2019 (Sun) (+)
**Today´s Progress:** I connected the server to the Burger-App (using _Firebase_) and started working with Firebase.

### -- Day off - 4.2.2019 (Mon) --

### Day 169 - 5.2.2019 (Tue) (+)
**Today´s Progress:** I continued with the Burger-App at the React course (code-along). I added sending the POST-request and worked on handling the errors (using higher-order-component). 

### Day 170 - 6.2.2019 (Wed) (+)
**Today´s Progress:** I did the first part of the section about _React-Router_ (routing, _Link_ and _NavLink_, _withRouter_, passing and extracting _route-parameters, query-parameters_ and fragments/hash,...). 

### Day 171 - 7.2.2019 (Thu) 
**Today´s Progress:** I finished the section about _React-Routing_ (_Switch_ component, _nested routes_, _History-prop_, _Lazy loading_,...). 

### Day 172 - 8.2.2019 (Fri) +
**Today´s Progress:** I did the final challenge of the _React-Routing_ section of the React-course (I practiced there most of the things  I learned in the last three days).

### -- Days off - 9.2.2019 (Sat) to 17.2.2019 (Sun) --
I was on winter holiday with my family and friends. I took with me my laptop, but didn´t come to coding (just reading some stuff regarding coding, but not much).

### Day 173 - 18.2.2019 (Mon) +
**Today´s Progress:** I repeated some JavaScript concepts (ES6 features).

### Day 174 - 19.2.2019 (Tue) 
**Today´s Progress:** I continued with the React-course: I did the section _Adding Routing to the Burger Project_.

### Day 175 - 20.2.2019 (Wed) +
**Today´s Progress:** I finished the part of the _React-course_ until the Redux part. I went back to the React section of the course _The Complete Web Developer in 2019_, which I did earlier: this time it´s everything crystal-clear! Wow, it´s great! I started the _Robofriends App_.  

### Day 176 - 21.2.2019 (Thu) +
**Today´s Progress:** I continued with my _Robofriends App_ along with the React section of the course _Complete Web Developer in 2019_.

### Day 177 - 22.2.2019 (Fri) 
**Today´s Progress:** I reviewed the sections about _JSON/AJAX, Asynchronous JS, Backend Basics and APIs_. 

### Day 178 - 23.2.2019 (Sat) +
**Today´s Progress:** I watched the first part of the Front-End of the Face-Recognition-App. I got inspired by it and coded part of my first react plan-app. 

### Day 179 - 24.2.2019 (Sun) +
**Today´s Progress:** I watched another part of the Front-End Face-Recognition-App. I continued coding my first _react plan-app_ (added forms and routing - sign-in / sign-out / register).

### Day 180 - 25.2.2019 (Mon) +
**Today´s Progress:** I reviewed the _Backend part_ of the ZtM course (first part of it). I continued coding my react-plan-app (it´s backend).

### Day 181 - 26.2.2019 (Tue) +
**Today´s Progress:** I finished the Backend-part of the ZtM course. I connected the backend and frontend part ov my react-plan-app. I also started reviewing the part about _Databases_. I installed and started _PostgreSQL_ (wasn´t so easy - there were many problems, but I succeeded!). 

### Day 182 - 27.2.2019 (Wed) +
**Today´s Progress:** I finished the Database-part of the ZtM course. I created my _Database_ and connected it to my front-end and back-end part of my app. It´s great!!! 

**Thoughts:** I decided to make my first project using React and Databases a more simple than I intended (complex to-do app). First I will do something easier, just to practice combining frontend with the backend and database. (But later I will do my to-do app - I look forward to doing it!)

### Day 183 - 28.2.2019 (Thu) +
**Today´s Progress:** I worked on my app. I did various changes with database and front-end to see how it impacts the result. I think I need some review of routing. 

### Day 184 - 1.3.2019 (Fri) +
**Today´s Progress:** I managed to find the bug in my react-app! (I thought that the problem was in routing, but the bug was much simpler - incorrect type of brackets!! Then I started my react app (from scratch) - _React Calculator_. I made the components and did just basic styling (this needs to be improved!) I decided to use plain css (not tachyons).

### Day 185 - 2.3.2019 (Sat) +
**Today´s Progress:** I continued with my _React Calculator_ - styling and basic structure. 

### -- Day off - 3.3.2019 (Sun) --

### Day 186 - 4.3.2019 (Mon) +
**Today´s Progress:** I read part of the _React docs_. I worked on the functionality of the _React Calculator_.

### Day 187 - 5.3.2019 (Tue) +
**Today´s Progress:** I enrolled to an in-person course of _Advanced JavaScript_ and today was the first lesson: today there were some introductory topics (npm, git, github).

### Day 188 - 6.3.2019 (Wed) +
**Today´s Progress:** I read the topics about props.children and intro to react hooks. I read part of the _The road to React_ and watched some videos from Dan Abramov. I learned about _hot module reloading_ (by Dan Abramov).

**Thoughts:** 
Hot module reloading: tool to reload the application in the browser without page refresh (this way the application state is kept):
``` if (module.hot) {
module.hot.accept() }
```

### Day 189 - 7.3.2019 (Thu) +
**Today´s Progress:** I read some more articles about React (mostly from Robin Wieruch). I read and coded-along with the Road to Learn React book.  

### Day 190 - 8.3.2019 (Fri) +
**Today´s Progress:** I finished the functionality of my _React Calculator_ (all the calculations work, even with the float numbers etc). 
I finished the course "The Complete Web Developer in 2019: Zero to Mastery" (went through the CSS Grid section, which was added to the course). 

### Day 191 - 9.3.2019 (Sat) +
**Today´s Progress:** I fixed the bug with accepting more commas "." in a number in my _React Calculator_. I started the course [The Complete Junior to Senior Web Developer Roadmap (2019)](https://www.udemy.com/the-complete-junior-to-senior-web-developer-roadmap/)_ - I did the section about _SSH_.

### Day 192 - 10.3.2019 (Sun) +
**Today´s Progress:** I added restriction in possible length of number-input in my _React Calculator_. I continued with the course (JtS)- finished the section about _Performance: part 1_ and did the section about _React_ (Robofriends-app in React).

**Thoughts:** Regarding performance, I like the _Above the fold loading_ (importing the stylesheet of only the visible part of the page, the lower part imports later). Also, _downloading css according to @media_ is super.

_Tools for performance testing:_ [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/?hl=cs), [WebPage Test](https://www.webpagetest.org/).

### Day 193 - 11.3.2019 (Mon) 
**Today´s Progress:** I did the section about _Redux_ and _Webpack, Babel, ESLint,..._ in the course (JtS). 

### Day 194 - 12.3.2019 (Tue) +
**Today´s Progress:** I did the section _Performance 2_ in the course JtS: learned about _Code splitting, Tree Shaking,..._ and about _PWA (Progressive web apps)._ 

### Day 195 - 13.3.2019 (Wed) 
**Today´s Progress:** I read more information about _asynchronicity of setState() in React_ (I think some bugs in my React-calculator are connected with this). Also, I repeated first part of the _React-course (Basics, Lists&Conditionals, Styling of components, Debugging of React-apps)_. That´s great how things are fitting together now! 

### Day 196 - 14.3.2019 (Thu) +
**Today´s Progress:** I worked on my _React Calculator_: I tried to find out where is the bug. I solved one, but with the solution I created another bug in functionality of the calculator. :-( There must be some issue in the logic of the app. I must find out where!!!

### Day 197 - 15.3.2019 (Fri) +
**Today´s Progress:** I want to put my previous projects online, so I´ll go through them to check if these are ok. Today I went through Survey form, Technical Documentation Page, and Randome Quote Machine (in this I have one issue which I will consult). I also watched the section of _Lifecycle Hooks_ and _React Hooks_ in the React-course. 

### Day 198 - 16.3.2019 (Sat) 
**Today´s Progress:** I continued with the section of _Lifecycle Hooks_ and _React Hooks_ in the React-course. Learned about _ref_ and _context_. 

### Day 199 - 17.3.2019 (Sun) +
**Today´s Progress:** I worked on improving my _Portfolio Website_ (styling, fonts, colors, animations, texts,...). It took longer than I thought but I like it (of course there are still things to improve). ;-) 

### Day 200 - 18.3.2019 (Mon) +
**Today´s Progress:** I continued with improving my _Portfolio Website_. I watched part of the section about _Testing_ in the Junior-to-Senior course. 

### Day 201 - 19.3.2019 (Tue) +
**Today´s Progress:** I attended the in-person Javascript course (the main topic was classes and inheritance). In the online course (JtS) I learned about _TypeScript_. 

### Day 202 - 20.3.2019 (Wed) +
**Today´s Progress:** I did the section about _Single Page Applications_ and _Server Side Rendering_ in the JtS course.

### Day 203 - 21.3.2019 (Thu) 
**Today´s Progress:** I did the section about _Security_ in the JtS course.

### Day 204 - 22.3.2019 (Fri) 
**Today´s Progress:** I did the section about _Docker_ in the JtS course. At first encounter it looks really difficult, but I believe that I will understand it later, after I read some other information about it from other sources. ;-)

### Day 205 - 23.3.2019 (Sat) 
**Today´s Progress:** I learned about _Sessions & JWT_ in the JtS course (_Cookies-based- and token-based authentication_, their differences, pros and cons,...) and also about the _AWS_ (esp. about _AWS Lambda_). 

### Day 206 - 24.3.2019 (Sun) +
**Today´s Progress:** I learned about _Performance_ on the backend (_CDNs, GZip, Databases, Caching, Load balancing_) and about _CI/CD_. I began my homework for the in-person JavaScript course (in vanilla JavaScript).

### Day 207 - 25.3.2019 (Mon) +
**Today´s Progress:** I finished my homework for the in-person JavaScript course (A Library-app in vanilla JS). 

### Day 208 - 26.3.2019 (Tue) +
**Today´s Progress:** Today I had my in-person JavaScript course - today´s topic was _asynchronous JS, APIs, fetch_. I solved the problem with the background in my Wikipedia Viewer (after loading the list of results the background image wasn´t over the whole viewport (despite background-size: cover)) - solution was to set the min-height: 100vh (how easy!). :-D 

### -- Day off - 27.-28.3.2019 (Wed-Thu) --
(Funny thing: being ill with high fever I had dreams about JavaScript and React projects. :-D )

### Day 209 - 29.3.2019 (Fri) +
**Today´s Progress:** I want to make some of my earlier projects in React: I chose the _Wikipedia Viewer_ to do it _in React_, so I started work on it.

### Day 210 - 30.3.2019 (Sat) +
**Today´s Progress:** I worked on my _Wikipedia Viewer in React_: it´s almost done. I learned about ```rel="noopener noreferrer``` when using ```target="_blank"```, and also about ```dangerouslySetInnerHTML={{ __html: `${props.snippet}...` }}``` in place of ```innerHTML```. 

### Day 211 - 31.3.2019 (Sun) +
**Today´s Progress:** I finished my [Wikipedia Viewer in React](https://github.com/marieval/Wiki-Viewer-React).

### Day 212 - 1.4.2019 (Mon) +
**Today´s Progress:** I did some changes to my [Personal Portfolio Website](https://marieval.github.io/) and published it at github-pages. (It´s not finished yet, mainly the projects-section is not complete, but as I want to publish my react-app on github-pages I needed to publish the personal website first).

### Day 213 - 2.4.2019 (Tue) +
**Today´s Progress:** I managed to publish my _Wikipedia-Viewer in React_ on _github-pages_ (first it didn´t work, finally the solution was to set the ```git remote add origin <url>```). I improved responsivity of the project (only locally). 

### Day 214 - 3.4.2019 (Wed) +
**Today´s Progress:** I deployed the updated [Wikipedia-Viewer in React](https://github.com/marieval/Wiki-Viewer-React) to _github-pages_. I uploaded to github also my older project [Random Quotes](https://marieval.github.io/random-quotes/) (in this project I used _SASS/SCSS_) and deployed it to github-pages. 

### Day 215 - 4.4.2019 (Thu) +
**Today´s Progress:** I improved responsivity of my older projects (done as FCC-projects): _Twitch.TV API_, _JavaScript Calculator_, _Tic-Tac-Toe Game_ and updated the codes on Codepen. I updated those projects on my _Personal Portfolio_ and pushed the portfolio to GitHub and gh-pages. (The Portfolio Website is still not finished) 

### Day 216 - 5.4.2019 (Fri) +
**Today´s Progress:** I added responsivity to my older project _Local Weather App_. I further improved my _Personal Portfolio Webpage_. I also read some chapters of the book _Learning React (Alex Banks, Eve Porcello)_.

### Day 217 - 6.4.2019 (Sat) +
**Today´s Progress:** I improved my _Personal Portfolio Webpage_. I learned more about _Validating props_, _Default props_ and _Refs_ in React (online and in the book Learning React). 

### -- Day off - 7.4.2019 (Sun) --

### Day 218 - 8.4.2019 (Mon) +
**Today´s Progress:** I worked on the _Meet-Robot_ app (an app based on the course Zero To Mastery). I worked especially on it´s styling and made other minor changes. (Note: _Tachyons_ is sooo easy to use!)

### Day 219 - 9.4.2019 (Tue) +
**Today´s Progress:** On the in-person JavaScript course, we continued with the _async/await_ topic and _Promise.all()_. Also, I worked on my _Meet-Robot_ app. 

### Day 220 - 10.4.2019 (Wed) +
**Today´s Progress:** I tried to deploy my _Meet-Robot_ app to gh-pages, but it always got stuck and didn´t deploy (I was able only to upload the code to github). I googled for the problem, tried various solutions, but didn´t succeed. I updated my _Personal Portfolio_ (the deployed version). Further, today I worked on the _Find-Face_ app (another project of the Zero-To-Mastery course). I did the basic view and implemented the _Clarifai API_ to detect faces in pictures. 

**Thoughts:** To sync gh-pages + master branch:
```
git add . 
git status 
git commit -m "..." 
git push origin master 
git checkout gh-pages 
git rebase master 
git push origin gh-pages 
git checkout master 
```

### Day 221 - 11.4.2019 (Thu) +
**Today´s Progress:** I attended _Front-end Miniconference_: there were three interesting presentations: _Browser APIs_, _AMPHTML e-mail_ and _Native Lazy-Loading_.  Also, today I worked a bit on the _Find-Face_ app (however, the bounding box is not displaying correctly - I have to fix it). 

### Day 222 - 12.4.2019 (Fri) +
**Today´s Progress:** I deployed my [Meet-Robot](https://marieval.github.io/meet-robot/) app (the previous problem was fixed by reinstalling gh-pages package and fixing the vulnerabilities). I also updated my _Personal Portfolio Webpage_. 

### Day 223 - 13.4.2019 (Sat) +
**Today´s Progress:** I did the front-end part of my _Find-Face_ app (an app based on the Zero-To-Mastery course, which I finished earlier) - in React. Also, I decided to strenghten my understanding of JavaScript so I bought the course [Advanced JavaScript Concepts](https://www.udemy.com/share/100TZoBEAecF9QQXQ=/) and went through the JavaScript Foundation sections (among others about Call Stack, Memory Heap, Stack Overflow, Garbage Collection, Memory Leaks, Hoisting, Dynamic & Lexical Scope, Context,... These topics are not new to me, but they are really good explained in this course, so now it´s everything much clearer to me!)  

### Day 224 - 14.4.2019 (Sun) +
**Today´s Progress:** I started the backend-part of my _Find-Face_ app. Also, I continued with the _Advanced JavaScript Concepts_ course - did the section _Types in JavaScript_ (JS-types, type coercion, dynamic vs static typing, weakly vs strongly typed languages,...).

### Day 225 - 15.4.2019 (Mon) +
**Today´s Progress:** I finished the backend part of my _Find-Face_ app.

### Day 226 - 16.4.2019 (Tue) +
**Today´s Progress:** I learned in detail about _Closures_ and _Prototypal Inheritance_.

### Day 227 - 17.4.2019 (Wed) +
**Today´s Progress:** I did the section _Object Oriented Programming_ of the course _Advanced JavaScript Concepts_ (Factory Functions, Object.create, Constructor functions, Classes, Inheritance,...).

### Day 228 - 18.4.2019 (Thu) 
**Today´s Progress:** I did the section _Functional Programming_ in the course _Advanced JavaScript Concepts_ (Pure functions, Idempotent, Imperative x Declarative, Immutability, Higher Order Functions, Closures, Currying, Partial application, Memoization,...).

### Day 229 - 19.4.2019 (Fri) 
**Today´s Progress:** I watched the section _Asynchronous JavaScript in the course _Advanced JavaScript Concepts_ (fetch, async / await,...).

### -- Day off - 20.-21.4.2019 (Sat-Sun) --

### Day 230 - 22.4.2019 (Mon) 
**Today´s Progress:** I learned more about _Asynchronous JS_ - sequence, parallel, race, Web Workers,...

### Day 231 - 23.4.2019 (Tue) +
**Today´s Progress:** I learned about _Modules in JavaScript_ (IIFE/Module pattern, CommonJS, ES6 Modules) and about _Error Handling_. In the in-person JavaScript course we worked on the Zoo-app (using asynchronous JS, modules,...). 

### Day 232 - 24.4.2019 (Wed) +
**Today´s Progress:** I worked on a new _Weather-app_ (current weather and forecast in a city based on OpenWeatherMap API is working).

### Day 233 - 25.4.2019 (Thu) +
**Today´s Progress:** I learned basics about _Data Structures_ and more about _Arrays_ (dynamic vs. static arrays,...) and I revised some Array-operations.

### Day 234 - 26.4.2019 (Fri) +
**Today´s Progress:** I learned about _Hash Tables_ and revised some Objects-operations. 

### Day 235 - 27.4.2019 (Sat) 
**Today´s Progress:** I revised some of the advanced JavaScript topics and finished the course [Advanced JavaScript Concepts](https://www.udemy.com/advanced-javascript-concepts/). 

### -- Day off - 28.4.2019 (Sun) --
(Today I worked on my CV for being able to apply to IT-jobs.)

### Day 236 - 29.4.2019 (Mon) +
**Today´s Progress:** I further improved my _Weather-app_ (did especially refactoring the code).

### Day 237 - 30.4.2019 (Tue) +
**Today´s Progress:** I did some improvements to my _Weather-app_.

### -- Day off - 1.5.2019 (Wed) --

### Day 238 - 2.5.2019 (Thu) +
**Today´s Progress:** I learned more about using _Async / Await_ (I think I understand it much better now!). Furthermore, I learned about _Jekyll_ (and other Static Site Generators). I registered to _CodeWars_ and completed one "kata" (challenge). 

### Day 239 - 3.5.2019 (Fri) +
**Today´s Progress:** I fixed some bugs on my _JavaScript Calculator_ and did some changes in _My Portfolio_ website. 

### Day 240 - 4.5.2019 (Sat) +
**Today´s Progress:** I continued with my _React Calculator_ (which I started already longer time ago..): I worked on the functionality.

### Day 241 - 5.5.2019 (Sun) 
**Today´s Progress:** I learned about _Performance measurements_, _Big O_, _Time complexity_ and _Space complexity_ (in the course [Master the Coding Interview: DataStructures & Algorithms](https://www.udemy.com/course/master-the-coding-interview-data-structures-algorithms/)).

### Day 242 - 6.5.2019 (Mon) +
**Today´s Progress:** I continued with the topic from my last-week´s in-person class of JavaScript: implementing _Promise.all_ and _async / await_ in my app (Animals/Zoos). I also attended local front-end _Meetup_: the topic was _Static Website Generators_.

### Day 243 - 7.5.2019 (Tue) +
**Today´s Progress:** I did the _DataStructures: Arrays_ topic, and did some challenges regarding arrays. 

### Day 244 - 8.5.2019 (Wed) +
**Today´s Progress:** I continued with my assignment: _Weather-app_: added eventListeners for buttons for choosing a city, in which the weather&forecast should be displayed.

### Day 245 - 9.5.2019 (Thu) +
**Today´s Progress:** I learned further about datastructures: _Linked Lists_ and did related challenges. I did some JavaScript challenges at SoloLearn.

### Day 246 - 10.5.2019 (Fri) +
**Today´s Progress:** I learned about _Stacks & Queues_, and _Trees_. I did challenges related to these topics. I did some challenges at _CodeWars_.

### Day 247 - 11.5.2019 (Sat) 
**Today´s Progress:** I continued learning about datastructures: _Graphs_. Today, I attended an in-person workshop on _Scrum_. 

### Day 248 - 12.5.2019 (Sun) +
**Today´s Progress:** I learned about _recursion_ in JS and did some challenges. 

### Day 249 - 13.5.2019 (Mon) +
**Today´s Progress:** I continued with my assignment: _Weather-app_. I learned more in detail about _sorting_ of data. 

### Day 250 - 14.5.2019 (Tue) +
**Today´s Progress:** Today, in my in-person JS-course we worked further on _async-await_ utilization. I used it in our Animal/Zoo project. 

### Day 251 - 15.5.2019 (Wed) +
**Today´s Progress:** I got back to my _React Calculator_ and worked on it´s functionality.

### Day 252 - 16.5.2019 (Thu) +
**Today´s Progress:** I worked on my _React Calculator_: the calculations are working, but there is still a bug when doing some consecutive math-operations. 

### Day 253 - 17.5.2019 (Fri) +
**Today´s Progress:** I did some minor changes to my _Portfolio Website_. 

### -- Day off - 18.5.2019 (Sat) --

### Day 254 - 19.5.2019 (Sun) +
**Today´s Progress:** I did some repetition on _React_ basics (props, state, two-way-binding, useState(),...).

### Day 255 - 20.5.2019 (Mon) +
**Today´s Progress:** I did some repetition on _React_ (Conditional rendering, Lists, Styling of components,...).

### Day 256 - 21.5.2019 (Tue) +
**Today´s Progress:** In my in-person JavaScript course, I learned more about _state_ and tried _localStorage_ in practice. 

### Day 257 - 22.5.2019 (Wed) 
**Today´s Progress:** I read more about _BEM_ (A friend of mine pointed out that I used BEM in my projects incorrectly, so I would like to improve it. ;-) ) Also, I tried to better understand the _Lifecycle hooks in React_. 

### Day 258 - 23.5.2019 (Thu) + 
**Today´s Progress:** I did some minor improvements to my _Portfolio Website_. 

### Day 259 - 24.5.2019 (Fri)  
**Today´s Progress:** I learned more about how to plan a _project in React_ and started one as code-along. 

### Day 260 - 25.5.2019 (Sat)  
**Today´s Progress:** I continued learning about _React_ (passing props in the app, managing state, event handlers, conditional css).

### -- Day off - 26.-27.5.2019 (Sun-Mon) --

### Day 261 - 28.5.2019 (Tue) + 
**Today´s Progress:** In my _[Wiki-Viewer App](https://github.com/marieval/Wiki-Viewer-React)_, I converted class-based component Searchwiki to functional component (because I don´t need to manage state there). In my _[Random-Quotes App](https://github.com/marieval/random-quotes)_ I updated the dependencies (because GitHub showed high vulnerabilities in those): I had to use ```git push -f origin master``` to force the push to GitHub. Today, I attended also my in-person _Advanced JavaScript course_: we created an app for a coffee-shop. I really enjoyed it: it was like "connecting the dots" - how everything can be used and fits together..

### Day 262 - 29.5.2019 (Wed) + 
**Today´s Progress:** I learned/revised the topic of _AJAX in React_. 

### Day 263 - 30.5.2019 (Thu) + 
**Today´s Progress:** I think I need to build my own project, so I decided to create my "old" idea of a _self-management app in React_. I did  planning of structure of the whole app an started some basic components (for navigation etc).

### -- Day off - 31.5.-3.6.2019 (Fri-Mon) --

### Day 263 - 4.6.2019 (Tue) + 
**Today´s Progress:** In my in-person JS course, I learned/improved my knowledge in usage of _JS-Modules, Async/Await,..._. We created an app for an e-shop. 

### Day 264 - 5.6.2019 (Wed) + 
**Today´s Progress:** I started building my own version of a coffee-shop app to train my plain-JS knowledge. 

### Day 265 - 6.6.2019 (Thu) + 
**Today´s Progress:** I continued building my coffee-shop app using vanilla-JavaScript.

### Day 266 - 7.6.2019 (Fri) + 
**Today´s Progress:** I continued with building the coffee-shop app.

### Day 267 - 8.6.2019 (Sat) + 
**Today´s Progress:** I finished the coffee-shop app.

### -- Day off - 9.6.-13.6.2019 (Sun-Thu) --

### Day 268 - 14.6.2019 (Fri) + 
**Today´s Progress:** I did some JavaScript challenges (however, I wasn´t able to solve those dealing with tree-traversal and a specific type of sorting).

### -- Day off - 15.6.2019 (Sat) --

### Day 269 - 16.6.2019 (Sun) + 
**Today´s Progress:** I attended a Hackathon organized by Czechitas. My team created an app for keeping track of lending/borrowing things using HTML/CSS/JavaScript on the frontend and Java on the backend. It was a great experience!! 

### -- Day off - 17.6.2019 (Mon) --

### Day 270 - 18.6.2019 (Tue) + 
**Today´s Progress:** Today I learned about _Semantic UI React_ - I like it: I look forward to trying it in my project!

### Day 271 - 19.6.2019 (Wed)  
**Today´s Progress:** I learned basics about _Semantic UI in React_.

### Day 272 - 20.6.2019 (Thu) 
**Today´s Progress:** I reviewed some points from _JavaScript under-the-hood_ (JS engine, interpretation vs. compilation, JIT compilation,...)

### Day 273 - 21.6.2019 (Fri) 
**Today´s Progress:** I tried some small things using _Semantic UI in React_.

### Day 274 - 22.6.2019 (Sat) 
**Today´s Progress:** I continued with revising the _JavaScript_ under-the-hood parts (Execution Context, Scope, Hoisting, This,...) 

### -- Days off - 23.6.-10.7.2019  (Mon-Wed) --

### Day 275 - 11.7.2019 (Thu) +
**Today´s Progress:** I learned about _GatsbyJS_ and how to use it. I started a simple blog using GatsbyJS. 

### Day 276 - 12.7.2019 (Fri) +
**Today´s Progress:** I worked on the _GatsbyJS_ blog and tried to deploy it to _Netlify_ (deploying got stuck and doesn´t seem to work. I´ll try tomorrow.) I was excited about GatsbyJS (and have already ideas for what projects I will use it) and about how easy it is to deploy it to Netlify, but there is this problem with deployment... I hope that tomorrow it will work as supposed.. 

### Day 277 - 13.7.2019 (Sat) +
**Today´s Progress:** I started the basic react-project _Monster-Rolodex_ based on the React course by Andrei Neagoie. (Netlify deployment, which I did yesterday, still doesn´t work.)

### -- Days off - 14.7.-19.7.2019  (Sun-Fri) --

### Day 278 - 20.7.2019 (Sat) +
**Today´s Progress:** I started the e-commerce project _Crwn-shop_ based on the React course by Andrei Neagoie. 

### Day 279 - 21.7.2019 (Sun) +
**Today´s Progress:** I continued with the _Crwn-shop_: added sign-in page, used routing in the app.

### Day 280 - 22.7.2019 (Mon) +
**Today´s Progress:** I connected _Firebase_ to my _Crwn-shop_ app and added _Google-sign-in_. 

### Day 281 - 23.7.2019 (Tue) +
**Today´s Progress:** I implemented using _Firestore_ to my _Crwn-shop_ app.

### -- Day off - 24.7.2019  (Wed) --

### Day 282 - 25.7.2019 (Thu) +
**Today´s Progress:** I learned basics about _Redux_ and started implementing it in the Crwn-shop app.

### Day 283 - 26.7.2019 (Fri) +
**Today´s Progress:** I added _Redux_ to the _Crwn-shop_ app (implemented connect(), mapStateToProps and mapDispatchToProps to my Header and App components).

### -- Days off - 27.-28.7.2019  (Sat-Sun) --

### Day 284 - 29.7.2019 (Mon) +
**Today´s Progress:** I added the cart-icon and cart-dropdown to the header (incl. connection to state using Redux).

### Day 285 - 30.7.2019 (Tue) +
**Today´s Progress:** I added the cart-items to the app (in the cart-dropdown) and connected it using Redux. 

### -- Day off - 31.7.2019  (Wed) --

### Day 286 - 1.8.2019 (Thu) +
**Today´s Progress:** I learned about _local storage_ using _Redux-Persist_ and used it in the _Crwn-shop_ app. I implemented _Reselect_ in the app.

### Day 287 - 2.8.2019 (Fri) 
**Today´s Progress:** I decided to do some repetition: Today I revised implementing Firebase.

### Day 288 - 3.8.2019 (Sat) 
**Today´s Progress:** Today I revised setting up Redux in a project. 

### -- Day off - 4.8.2019  (Sun) --

### Day 289 - 5.8.2019 (Mon) 
**Today´s Progress:** Today I continued revising some sections of Redux.

### -- Day off - 6.8.2019  (Tue) --

### Day 290 - 7.8.2019 (Wed) 
**Today´s Progress:** Today I attended a meetup with some presentations reagarding accessibility, animations in JS, and others. I added some routing to the crwn-shop. 

### Day 291 - 8.8.2019 (Thu) 
**Today´s Progress:** Continue with my _Crwn-shop_ app. Implemented _Stripe payments_.

### -- Days off - 9.-11.8.2019  (Fri-Sun) --

### Day 292- 12.8.2019 (Mon) 
**Today´s Progress:** I deployed the _Crwn-shop_ app to _Heroku_. 

