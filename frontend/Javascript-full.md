
### Questions?
* **How much will it take**
    - If you are new to programming and this is your first or second language, without having done any major projects, anywhere between 4 and 12 months depending on your background and time you are willing to put into learning
    - If you are an experienced programmer, this can take between 2 and 6 months, again depending on the time you put in and you general background.
* **Is this enough for employment?**
    -	The bad news is no, your changes of being employed while knowing only javascript are very slim unless you developed a popular library or have some kind of awesome project under your belt. You will have to either learn a frontend development framework + frontend concepts in general, or focus on the backend
    -	 The good news is that learning javascript to advanced degree means you are already halfway there, you only have to choose a niche you want to continue on. We have 2 roadmaps that you can start with or continue with after learning javascript those being frontend and backend roadmaps
    -	Frontend development roadmap
    -	Backend development roadmap


### Prerequisites
**Essential**
* *Basics of computer science* - A solid understanding of computer science fundamentals provides a strong foundation for any aspiring programmer. While some concepts may seem unrelated to everyday tasks, they equip you with the tools to solve complex problems. Various courses and resources are available for learning the basics.
    - [Harvard CS50](https://www.youtube.com/watch?v=8mAITcNt710)
    - [0 to software engineer roadmap](https://github.com/jwasham/coding-interview-university)

**Recommended**
* *Git and Github* - Understanding Git is really important. Created by Linus Torvalds, this version control system is a cornerstone in modern development. Mastering Git and GitHub will streamline your coding projects and make team collaboration easier. To get started, these videos are worth watching
    - [Git explained by fireship](https://www.youtube.com/watch?v=HkdAHXoRtos)
    - [Git explained by freecodecamp](https://www.youtube.com/watch?v=RGOj5yH7evk&t=0s)
* *Problem solving* - Being proficient at problem-solving is more than just a skill—it's a necessity. It's the thing that sets you apart and there is no real "pathway" to learning it. The only thing that will truly help you is thinking deeply and pushing your limits by making projects or solving some challenges. Below there are some videos that present some of the ways to think about problem solving
    - [Problem solving beginner guide](https://www.youtube.com/watch?v=UFc-RPbq8kg)
    - [Problem solving techniques](https://www.youtube.com/watch?v=r4TgqWbKRtA)
* *Internet and web* - Javascript is a language mainly used for frontend development, but is has a strong presence in the backend too. No matter which one you chose, you will still need to understand what a request is, how computer networks work with each other, etc. You don't need to master it, only have a good overview of the topic. This topic is more broadly called "networking"
    - [Basic computer networking course](https://www.youtube.com/watch?v=IPvYjXCsTg8)

**Legend**
* Basic programming node ( just look briefly through it if you have experience )
* Javascript specific ( important javascript specific concept )
* high priority
* Low priority
* Links ( links )

### 0. How to learn from here
* **Js is weird** - Javascript is most likely one of the weirdest programming languages out there, being infamous for some of the stunts if does. Don't feel discouraged if sometimes you simply don't get it, or everything seems to come down on you. All of us were there at one point or another.
* **About the roadmap** - This roadmap is neither an exhaustive list, nor the congregate of all human knowledge regarding javascript. It has the main chapters that a javascript programmer should know in order to work in a professional environment. You should learn and search for concepts outside this roadmap constantly and always try to improve your skills.
* **Learning is a marathon** - You should not try to "speedrun" this roadmap UNLESS you truly understand the concepts presented. Going over 10 things and not remembering any of them renders all of your effort useless. So learn constantly, make sure you understand the concept and you can implement it yourself and then got to the next one. And ALWAYS search for things that are not presented or might be missing in the roadmap, be as expansive as possible.


### 1. About javascript
	- A few words about javascript that I wish I knew earlier
* **What can you use it for** - First of all javascript is the foundation of web development. It was created to breathe life into webpages. Over the years javascript evolved and we keep seeing the doom predictions coming true "everything that can be built using javascript will be build using javascript". Right now javascript can be used for a wide range of tasks spanning frontend, backend, AI and even robotics.
* **History of javascript** [History of javascript by fireship](https://www.youtube.com/watch?v=Sh6lK57Cuk4)
* **Javascript for haters** [Javascript for haters](https://www.youtube.com/watch?v=aXOChLn5ZdQ)
* **Where you can run javascript** - Running javascript was one of the most confusing things for me when first learning the language. It seemed that 10 people had 10 ways to run javascript in different places and it messed up with my head. So I want to clarify this running thing from the start. Javascript can run 1. In the browser or 2. In a runtime on YOUR device WITHOUT a browser. Oftentimes, the js you run in the runtime can then be packed and sent to the browser with tool such as webpack, so things are not always only black or only white.
    * Browser - The most common environment, used for web development. I suggest you to try to right click -> inspecte element and then go to console. There you will be able to write javascript that will behave the same as the one you write in your ide.
    * Nodejs / runtimes - Nodejs is the most popular runtime but there are alternatives such as Deno or Bun ( which are also runtimes ). What these runtimes do is extract the browser engine and make it run locally. It's that simple! That of course means that you won't be able to access browser specific object if you run pure nodejs code such as document or window, but the language will stay the same for the most part.
    * Something VERY IMPORTANT about javascript ( explain how weird all there envs are )
* **Javascript is NOT Nodejs** - While Node.js uses the JavaScript language, it's important to understand that Node.js is a runtime that allows JavaScript to be used server-side. They are not the same thing. So javascript is the programming language and nodejs is the engine that allows js to run anywhere.
* **Javascript is NOT Ecmascript** - To put it simply, ecmascript is a blueprint and javascript is a language that implements that blueprint. Do not confuse the 2 !!
*  **Javascript is NOT Java** - When JavaScript was created, it initially had another name: “LiveScript”. But Java was very popular at that time, so it was decided for marketing purposes to make it closer to Java. So it has no real relation to Java at all.

### 2.  Basics of javascript

- The following chapters will give you the basics you need to know to start with javascript. You should know most of them, and at least to have heard about the others. I left a really good js course below that I HIGHLY encourage you to check out, since they cover many topics presented here in a very intuitive way

    -  [Bro code javascript course](https://www.youtube.com/watch?v=8dWL3wF_OMw)

* **2.1 Variables** - Everything you should know about variables. Better learn it all at the beginning so you won't have weird troubles later on. For the most part a manageable chapter.
  - [Basics of variables video](https://www.youtube.com/watch?v=edlFjlzxkSI)
  - [Variables explained](https://javascript.info/variables)
  - [Data types explained]()
    * *Datatypes*

        * Primitives - These are the simplest types of data.  Numbers, strings, booleans are all primitives. They are always copied again so if you have a=1 , b=a, the value of a will be copied inside b.
          - [Primitives explained](https://javascript.info/types)
        * Non-primitives  - More complex types of data such as a JSON. And remember, THEY ARE PASSED BY REFERENCE. If you forget this, it will be the source of hours of pain and desperate debugging
            - [Primitives vs Non-primitives](https://www.youtube.com/watch?v=r5rYoJFWfN0)
        * Mutability - In a nutshell primitive types are immutable and their value will simply be copied somewhere else, whereas a non-primitive such as an array or object can be changed after it's created
            - [Mutability video](https://www.youtube.com/watch?v=DCJVYbu0MUQ)
        * Why I lost a hackathon - Here is a little story about data types and mutability. In the first year of college I started learning javascript and decided to put my skills to the test with a hackathon. I was about 1 to 2 months into learning js and I didn't get my theory right, being under the impression that a JSON is a primitive type and it's copied. It didn't make any sense but anyway. I tried creating a small physics engine that would pass some json's around. I swear I debugged those damn jsons for 18 hours straight and I just couldn't figure out why they were messing up with each other so badly, because what I have done is to "copy" one json and then change it, but that altered the previous json and the rest is history.
    * *Declarations - const, let, var* - Const is for constants, var is the old version, let is the new version. The main difference is that "var" declared variable is hoisted, which means javascript puts it at the top of the file at runtime
        - [Var vs let video](https://www.youtube.com/watch?v=A2x75iOqidA&list=PLZPZq0r_RZOMRMjHB_IEBjOW_ufr00yG1&index=28)
    * *Hoisting* - Hoisting is a way in which javascript "moves" some functions and variables at the top of the file before executing them. This allows the use of functions before declarations without errors.
        - [Hoisting for variables](https://www.youtube.com/watch?v=EjWf0TyLK-A)
    * *Type casting* - Casting means turning a variable from one type to another. This can be done either in an explicit way in code such as parseInt("21") or in an implicit way at RUNTIME where the compiler converts a variable of one type to another, eg "11" + 2 = "112"
        - [Typecasting explained video](https://www.youtube.com/watch?v=5-rhVtbJlYA)
* **Basic control flow** - These are the basics ways to make decisions inside your program. If you already programmed somewhere else you can skip this part
    * [if statement](https://www.youtube.com/watch?v=fA8BceA_cp4)
    * [switch statement](https://www.youtube.com/watch?v=Mg_Wulbkm-o)
* **2.2 Functions**
    * *"Classic" functions* - The standard way of declaring a function. It can be accessed before declaration.
      -	[Functions explained video](https://www.youtube.com/watch?v=d7cfhgfojLA)
      -	[Functions basics article](https://javascript.info/function-basics)
    * *Arrow functions* - A special way of declaring functions and use them kindof like variables. They are extremely useful to declare minimalistic functions, but also for advanced concepts such as closures. The "this" keyword also behaves differently, but we will come back to that a bit later.
      - [Arrow functions video](https://www.youtube.com/watch?v=kzzkrhzGpkg)
      - [Arrow functions article](https://javascript.info/arrow-functions-basics)
    * *Callbacks* - Callbacks are a type of function, that is well "called back". The idea is, this function is passed as a parameter in a second function and it is at some point called back within the second function.
        - [Callbacks explained video](https://www.youtube.com/watch?v=6J54mZBC69k)
    * 	[Hoisting for functions](https://www.youtube.com/watch?v=EvfRXyKa_GI)
* **2.3 Loops**
    * *for / while* - The 2 classic loops that appear in any programming language
        -	[For loop video](https://www.youtube.com/watch?v=XOROiF-phnE)
        -	[While loop video](https://www.youtube.com/watch?v=dje0ZaMY5Ck)
    * [*for of*](https://www.youtube.com/watch?v=yauK_9vSlg8)
* **2.4 Data manipulation functions** - There are a number of high level function in javascript which are meant to make data manipulation and transformation much much easier than normal. You should not know all of them, but it's good to have a basic grasp if the needget-started ever comes.
  - [Array methods article](https://javascript.info/array-methods)
    * [*Map*](https://www.youtube.com/watch?v=KZU4V38Cwfc)
    * [*filter*](https://www.youtube.com/watch?v=8dWL3wF_OMw&t=10090s)
    * [*Reduce*](https://www.youtube.com/watch?v=oZXhEFn187c)
    * [*forEach*](https://www.youtube.com/watch?v=KPuGKeVrmZg)
    * [*splice*](https://www.freecodecamp.org/news/javascript-splice-how-to-use-the-splice-js-array-method/)
    * [*slice*](https://www.w3schools.com/jsref/jsref_slice_array.asp)

* **2.5 Equality comparions** - Comparing variables in javascript can be tricky, since the data types are sometimes changed at runtime and you are allowed to compare anything ( which can be misleading sometimes )
    * *== and ===* - The double equality only compares the effective value, while triple equality also compares the type. As a thumb rule, always use the triple equality to be safe.
        - [== vs ===](https://www.youtube.com/watch?v=C5ZVC4HHgIg)
    * *isNan* - In javascript, if you try to do forbidden operations such as 0/0, the result will be something called "Nan" standing for Not a Number. Ironically enough, the Nan type is a number type in javascript, so checking whether a variable is a number or not will not guarantee is not a Nan. For this we have the function called isNan, which checks wheter a variable isNan or not
        - [isNan explained](https://www.w3schools.com/jsref/jsref_isnan.asp)
* **2.6 Basic frontend specific javascript** - This chapter is dedicated to anyone who want to learn frontend specific javascript. I have tried for the most part to keep this roadmap frontend agnostic and give the core concepts which are applicable to
    * *Document* - The document is kindof the root of the entire website. From there you have access to the entire website.
    * *Understanding the dom*
    * *Interacting with DOM* - Interacting with the DOM is the basis of javascript and frontend development. It is the way to make a website interactive and breathe life into it. I left below a really good tutorial for the basics of interacting with the DOM
      - [Interacting with the DOM](https://www.youtube.com/watch?v=y17RuWkWdn8)
        * [Node vs element](https://www.youtube.com/watch?v=rhvec8cXLlo)
        * [Node attributes](https://www.youtube.com/watch?v=exCLp12CUvQ)
        * [Node properties](https://javascript.info/dom-attributes-and-properties)
        * [Search methods](https://javascript.info/searching-elements-dom)
    * *Browser events* - Events are the way a browser sends messages to your javascript code. They are certain user interactions recorded by the browser which call a callback function "to do stuff" inside your code. For example, a button has an onClick event that does something
      - [Javascript event listeners video](https://www.youtube.com/watch?v=XF1_MlZ5l6M)
      - [Introduction to browser events](https://javascript.info/introduction-browser-events)
        * [e object](https://www.youtube.com/watch?v=_BVkOvpyRI0)
        * [Custom events](https://www.youtube.com/watch?v=DzZXRvk3EGg)
        * [mouse events](https://www.youtube.com/watch?v=MhUCYR9Tb9c)
        * [keyboard events](https://www.youtube.com/watch?v=lNJMDTSkNXo)


###  3. More core concepts
- Here is a list of more core javascript concepts that cannot be put in the basics section, but are still vital to your growth as a javascript developer.

* **Objects** - Objects might be the most important javascript concept of all. Almost everything you use in javascript are objects, from functions, to arrays to well, objects. This is a kind of pattern that is also present in python, where anything and everything is interpreted as an object. Primitive on the other hand ARE NOT objects.
    - [Objects explained fireship](https://www.youtube.com/watch?v=napDjGFjHR0)
    - [Objects explained Brocode](https://www.youtube.com/watch?v=adp5-HFSD30)
    - [Object explained article](https://javascript.info/object)
    * "this" keyword - "This" keyword is a very important concept in javascript objects, allowing you to access properties of the current object inside its methods. Oddly enough, this keyword works in plain functions too ( because functions are also objects in javascript ). We will come back on the this keyword sometime later for additional explanations, but for now remember it is used to access the current object.
      - [This keyword article](https://javascript.info/object-methods)
      - [This keyword video](https://www.youtube.com/watch?v=gvicrj31JOM)
      - [This keyword by bro code](https://www.youtube.com/watch?v=5L0LPndzROU)
    * [The "new" operator](https://javascript.info/constructor-new)
    * *Objects references* - I have mentioned this chapter before, but I want to stress it again, objects are passed BY REFERENCE, not by value like primitives are. Make sure you got that right
      - [Passing by reference vs value](youtube.com/watch?v=-hBJz2PPIVE)
    *  *Deepcopies* - Deepcopy is a way to truly copy an object into another object, without having any leftover references. It's a must know for any javascript developer
        - [Deepcopies explained](https://www.youtube.com/watch?v=LnBxD1aXw7I)
    * [*Garbage collection*](https://javascript.info/garbage-collection)

* **Data structures** - A list of important data structures in javascript that is highly recommended to be familiar with. The most important one is by far the JSON which is widely used to send data back and forth with apis and serves as a basis to the language data flow.
    * *JSON* - JSON is the most used data structure in javascript. You can think of it as a quick map, which holds values on different fields. A JSON can be used as an object too if on those fields you put either other JSONs or functions ( which you can use as methods )
        - [JSON explained video](https://www.youtube.com/watch?v=iiADhChRriM)
        - [JSON and its methods](https://javascript.info/json)
    * *Map* - Map is a built-in JavaScript object that stores key-value pairs and maintains the order in which they were inserted. Keys in a Map can be of any type, including objects, functions, or primitive types. Maps are iterable and have useful methods for manipulation, like `set()`, `get()`, `delete()`, and `has()`.
        - [Map explained](https://youtu.be/8dWL3wF_OMw?si=-40CY7zXH48X94cx&t=11568)
        - [Map and set explained](https://javascript.info/map-set)
        - [Why use maps instead of objects](https://www.youtube.com/watch?v=hubQQ3F337A)
    * [*WeakMap and Weakset*](https://javascript.info/weakmap-weakset)
    * *Set* - Set is a built-in JavaScript object that stores unique values of any type, whether primitive or object references. A Set object ensures that each value can only occur once, effectively removing any duplicates. Sets are iterable and have methods like `add()`, `delete()`, and `has()` for manipulation. They don't have key-value pairs; each value is its own key.
        - [Map and set explained article](https://javascript.info/map-set)
    * [*WeakSet*](https://javascript.info/weakmap-weakset)
    * [*Object Keys*](https://www.youtube.com/watch?v=UxMdQmJfWM8)
    * *Rest parameter and spread syntax* - The spread syntax has many uses, one them being to spread the fields of an object into another object. It is a very commonly used pattern for creating new objects or overwriting old fields.
      - [Object destructuring explained](https://www.youtube.com/watch?v=NIq3qLaHCIs)


* **More on "this" keyword** - We have touched upon "this" keyword before, but we haven't discussed all aspects of it. The "this" keyword behaves differently in various situations and now we will explore all of them.
  - ["This" explained in all situations](https://www.youtube.com/watch?v=fVXp7ZWjlO4)
  - ["This" by fireship](https://www.youtube.com/watch?v=YOlr79NaAtQ)
    * *In normal functions* - In regular functions, the this keyword references the object that called the function, which can be the global object, a specific object, or another function context, depending on how the function is called.
      - [Regular vs arrow functions](https://medium.com/geekculture/regular-vs-arrow-function-1f8140fbcece)
      - [Understanding this keyword](https://www.codementor.io/@dariogarciamoya/understanding-this-in-javascript-with-arrow-functions-gcpjwfyuc)
    * *In arrow functions* - Arrow functions don't truly have a this keyword, the this keyword of the arrow function will inherit the this keyword from the context of the parent that calls it.
      - [Regular vs arrow functions](https://medium.com/geekculture/regular-vs-arrow-function-1f8140fbcece)
      - [Understanding this keyword](https://www.codementor.io/@dariogarciamoya/understanding-this-in-javascript-with-arrow-functions-gcpjwfyuc)
    * *binding (call, apply, bind)* - Binding is a way to modify the default behavior and value of the this keyword to your liking.
      - [Binding explained video](https://www.youtube.com/watch?v=9eUe1-gLeKs)

* **Prototype** - You can think of a prototype as kindof a "base" for a certain class of objects in javascript. All objects including arrays, functions, etc have a prototype. Changing that that base class will reflect into all objects of that type, however, it is generally frowned upon directly changing a prototype. There are functions that handle that instead
  -[Prototypes explained visually](https://www.youtube.com/watch?v=01jVgCK-HX4)
  -[Prototypes article](https://javascript.info/function-prototype)
  -[Prototype chains explained](https://www.youtube.com/watch?v=jnME98ckDbQ)
    * *Prototypal inheritance* - This is the technique used to give certain new functionalities to a set of objects, by changing their base prototype which will then change all the objects. There are certain functions that allow you to manipulate prototypes however you want
        - [Prototypal inheritance article](https://javascript.info/prototype-inheritance)
    * [*Native prototypes*](https://javascript.info/native-prototypes)

### 4. Transpilers - Babel
- Babel is a tool that transpiles newer JavaScript code into older versions. This is useful because not all environments, especially some browsers, support the latest JavaScript features. Transpiling ensures backward compatibility with older environments.
* [Babel](https://babeljs.io/)

### 5. Useful features and syntactic sugar
- Syntactic sugar are various ways to simplify your code and make it more aesthetic/organized. They are not absolutely necessary to use or learn, but you might find them around and even want to use them yourself, so they are quite useful.	If you followed all the previous tutorials, you most likely know a good part of these ones
* [**?? ( nullish coalescence )**](https://javascript.info/nullish-coalescing-operator)
* [**!! ( double bang )**](https://dev.to/sanchithasr/what-is-the-double-bang-operator-in-javascript-4i3h)
* [**Rest parameter and spread syntax**](https://javascript.info/rest-parameters-spread)
* [**optional chaining .?**](https://javascript.info/optional-chaining)
* [**inline if**](https://javascript.info/ifelse)
* [**template literals**](https://www.youtube.com/watch?v=K4Kh5gw4PRE)
* [**Javascript weirdness**](https://www.youtube.com/watch?v=sRWE5tnaxlI)

### 6. Modules and packaging
- There are two primary module systems in JavaScript: CommonJS and ES6 modules. CommonJS was introduced by Node.js and became the de facto standard for server-side JavaScript. On the other hand, ES6 modules were introduced with ECMAScript 6 and have become the standard for client-side (browser) JavaScript. Over time, Node.js also introduced support for ES6 modules alongside CommonJS.
  - [Javascript modules in 100 seconds](https://www.youtube.com/watch?v=qgRUr-YUk1Q)
  - [ES6 vs Commonjs](https://www.youtube.com/watch?v=mK54Cn4ceac)
* **CommonJs** - Old way of importing thing in nodejs, was gradually replaced with ES6 over the course of time.
  -[CommonJs vs ES6 modules](https://www.youtube.com/watch?v=mK54Cn4ceac)
* **ES6 Modules** - Introduced with ECMAScript 6 (also known as ES6), this module system became the standard for client-side JavaScript and has since been adopted by Node.js as an alternative to CommonJS.
  -[ES6 modules explained](https://www.youtube.com/watch?v=cRHQNNcYf6s)
* **Dynamic imports** - A way of importing modules into javascript as you go, in order to reduce the initial js bundle size and reduce the overhead for optimization purposes.
  - [Dynamic imports article](https://javascript.info/modules-dynamic-imports)
  - [Dynamic imports explained](https://www.youtube.com/watch?v=ddVm53j80vc)

### 7. Advanced javscript
- At this point your should have a solid grasp on the basics and middle level javascript concepts and tools. Here are the last puzzle pieces you miss in order to truly call yourself a javascript developer. You can learn many of them gradually as you build projects, but the one you should truly pay attention to is ASYNCRONOUS JAVASCRIPT.
* **Javascript Event loop** - Javascript is a single threaded language, meaning you don't have the paralelism you can enjoy in other programming laguages. Instead, there is a mechanism at work called the JAVASCRIPT EVENT LOOP which allows you to use computationally heavy operations or simply events that have to wait, without actually blocking the main thread. Below I left the most likely the best explanation up to date of the javascript event loop
    - [Javascript event loop explained](https://www.youtube.com/watch?v=8aGhZQkoFbQ&t=0s)
* **Asyncronous javascript** - Asyncronous javascript is a must-know in an area such as web development that handles requests between servers all the time. I HIGHLY recommend watching the video in javascript event loop if you haven't yet.
  - [Asyncronous javascript explained](https://www.youtube.com/watch?v=1Z7FjG--F20)
    * *Fetch api* - The fetch api is the standard way in javascript of "getting" data from some other computer by sending requests. There are many requests libraries out there but they are all based on the fetch API so you should make sure you understand it
      - [Fetch api explained](https://www.youtube.com/watch?v=cuEtnrL9-H0)
    * *Callback and callback hell* - Callbacks are functions that are passed to other functions as parameters and then called inside them. What tended to happen with asyncronous code is the "callback hell" which means a callback in a callback in a callback and so one which lead to some excruciating code.
        - [Callbacks explained article](https://javascript.info/callbacks)
    * *Promises* - Promises are the standard way in javascript to signal whether a asyncronous function was finished successfully or failed. They are what powers the entire asyncronous part of javascript.
        - [Promises explained in 10 minutes](https://www.youtube.com/watch?v=DHvZLI7Db8E)
        - [Promises basics](https://javascript.info/promise-basics)
        - [Promise chaining](https://javascript.info/promise-chaining)
    * *Promisify a function* - If you have a certain function that you want to run in an asyncronous manner because of performance issues, you have the option to promisify it by wrapping it with a promise
        - [Promisify a function](https://javascript.info/promisify)
    * *async/await* - Async/await was the way developers came up with to mitigate the callback hell issue and. This syntax is a nice abstraction over regular promises and callbacks which allows us to have nice looking code which is much more readable.
    * [*setTimeout and setInterval*](https://www.geeksforgeeks.org/java-script-settimeout-setinterval-method/)
* **Closures** - Closures are a widely used pattern in javascript that involves in a nutshell having function B declared inside function A and function B using function A params. The best example of closure is the decorator pattern.
  - [Closure explained](https://www.youtube.com/watch?v=3a0I8ICR1Vg)
* **Design patterns** - Design patterns are a number of programming lessons from our collective pool of knowledge. They are general programming knowledge that everyone should know about. These are only some of the patterns I considered to be most relevant, in reality there are a lot more than these.
    * *Resources*
        *  [Video playlist course](https://www.youtube.com/watch?v=v9ejT8FO-7I&list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc)
        *  [Visual and intuitive website](https://refactoring.guru/design-patterns/catalog)
        *  [Design patterns for humans](https://github.com/kamranahmedse/design-patterns-for-humans)
* [**Symbols**](https://javascript.info/symbol)
* [**Iterators**](https://www.youtube.com/watch?v=2oU-DfdWM0c)
* [**Generators**](https://www.youtube.com/watch?v=IJ6EgdiI_wU)
* **Advanced frontend specific concepts** - I also left here some frontend javascript specific topics that you might want to checkout such as using web workers for expensive operations and browser storage.
    * [*Web workers*](https://www.youtube.com/watch?v=Gcp7triXFjg)
    * [*Browser storage*](https://www.youtube.com/watch?v=GihQAC1I39Q&t=0s)
    * *Frontend development roadmap*

* [**Immediatly invoked functions**](https://www.youtube.com/watch?v=3cbiZV4H22c)

### 8. Code quality
- Code quality is important especially when working in teams or on a bigger project in general. It will dictate the speed of your development long term, the number of bugs you encounter and how good the codebase will become. There are a few notions you should know about code quality among of which is strict mode, good practices, standards and typechekers
* **Use strict** - Use strict is a javascript mode that is meant to reduce the number of bugs, make it more secure and more clean by introducing a set of rules that will enforce good practices and highlight potential pain points
  - [Javascript strict mode explained](https://www.youtube.com/watch?v=G9QTBS2x8U4)
* [**Ninja code ( must read !! )**](https://javascript.info/ninja-code)
* [**Common standards**](https://www.w3schools.com/js/js_conventions.asp)
* **Good practices** - Good practices are a set of guidelines that you should generally follow and keep consistent within your codebase. They are generally applicable to any programming language, so make sure to follow them
  - [Javascript best practices](https://www.youtube.com/watch?v=RMN_bkZ1KM0)
  - [10 javascript best practices](https://medium.com/@CodeWithMasood/10-javascript-best-practices-that-every-developer-should-know-aab2d5bccafc)
  - [Junior vs senior code](https://www.youtube.com/watch?v=g2nMKzhkvxw)

### 9. Typecheckers
- Typechecker are an industry standard at this point and are used in any serious project. They allow you to keep track of basic type inference, reducing greatly the number of bugs, making refactor much more easier and generally creating a more cohesive codebase. The 2 most common typecheckers are typescript ( which is the most popular and a standard for most frameworks ) and JSDoc, which despite being less used it's still a solid choice where you don't have to write type logic.
* **Typescript** - Typescript is the most widely used typechecker in the javascript ecosystem being the default choice of many frameworks and tools in the frontend ecosystem
    - [Typescript course playlist](https://www.youtube.com/watch?v=2pZmKW9-I_k&list=PL4cUxeGkcC9gUgr39Q_yD6v-bSyMwKPUI)
* **JSDoc** - JSDoc is a lightweight alternative to typescript, being considered better by some projects because it gives the type inference many developer crave but without having to write the type logic itself, only the specific comments for the type inference
    - [JSDoc course](https://www.youtube.com/watch?v=YK-GurROGIg&t=0s)

### 10. Consider continuing with
- Congrats on reaching the end of the roadmap !!! You should have now a solid grasp of all the javascript concepts you need to start working on a real project that uses javascript. Now you should specialize in a niche such as frontend or backend development and learn the specifics of that niche
* **Frontend development roadmap**
* **Backend development roadmap**


