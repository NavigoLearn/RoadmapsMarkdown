* You can use all of them but I encourage you to pick one and master it.
* Prop drilling
	Prop drilling, in React, occurs when you must pass data through multiple intermediary components in the component hierarchy, even if those components don't directly use the data. This can lead to more complex and less maintainable code. It's often addressed with state management tools like React Context or Redux, which enable data sharing across components without the need for extensive prop passing, yet in small application you can use it (I didn't tell you that).
	[Prop Drilling](https://www.youtube.com/watch?v=QLO64jkGkRg)
* Context API (advanced)
	Some advanced concepts worth mentioning if you chose to work with context api in your project.
	[Context Api](https://www.youtube.com/watch?v=t9WmZFnE6Hg)
	[Context Hack](https://www.youtube.com/watch?v=I7dwJxGuGYQ)
* Redux
	Developers have increasingly sought alternatives to the Context API and React's internal state management, especially in larger projects where they can become unwieldy and complex to manage. An option for global state management often considered is Redux, which, despite some controversies, is widely viewed as a popular and effective tool for this purpose.
	[Redux course](https://www.youtube.com/watch?v=zrs7u6bdbUw)
* Zustand
	Zustand is a state management library for React that simplifies and streamlines the way you handle application state. It offers a straightforward, hook-based API for creating and managing global or local state, making it easier to organize and access data in your React components. Zustand is known for its simplicity and minimalistic approach, reducing the complexity often associated with other state management solutions like Redux, while providing powerful tools for efficiently handling state in your applications.
	[Zustand vs Redux](https://www.youtube.com/watch?v=DK-S4ZcmDcE)
	[Zustand course](https://www.youtube.com/watch?v=fZPgBnL2x-Q)
	[Usage example](https://refine.dev/blog/zustand-react-state/#build-a-to-do-app-using-zustand)
* Nanostores
	May not be as widely known as some other libraries on this list, but it's my personal favorite. It offers a simpler entry point and usage compared to the others. The only downside is that if you don't handle your stores correctly, it can become messy, especially when dealing with module imports.
	Fun fact: Navigo uses Nanostores as the primary state management tool!
	[Nanostores explanation](https://github.com/nanostores/nanostores)
	[Video explanation](https://www.youtube.com/watch?v=gVTAZOryDAo)