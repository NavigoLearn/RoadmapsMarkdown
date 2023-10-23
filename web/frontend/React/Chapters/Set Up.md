1. 1 What are ES Modules?(main)
		ES modules in JavaScript are basically exportable files which can then be imported in any other file.
		[ES modules explained](https://www.youtube.com/watch?v=qgRUr-YUk1Q)
			* 1.1 What are module bundlers & why are they useful?
		 Module bundlers are tools used in web development to simplify and optimize code. They take separate pieces of code (modules), organize them, and create smaller, faster files. This process makes it easier for developers to work on projects by managing dependencies and improving the development workflow. When websites are ready for the public, the bundlers create efficient bundles that load quickly for users, enhancing the overall performance of web applications.
		 i. [Module bundlers explained - Fireship](https://www.youtube.com/watch?v=5IG4UmULyoA

	1.2 Using  module bundlers
	* **Create React App**(Main)
		The "create-react-app" method is a user-friendly way to set up React.js projects quickly. It streamlines project initialization, automating setup tasks. While it offers less customization compared to manual configurations, it is widely preferred for its simplicity and accessibility, making it an excellent choice, especially when creating a quick React test app.
			[Create react app](https://www.youtube.com/watch?v=HWpjpq2ux04)

	* **Vite**(Main)	  
		Vite is a modern tool that helps developers build websites quickly. It's all about speed and simplicity. When you're working on your website, Vite doesn't bundle your code together, which makes things faster. It uses a cool thing called 'zero-config,' meaning you can get started without doing much setup. 
		To make an application with React + Vite, watch the video or read the article
			[Vite in 100 seconds](https://www.youtube.com/watch?v=KCrXgy8qtjM&t=18s)
			[Vite + React Setup - Video](https://www.youtube.com/watch?v=agpZsCUllqc)
			[Vite + React Setup - Article](https://vitejs.dev/guide/)
			[Use Vite](https://www.youtube.com/watch?v=9OmnmouE6tw)
		
	* **Parcel**(resource)
		Parcel is perfect for small to medium projects with its easy 'zero-config' setup, like Vite. It automatically optimizes bundles, simplifying development. Meanwhile, Vite focuses on speed, prioritizing rapid development. Parcel's simplicity suits straightforward projects, while Vite excels in performance-critical scenarios.
			[Parcel Guide](https://www.youtube.com/watch?v=U7CQE1TFMkg)

	* **Razzle**(resource)
		Razzle is designed for Server-Side Rendering (SSR), and it automates the setup process so you can jump into coding without hassle. Opt for Razzle when you need a fast and straightforward method to build server-rendered React applications, especially if you prefer to avoid dealing with complex configurations.
			[Razzle Guide](https://www.youtube.com/watch?v=u1J9De4bHmU)
			
	* **Snowpack**(resource)
		Snowpack is a little tricky and different from the traditional approach, remember when we learnt about ES Module? Well, snowpack allows you to import dependencies directly in the browser, resulting in faster development builds. It leverages the ES Modules and focuses on "bundless" development.
			[Snowpack Setup](https://www.snowpack.dev/tutorials/quick-start)

	1.3 Without module bundlers
	* **Manual Setup (Webpack and Babel)**(main)
		Good for educational purposes, I highly recommend using manual setup initially to understand how the processes unfold. It may be suitable for small projects if you choose not to use module bundlers. However, it's important to note that there are numerous disadvantages compared to using a module bundler.
		[Create app manually (much to learn)](https://www.youtube.com/watch?v=h3LpsM42s5o)