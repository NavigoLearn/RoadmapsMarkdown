# 3. The Fundamentals of Svelte
- In this section, you'll dive into the core concepts of Svelte including Components, Rendering Logic, Component Communication, and Reactivity.

## 3.A Svelte Components
- Learn about the building blocks of a Svelte application: components.
- 3.A.1 Using props in Svelte
    - Discover how props can be used to pass data to components in Svelte.
    - [Video - Props in Svelte](https://www.youtube.com/watch?v=Y1McRGLkxQc) - The Net Ninja
    - [Documentation - Props in Svelte](https://svelte.dev/docs/basic-markup#attributes-and-props) - Svelte Docs
- 3.A.2 Component lifecycle
    - Understand the lifecycle of a Svelte component and how you can hook into different stages of it.
    - [Video - Svelte Component Lifecycle](https://www.youtube.com/watch?v=e4xzh_WKgm4) - lihautan
    - [Documentation - Runtime Svelte](https://svelte.dev/docs/svelte) - Svelte Docs 
## 3.B Rendering Logic
- Master the rendering process in Svelte, including conditional and list rendering.
- 3.B.1 Conditional Rendering
    - Learn how to conditionally control the rendering of components in Svelte.
    - [Video - Conditional Rendering](https://www.youtube.com/watch?v=QqvxWXrtV2w) - Codevolution
    - [Example - Context Reactivity](https://stackoverflow.com/a/59908235) - rixo on Stack Overflow
- 3.B.2 List Rendering
    - Find out how you can use lists and how to render multiple components in Svelte.
    - [Video - List Rendering](https://www.youtube.com/watch?v=LwuSqc0u2Dc) - Codevolution
    - [Interactive Documentation - Each blocks](https://learn.svelte.dev/tutorial/each-blocks) - Svelte650015
## 3.C Component Communication
- Delve into the methods that Svelte provides for components to communicate with each other.
- 3.C.1 Parent-Child Component interaction
    - Take a look at how parent and child components communicate in Svelte.
    - [Video = Svelte State Management Guide](https://www.youtube.com/watch?v=4dDjQiOVrOo) - Joy of Code
- 3.C.2 Dispatching Custom Events
    - Understand how custom events can be used to execute parent component functions from child components.
    - [Video - Dispatching Custom Events](https://www.youtube.com/watch?v=xuDRfbHkpZs) - Evan Does Tech
## 3.D Reactivity in Svelte
- In Svelte, you use the $: syntax to mark a statement as reactive. Whenever the variables used within that statement change, the statement will re-run. This can be used with any valid JavaScript statements, including conditional statements, loops, etc.
- [Video - Reactive Declarations](https://www.youtube.com/watch?v=3QrKr1m8U8A) - Codevolution
- [Documentation - Reactive Declarations Limtations](https://svelte.dev/docs/typescript#limitations-reactive-declarations) - Svelte