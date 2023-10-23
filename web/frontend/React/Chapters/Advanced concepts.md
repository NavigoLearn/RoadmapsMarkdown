* Advanced React patterns
	These patterns may prove useful when we are dealing with a larger and more complex application, breaking it down into smaller pieces and making everything work together, with a significant amount of logic in between.
	* HOC
		Higher Order Components (HOCs) are a design pattern in React that allow you to reuse and enhance the functionality of your components. They work by taking a component as input and returning a new component with additional props, state, or behavior. This is helpful for sharing common functionality, such as authentication or data fetching, among multiple components without duplicating code. HOCs promote code reusability and maintainability in your React applications. It is also my favourite.
		[HOC explained text](https://www.freecodecamp.org/news/higher-order-components-in-react/)
		[Simple example](https://www.youtube.com/watch?v=J5P0q7EROfw)
		[More complex example](https://www.youtube.com/watch?v=eyh04fR9z2g)
	* Render props
		[Render Props and HOC](https://www.youtube.com/watch?v=axL59Dc5rZA)
		[Render props example](https://www.youtube.com/watch?v=ix4z_jUrQpQ)
		In the "render props" pattern in React, you pass a function as a prop to a component, and this function is responsible for rendering content or providing data. This makes the component more versatile because it lets you change how the component displays data without modifying the component itself, making it a flexible and reusable building block in your application.
	* Container pattern
		[What is container pattern?](https://medium.com/@vitorbritto/react-design-patterns-the-container-presentational-pattern-775b91aa0c49)
		[Container pattern usage](https://blog.openreplay.com/understanding-the-container-component-pattern-with-react-hooks/)
	* State Initializer Pattern
		The "state initializer" pattern is a React pattern used to set the initial state of a component. Instead of directly setting the initial state in the constructor, you initialize it using a function or expression. This pattern is especially useful when the initial state depends on props, as it allows you to compute the initial state dynamically based on the incoming props, ensuring that the state reflects the component's specific starting conditions. It can help with making your component more predictable and flexible, particularly in cases where the initial state is not static but needs to be determined at runtime.
		[Explanation & usage](https://www.dhiwise.com/post/for-better-performance-state-initializer-pattern-in-react)
* [React reconciliation](https://www.educative.io/answers/what-is-the-concept-of-reconciliation-in-react)
* Debouncing and Throttling
	Debouncing and throttling are React patterns that control the rate of executing a function.
	
	Debouncing delays a function until a pause in input, ensuring it only runs after a certain period of inactivity. This is useful for handling events like search input.
	
	Throttling limits the frequency of function calls to a fixed rate, preventing it from executing more often than allowed. This is handy for tasks like scroll or resize events to reduce the rate of execution and conserve resources.
	[Debouncing and Throttling in 16 mins](https://www.youtube.com/watch?v=cjIswDCKgu0)
