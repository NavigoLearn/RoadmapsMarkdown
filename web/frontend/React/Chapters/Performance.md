* Use production builds
	Production builds are the final, optimized versions of a software application that are ready for release to end-users or deployment on live servers. These builds are tailored for performance, efficiency, and security, and they have been thoroughly tested to ensure reliability and stability in real-world environments. Basically optimisation just before launch.
	[Production build explained](https://www.youtube.com/watch?v=BbncM2nzCso)
	[Production build vs development build](https://www.linkedin.com/pulse/webpack-production-build-vs-development-prasenjit-sutradhar/)
* Lazy loading vs eager loading
	Lazy loading in React is a technique for optimizing the loading of components in a web application. It involves delaying the loading of certain parts of the application until they are actually needed, rather than loading them all at once when the application initially loads. This can improve the application's performance and reduce the initial load time.
	[Lazy loading vs eager loading](https://www.imperva.com/learn/performance/lazy-loading/)
	[React router lazy loading](https://www.youtube.com/watch?v=MJn4W7pR6RU)
	[Lazy load for images & explanation](https://www.youtube.com/watch?v=hJ7Rg1821Q0)
* Code splitting
	Code splitting in React is a technique that optimizes the performance of web applications by breaking the code into smaller, more manageable chunks. Instead of sending the entire application code to the user's browser at once, it allows you to load only the code needed for the current view or feature, reducing initial load times. This is typically achieved through dynamic imports or tools like Webpack, enabling faster page loading and a better user experience.
	[Code splitting explained & usage](https://www.youtube.com/watch?v=JU6sl_yyZqs)
	[Advanced code splitting](https://edvins.io/react-code-splitting-techniques)
* React profiler
	The React profiler browser extension allows developers to record a session while using a React app in development mode. Once recorded, the profiler displays a flame graph, alongside other information on how React rendered each component.
	[React profiler tutorial](https://www.youtube.com/watch?v=Qwb-Za6cBws)
	[Full concept](https://legacy.reactjs.org/blog/2018/09/10/introducing-the-react-profiler.html)
* Tree shaking
	React tree shaking is a concept in React that refers to the ability of a build tool, like Webpack, to eliminate or "shake off" unused React components or code during the build process. This optimization reduces the size of the final JavaScript bundle, making your application load faster and use less memory in the browser.
	[Bundle size problem](https://www.youtube.com/watch?v=kwUfeWe7DCw)
	[Tree shaking on webpack](https://www.telerik.com/blogs/tree-shaking-basics-for-react-applications)
* Virtualisation for long lists
	Virtualization in React is a technique for rendering long lists efficiently by only rendering the items that are currently visible within the viewport of a scrollable container. This approach improves performance by avoiding the rendering of off-screen elements, which can be especially beneficial when dealing with large datasets, as it minimizes the amount of DOM manipulation and increases the speed of your application.
	[Virtualisation explained](https://web.dev/articles/virtualize-long-lists-react-window)
	[Virtualisation usage video](https://www.youtube.com/watch?v=UrgfPjX97Yg)