1. React Components
	* Components analogy
		Think of React components like building blocks in a LEGO set.
		In a LEGO set, you have various types of pieces, each with a specific shape and function. These pieces can be combined in different ways to build complex structures like castles, cars, or robots. Similarly, in a React application, components are like those LEGO pieces. Each component is a self-contained piece of your user interface with its own structure and behavior.
		You can create different types of components, such as buttons, headers, forms, or even custom components like a "LEGO mini-figure." Each component can be reused and combined with others to construct your web application, just as you would assemble LEGO pieces to build a larger structure.
	* Component classes vs Functional components
		 Class Components: These are the traditional way of creating components in React. They are defined as JavaScript classes and can manage state and lifecycle methods.
		 Functional Components: These are modern and concise. They are defined as JavaScript functions and don't manage state or lifecycle on their own.
			[Brief state understanding](https://www.youtube.com/watch?v=g8-Xrpl_Uhk)	
			[Class Components vs Functional Components](https://www.youtube.com/watch?v=yc6elaGOoGQ)
			   * Components explained
			[Components explained video](https://www.youtube.com/watch?v=JtB_tippTUQ&t=488s)
		* Events
			Events like onClick, onHover, onMouseUp, onMouseDown, onSubmit (for forms), and onChange (commonly used with inputs) are all accessible and controllable in React.
			[Events](https://www.youtube.com/watch?v=0XSDAup85SA)
		* Components lifecycle
			This concept will be important when we touch Hooks in the next chapter, so just briefly understand it for now.
			[Lifecycles explained](https://www.youtube.com/watch?v=qnN_FuFNq2g)
		* A little exercise
			In your React application I want you to have 2 components. 1. The header of the page where it would have a simple text "Hey this is my first React component", using JSX. 2. A button which has an action when you click it that renders a random number out of an array, Array=[1, 2, 3, 4, 5]. You have an example below on how to use components together
			[Example](https://www.youtube.com/watch?v=NJ_qbsLf52w)
1. Components props
	 Component props in React are like the instructions you give to a component. They are pieces of data that you pass to a component so it knows how to display and behave. For example, if you have a "Button" component, you can give it props like "label" to specify the text on the button, and "onClick" to define what happens when you click it. Props are a way to customize and reuse components throughout your application.
	 [Props simple explanation](https://www.youtube.com/watch?v=kHJSNFU7H4U)
	 [Clean an reusable components with props](https://www.youtube.com/watch?v=Ib-80HIjuZ4&t=639s)