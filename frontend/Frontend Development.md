# Frontend development
### Essential Prequisites
* Basics of computer science - https://www.youtube.com/watch?v=8mAITcNt710
#### Recommended prequisites
* Git and github
* Problem Solving

For git and github nodes, add an attachment with the follwing

Git is a version control system made by linus torvalds, that is widely used in the current world. The videos below show an introduction to git and github that should get you started.
https://www.youtube.com/watch?v=HkdAHXoRtos - fireship
https://www.youtube.com/watch?v=RGOj5yH7evk&t=0s - freecodecamp

For problem solving
Problem solving is not defined by something clear, it is an abstract notion that cannot really be mastered by anyone, only barely touched. The only thing that will truly help you is thinking deeply and pushing your limits by making projects or solving some challenges.
https://www.youtube.com/watch?v=UFc-RPbq8kg - fireship
https://www.youtube.com/watch?v=r4TgqWbKRtA - tech with tim

0. How to learn web development and not lose your mind - What you are seeing in this roadmap is a HUGE amount of information. Web development is notoriously complicated to get started with, having a very complicated ecosystem. Despite this you should not feel discouraged. You should NOT KNOW everything especially as a beginner, what you should aim instead for about 50-70% of this roadmap topics is to "know that they exist" and have an idea of how they work. You should master you core that being javascript, html, css and a web framework and if you continue to be curious the rest will come along. I highly recommend going through all of the videos/resources and code along or at least be focused and understand everything and WHY it is done the way it is. I also left in many descriptions more humanly explanations for some concepts.

1. Internet and web - Internet powers our modern world and technologies. It is all around us and it is a good idea to understand it regardless of your professional activities. That being said, for frontend development you need to have a good grasp of at least the basics of the internet in order to start. I've selected what I deemed to be most relevant for this domain, since networking is a very large field
   A - How does the internet work?

   	1. Internet explained in 5 minutes - https://www.youtube.com/watch?v=7_LPdttKXPc 
   	2. How the internet works #1 (HTTP) - https://www.youtube.com/watch?v=wW2A5SZ3GkI&list=PL0yztVlNIsg6o9LnrSwJdJetwWV2ZpCLj&index=2
   	3. How does the internet works #2 - https://www.youtube.com/watch?v=0QI6I6APomE&list=PL0yztVlNIsg6o9LnrSwJdJetwWV2ZpCLj&index=3 
   	4. How does the internet works #3 - https://www.youtube.com/watch?v=QYXAxXjaKws&list=PL0yztVlNIsg6o9LnrSwJdJetwWV2ZpCLj&index=4

   B - What if the internet never existed

   	1. https://www.youtube.com/watch?v=tszFFafk8pA
   C - Networking course - Definitely not necessary, but I highly recommend this course, it really gives you insight into networking and a more broad base of knowledge about the internet. Feel free to skip it or watch it later if you want to advance faster through the roadmap.

   	1. Computer networking course - https://www.youtube.com/watch?v=IPvYjXCsTg8

2. Html
   A - Html basics - HTML is a markup ( not programming ) language that it's used to structure the blocks of a webpage. It is the clear starting point in web development

   	1. https://www.youtube.com/watch?v=HD13eq_Pmp8 - HTML course
   	2. https://www.youtube.com/watch?v=ok-plXXHlWw -  HTML in 100 seconds

   B - A taste of SEO- Despite not being important in the beginning, learning to do html the right way from the start can be of great advantage. So make sure to brush up this chapter at least

   	1. https://www.youtube.com/watch?v=JSm4aQl4w_U - Seo basics

   C - Html Semantic elements

   	 1. https://www.youtube.com/watch?v=bOUhq46fd5g

