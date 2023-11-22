* Ensure that you have nodejs installed on your machine
	* [Module Bundlers explained](https://www.youtube.com/watch?v=5IG4UmULyoA&t=1s)
	* Nextjs bundling
		Next.js 13 uses Webpack as its module bundler by default. Webpack is a popular open-source JavaScript module bundler that helps bundle and manage project dependencies, including JavaScript, CSS, and other assets. It enables code splitting, lazy loading, and efficient bundling of resources for web applications. It is a good thing to know if you ever want to change the configuration of your project.
		The founder of Webpack, Tobias Koppers, collaborates with the Vercel team to implement TurboPack, a new module bundler written in Rust. Claiming to be extremely fast and reliable, TurboPack, as of the Next.js 14 update, is still in beta. However, it has demonstrated impressive performance improvements, such as up to **53.3% faster** local server startup and up to **94.7% faster** code updates with Fast Refresh. Currently, its usage is limited to the development server, and I encourage you to give it a try.
		   [What is turbopack](https://www.youtube.com/watch?v=6ZwnBI4Rb1w)
		   [Why turbopack](https://turbo.build/pack)
	* [Create a nextjs project](https://nextjs.org/docs/pages/api-reference/create-next-app)