* SSR (Server-Side Rendering)
	Server-Side Rendering in Next.js involves rendering pages on the server before sending them to the client. When a user requests a page, the server generates the HTML content dynamically, including data fetching if needed, and sends the fully-rendered page to the browser. This results in faster initial page loads and better SEO, as search engines can index the fully-rendered content.
* CSR (Client-Side Rendering)
	Client-Side Rendering in Next.js means rendering pages on the client's browser using JavaScript. The server sends a minimal HTML document along with JavaScript, and the browser executes the JavaScript to render the page. While CSR provides a more dynamic and interactive user experience, the initial page load might be slower, and search engines may face challenges indexing dynamic content.
	* CSR vs SSR
		[CSR vs SSR 18:25 to 27:00](https://www.youtube.com/watch?v=ZVnjOPwW4ZA&t=2270s)
		[Rendering control benefits](https://www.youtube.com/watch?v=r8nXMA_pf0w&t=300s)
* Advanced and specific cases 
	* SSG (Static site generation)
		Static Site Generation in Next.js involves pre-rendering pages at build time. During the build process, Next.js generates HTML files for each page, including the data needed for rendering. When a user requests a page, the pre-built HTML is served directly, resulting in fast and efficient page loads. SSG is excellent for content that doesn't change frequently and provides optimal performance and SEO benefits.
		[SSG vs SSR](https://aws.amazon.com/blogs/mobile/ssg-vs-ssr-in-next-js-web-applications-choosing-the-right-rendering-approach/)
	* ISR (Incremental Static Regeneration)
		Incremental Static Regeneration in Next.js enhances the static site generation approach by allowing for dynamic updates. With ISR, pages are initially generated at build time, but Next.js can also re-generate them at specified intervals or in response to user requests, without rebuilding the entire site. This enables a mix of static and dynamic content, ensuring that information stays fresh while maintaining the benefits of static site performance.
		[What is ISR](https://www.youtube.com/watch?v=nrfuN_Hyd3Y)