3. CSS
   A - Basics

   	1. I have yet to meet someone who tells me "Yes I know css". Try to understand how it works, not to master it, that will come with time. Right now you need only a grasp of its way of working
   	2. Bro code css - https://www.youtube.com/watch?v=wRNinF7YQqQ

   B - Master your layouts ( or regret you didn't do it )

   	3. Understanding the quirks that surround css is quite tricky, but mostly you have to know how those damn div's interact with eachother in different situations. I highly advise to take a good look at all these videos
   	4. Secret to css layouts - https://www.youtube.com/watch?v=vHuSz4fRM88
   	5. The joy of css grid - https://www.youtube.com/watch?v=705XCEruZFs
   	6. Css flexbox in 100 seconds - https://www.youtube.com/watch?v=K74l26pE4YA
   	7. Learn css flexbox - https://www.youtube.com/watch?v=phWxA89Dy94

   C - Responsive design

   	8. Responsive means in a nutshell make the website look good on all devices ( eg Laptop, phone ). Responsive design has become more and more important in the past few years and right now is an essential skill of any frontend developer. 
   	9. Media queries in 7 minutes - https://www.youtube.com/watch?v=yU7jJ3NbPdA&t=0s
   	10. How to make responsive design - https://www.youtube.com/watch?v=ZYV6dYtz4HA
   	11. Master media queries - https://www.youtube.com/watch?v=K24lUqcT0Ms	
   D - CSS animations

   	1. Learn css animations https://www.youtube.com/watch?v=SgmNxE9lWcY

4. Javascript -  https://www.youtube.com/watch?v=aXOChLn5ZdQ
   A - Basics of javascript - The basics of one of the most despised programming languages. The basics of the programming language made in 10 days. Despite its quirks and oddities, javascript remains one of the most widely used programming languages today, so you should better learn it, so you will now know how a programming language shouldn't look

   	1. Javascript - Bro code - https://www.youtube.com/watch?v=8dWL3wF_OMw
   	2. Javascript - SuperSimpleDev - https://www.youtube.com/watch?v=SBmSRK3feww

   B - Dom manipulation with javascript

   	3. Dom manipulation - https://www.youtube.com/watch?v=y17RuWkWdn8
   	4. Event listeneres  - https://www.youtube.com/watch?v=XF1_MlZ5l6M

   C - What the hell is nodejs? - I remember as a beginner hearing all these terminology about javascript and nodejs, but believe when I say I took at least a few months to actually differentiate between javascript and nodejs. In a nutshell javascript is a language that runs INSIDE the browser ( eg google-chrome ), while nodejs is THE ENGINE OF THE BROWSER extracted outside the browser to run javascript. Nodejs is generally used to build backends and server-side apps, BUT you can also write frontend code by writing Nodejs code and then using a MODULE BUNDLER to TRANSPILE it to plain vanilla javascript. Both 1. writing classic js or 2. using nodejs + a module bundler are valid ways of delivering a frontend application although the latter is a standard at this point. While Node.js itself isn't running in the browser, its ecosystem is instrumental in modern front-end development processes. It's like using a sophisticated toolset to build a car; the tools themselves aren't part of the car, but you wouldn't have the final product without them.

   	1. https://www.youtube.com/watch?v=ENrzD9HAZK4

   D - Javascript Is Weird

   	1. https://www.youtube.com/watch?v=sRWE5tnaxlI

   E - 100 javascript concepts - https://www.youtube.com/watch?v=lkIFF4maKMU&t=0s
   F - What is ecmascript ? - You should think of ecmascript like a BLUEPRINT and javascript as a language that follows that blueprint. Don't confuse the 2 of them

   	1. Javascript and Ecmascript - https://www.youtube.com/watch?v=nAdxWX7s3PY
   	2. ES6 modules - https://www.youtube.com/watch?v=cRHQNNcYf6s

5. How to do cool graphics-  There are a number of ways to achieve animations, graphics and effects on a website. Here are presented a few of those methods, but mostly they can be divided in 3 categories: Canvas graphics, Svg graphics and plain Js + css animations.  Svg is a container for vector based graphics which are easier in general to handle than canvas and "classic" animations are well, classic. They all have pros and cons so chose wisely. Also REMEMBER, All of the things listed above can be combined with each other !!

   A - Canvas - Canvas is well, a canvas on which you can "paint". The paint is done at each frame generally using requestAnimationFrame, and you have to repaint every second the newly moved or changed objects. Canvas is a low-level, flexible, efficient but hard to develop on solution

   	1. Learn canvas api - https://www.youtube.com/watch?v=gm1QtePAYTM
   	2. Canvas particle animations -  https://www.youtube.com/watch?v=vAJEHf92tV0

   B - Svg - Svg is a container for vector graphics. Svgs are widely used as icons in websites, but they can also have their own internal logic that handles the animations and transitions between vectors. There are also multiple websites that can generate Svgs that you can use in your code.  They are easier to manipulate than a canvas and highly customizable, but less performant especially for high number of objects.

   	1. Svg in 100 seconds -  https://www.youtube.com/watch?v=emFMHH2Bfvo
   	2. Awesome Svg animation - https://www.youtube.com/watch?v=UTHgr6NLeEw
   	3. Beautiful Svg curves - https://www.youtube.com/watch?v=lPJVi797Uy0
   C - Javascript + css -  The "classic" way of doing things, which has probably the most free-styling and multiple ways of achieving the same result. Keep in mind that javascript + css can be combined with svgs and canvas too so don't keep them separate if it makes sense to combine them.

   	1. Animating text with javascript - https://www.youtube.com/watch?v=GUEB9FogoP8
   	2. Professional scrolling effect - https://www.youtube.com/watch?v=C_JKlr4WKKs


5.  Javascript runtimes - See the "What the hell is nodejs" node for a more detailed explanation

	1. Nodejs explained - https://www.youtube.com/watch?v=XQT6XiJt4DE
	2. Deno - https://www.youtube.com/watch?v=F0G9lZ7gecE
	3. Bun ( it's buntime ) - https://www.youtube.com/watch?v=dWqNgzZwVJQ


6. Package managers - Package managers help us install and use other people's code. As simple as that! There are a few package managers out there, but npm is the most popular.
   1. What is npm ? - https://www.youtube.com/watch?v=P3aKRdUyr0s
   2. Why I switched to pnpm ? - https://www.youtube.com/watch?v=d1E31WPR70g

7. Bundling and transpilation tools - There are a set of tools that you need to know about and those are bundle tools and transpilers. Bundle tools take all your code and bundle it into a nice, thick set of optimized js, while transpilers ( babel being the most popular ) take javascript code and convert it into the old version that is compatible with all the browsers. For the most part you won't take any of these since they are automated in most frameworks, but you should have an idea of what they do and how they work.

   	1. Module bundlers explained - https://www.youtube.com/watch?v=5IG4UmULyoA
   	2. What is babel? - https://babeljs.io/docs

   A. Frontend development setup  - https://www.youtube.com/watch?v=IZGNcSuwBZs&t=0s


Project alarm ! - remember you need to always fix the information you have aquired and you've been hard at it!
Lets see some ideas. You should do at least one of these, preferably 2 of them.

1. The div race - Make 2 divs that race with each other !! One is controlled by an evil wizard which can accelerate the div speed with 10 pixels per second. The other is controlled by you! You have 2 buttons on the website. The first one needs can make your div move by 50 pixels per second, while the other will reset the speed of the other div to 0 ( so the wizard will start accelerating the div again ). Your goal is to make this website  work and win the game ! Good luck ! Tip: use a recursive setTimeout for the wizard functionality
2. Playlist saving app - A spiced up to do list that allows link embedings. You have to create a website in which you can: add, remove and edit playlist entries. An entry has a title and a link associated to it. You can edit both the title and the link of any entry. You can add and delete entries. You will also have a view-only mode in which you have the list of entried you can click that will send you over to the specific link
3. Make a sorting algorithm visualizer - Well if you do this one you can truly say you mastered the previous chapters and you can easily create a above average website. This one is part of a project that got Clement Mihailescu into google ( the founder of algoexpert.io ). You can see the video where he is presenting the project here. Your goal is to implement one of the algorithms in the sorting part. But if you see any other one you like, you should be able to do those too instead

   	 1. https://www.youtube.com/watch?v=n4t_-NjY_Sg

--- 
10. CSS advanced - A list of the professional ways you can write css. I found tailwind to be the most useful if you have a specific design for your website. UI libraries can be helpful if you want quick components that look fine for your projects or your company already uses one. Saas is basically css on steroids.

	A - Tailwind CSS - https://www.youtube.com/watch?v=mr15Xzb1Ook
	B - UI libraries -  Components libraries that you can use out of the box in your projects. These are some of the 3 most popular ones. They can be used in any project and are not specific to a framework

		1. Bootstrap - https://getbootstrap.com/
		2. Shadcn UI - https://ui.shadcn.com/
		3. Bulma - https://bulma.io/

	C - Saas  - https://www.youtube.com/watch?v=akDIJa0AP5c


11. Javascript Advanced - This section has some more advanced topics related to javascript
	A - Asynchronous javascript - Javascript functions such as api calls, fetching data or setTimeout can be asynchronous, so they don't behave like normal functions. I strongly recommend seeing the event loop video first as it is the best explained one can imagine. Down below I also

		1. Must see - asynchronous javascript - https://www.youtube.com/watch?v=1Z7FjG--F20
		2. Async explained episode - https://www.youtube.com/watch?v=vn3tm0quoqE
	B - Event loop and concurrency - https://www.youtube.com/watch?v=8aGhZQkoFbQ
	C - Closures - https://www.youtube.com/watch?v=vKJpN5FAeF4
	D - Fetch API - This is the standard way of getting or "fetching" data from an external server. You need a good idea of how asyncronous functions work in order to use this it. There are multiple libraries built on top of it such as axios that help abstract way some complexity

		1. The fetch API - https://www.youtube.com/watch?v=drK6mdA9d_M
		2. Get data from a REAL APi - https://www.youtube.com/watch?v=zUcc4vW-jsI



13. Testing - Like it or not, testing is an industry standard. Now WHY you should test your apps? Well,  for simple apps is mostly useless. The true value of testing appears when you have big apps, with multiple modules interacting with each other and you make a change and without knowing it you broke 3 features while adding the 4th. So you go back and fix the 3 initial features and now they work with the 4th one, but 2 unrelated things are not working anymore because of that code. This is an extreme example, but truth is a solid set of tests can ensure that your app still works after adding or changing something.

		1. Test-driven development - https://www.youtube.com/watch?v=Jv2uxzhPFl4

14. Javascript frameworks of never ending pain
	8.A How js frameworks came to be
	8.B Brief history of js frameworks
	8.C Established frameworks
	1. React
	2. Angular
	3. Vue

	8.D Hot and new
	4. Svelte
	5. Solid
	6. Qwick

	8.D 10 apps in 10 frameworks - https://www.youtube.com/watch?v=cuHDQhDhvPE
	8.E How to learn everything without learning everything?
15. Pick the "right" framework
16. State management
17. typescript
18. Testing advanced

Project alert !!
Build a Path visualizer algorithm


---
19. Basics of apis
	14.A How apis work
	14.B How to use an api?
	14.C Authentification
	14.D Databases
	14.E How to work with "pseudo-apis"
20. Performance
21. ways to render a webpage ( and how we came full circle )
22. SEO - advanced
23. Testing - advanced
24. Picking a meta framework
25. Topics that were not touched upon
	A. Application storage
	B. Cookies
	C. Security -https://cheatsheetseries.owasp.org/cheatsheets/Third_Party_Javascript_Management_Cheat_Sheet.html
26. Deployment and Hosting
27. Becoming a high value frontend developer
28. Libraries you might want to check out
	A. D3js
	B. Threejs
	C. Framer motion
	D. Chart.js

29. What is next?
	A. Project ideas
	B. Fields to expand into

	
