1. Into the JSX
	* What is JSX (for starters)?
		JSX is an HTML-like syntax used by React that extends ECMAScript so that HTML-like text can co-exist with JavaScript/React code, an easier way to write javascript, and can be used in various ways.
		[What is JSX?](https://www.youtube.com/watch?v=9GtB5G2xGTY&t=257s)
			
		* JSX, syntax extension for JavaScript
			Below you have a list of resources which will help you better understand what JSX is all about, make sure you go through each one of them! They are very important!
			[Examples of usage](https://en.wikipedia.org/wiki/JSX_(JavaScript))
			[Conditional rendering](https://www.youtube.com/watch?v=Rr5AqASIyxw)
			[Cheat sheet](https://www.codecademy.com/learn/bwa-intro-to-react/modules/react-101-jsx-u/cheatsheet)
			*  a little exercise
			You will use JSX to manipulate the DOM's appearance. Make sure you have Node.js installed and for this exercise we will use Vite to initialise our project(you can use any method presented at the Set up Node).
			Once you create you Vite + React project go into src/App.jsx (or .tsx) delete everything inside the angle brackets, write a header tag inside which there is a h1 element with the text "I am learning JSX!" and a p with the text "This is a simple practice JSX!" and then create another p tag which renders and equation like {2 + 6} and then try to conditionally render it using ? and &&. Feel free to play around maybe implement some of the logic from the previous article.
		* JSX, Syntactic Sugar for JS
			Not necessary a must know but Syntactic Sugar is a way of writing everything more compact and way prettier, I highly encourage you to learn it because it makes your code more readable and professional
			[JS Syntactic Sugar](https://sophiali.dev/syntactic-sugar-examples-javascript)
			[JSX is Syntactic Sugar for JS](https://fettblog.eu/jsx-syntactic-sugar/)
		* JSX attributes (brief explanation)
			Just like in html where we have an 'alt' attribute to an anchor tag, our JSX element have also such attributes almost the same but a little different. There are some key differences: class becomes className, for becomes htmlFor. Custom Attributes: JSX allows you to pass custom attributes or data using curly braces, e.g., `{myCustomAttribute: 'someValue'}`, which is not possible in HTML.
			Boolean Attributes: In JSX, boolean attributes like `disabled`, `checked`, or `readOnly` are typically expressed without values. If the attribute is present, it's considered true. In HTML, boolean attributes are often written with or without values.
			Style Attributes: In JSX, the `style` attribute accepts an object with camelCased property names (e.g., `backgroundColor`) for inline styles, while in HTML, the `style` attribute typically uses hyphen-separated property names (e.g., `background-color`).
			[Brief explanation](https://www.youtube.com/watch?v=BvBf8GjsYdw)