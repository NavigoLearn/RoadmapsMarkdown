**General Resources**
- [Swift Basics YouTube Playlist](https://www.youtube.com/playlist?list=PLwvDm4VfkdpiLvzZFJI6rVIBtdolrJBVB)
- [Develop in Swift Fundamentals](https://books.apple.com/us/book/develop-in-swift-fundamentals/id1511184145)

**0. About**
- Swift is THE programming language if you want to code and build apps that run on Apple Software, and there's no way around it. Swift provides all of the tools you would ever need for developing an app from the ground-up, for iOS, MacOS, iPadOS, WatchOS and every other AppleOS you could think of. 
- For this section of the roadmap, if you want to try writing code yourself while going through the nodes, instead of creating a new Swift project, you can just create a playground. Open Xcode, and on the status bar click File -> New -> Playground. Create a "Blank" one, and name it whatever you like. Once you've created your Playground, on the left of the window you'll see the navigator where there will be a Swift Icon next to the name of your Playground, Right Click on it -> New Playground Page. Here you can try writing all sorts of code, without using bulky Xcode projects while you get used to the Syntax and principles of writing Swift Code. As you can see inside of the Editor, you will have your lines numbered from 1 to n lines (n being the number of lines you have in your Playground Page), along with a Play button. Click on the Play button, and your code will run.
- For starters, I also recommend to check out Fireship's Swift in 100 seconds video to get to know what you're going into
	- [Swift in 100 Seconds](https://www.youtube.com/watch?v=nAchMctX4YA)

**1. Comments**
- The foundation of writing code are comments. Comments are used thoroughly by all developers around the world, and if you want to code, you should write them too! Think of it as taking notes whithin your app. 
	- [Swift Documentation for Comments](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/thebasics/#Comments)
	- [Swift Comments and Why you should use them](https://www.programiz.com/swift-programming/comments)
	- [How to better Document Swift Code](https://www.youtube.com/watch?v=2DODdEhsrWA&ab_channel=EmmanuelOkwara)

**2. Types in Swift**
- All types, examples, and usages of types - what to use in specific situations and how to keep track of them
	- Constants and Variables
		- [How to use Variables and Constants](https://www.youtube.com/watch?v=jRNa6hYTJLo&list=PLwvDm4VfkdpiLvzZFJI6rVIBtdolrJBVB&index=4&ab_channel=SwiftfulThinking)
		- [The Basics - Constants and Variables](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/thebasics#Declaring-Constants-and-Variables)
	- Basic Types (bool, integer, string)
		- Declaring constants can be somewhat confusing at first for knowing what variable is of what type, but one great way to making sure that you know exactly what you are doing is to directly specify the type of the variable you plan on using (e.g., `var greeting: String = "Hello, sir!"`)
			- [How to use basic Types](https://www.youtube.com/watch?v=JeoaCW9fO0w&list=PLwvDm4VfkdpiLvzZFJI6rVIBtdolrJBVB&index=3&ab_channel=SwiftfulThinking)
			- [Integers](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/thebasics#Integers)
			- [Floating-Point Numbers](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/thebasics#Floating-Point-Numbers)
		- [Strings and Chars](https://www.youtube.com/watch?v=NbkPGvalyUU&ab_channel=DarrellRoot)
		- [Booleans](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/thebasics#Booleans)
		- [Tuples](https://www.youtube.com/watch?v=zsjCrtENsZA&ab_channel=SwiftfulThinking)
		- [Optionals !!!!](https://youtu.be/PDWNf4pBI64?si=Jy_ViWkKgt_BlXlG)
		-  Type Safety and also Type Inheritance
			- Swift is a Type-safe language, meaning you must keep track of a variable's type and make sure that you won't declare a String EXAMPLE1 (e.g., `var EXAMPLE1 = "Hello, sir!"`, and an Integer EXAMPLE2 (e.g., `var EXAMPLE2 = 4`) and try to do EXAMPLE1 = EXAMPLE2, because it won't work. 
				- [Type Safety and Type Inheritance](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/thebasics#Type-Safety-and-Type-Inference)
	- Functions - very important! The core of Swift is just writing Functions that call other Functions upon Functions (hard to comprehend at first, but will get a lot easier down the line)
		- [How to use Functions in Swift](https://youtu.be/kr3SSplrJlw?si=AZ_Vq4DBUsum3-JR)
	
**3. Non-Primitive Data Types in Swift**
-  O*bject*O*riented*P*rogramming* (Struct vs Classes, Stack vs Heap)
	- Object Oriented Programming is based on the premise that we design code around data and objects instead of functions and logic. It's a very essential concept used in almost every language, so YOU MUST understand it if you want to build AppleOS apps.
		-  [What is Object Oriented Programming](https://youtu.be/XdZUVmqIkJE?si=0_ZoGvBmRxBVY2Wm)
	- Enums in Swift
		- Enumerations are used to define a group of related values with the ability to work with them using a type-safe way
			- [Enums in Swift](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/enumerations/)
			- [How to use Enums](https://www.youtube.com/watch?v=YPUCML__Md8&list=PLwvDm4VfkdpiLvzZFJI6rVIBtdolrJBVB&index=11)
	- Structs in Swift
		- Used to store different types of data types, not just Integers, Strings or Booleans
			- [Swift Structs Basics](https://www.programiz.com/swift-programming/structs)
			- [How to use Structs](https://youtu.be/gRKlprUj-I8?si=zCqPpPLISMYeMes3)
	- Classes in Swift
		- Classes are used to define objects, and they are very alike to Structs, but Classes are used to defined much more complex Objects. The general rule is to prefer the using of Structs as opposed to Classes, and only use them if you absolutely need to.
		- [Classes in Swift](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/classesandstructures)
		- [How to use Classes in Swift](https://youtu.be/xJgtknc-7CA?si=o1KVXWn6lXWqzHNN)
	- Access Control
		- Literally what the name suggests, it ensures a way to control which files are accessible from what part of your project. This is useful for hiding implementation details of the code and to specify a preferred interface for which our code can be used through
			- [Access Control Documentation](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/accesscontrol/)
			- [How to use Access Control](https://youtu.be/UbX2UtgZTJI?si=1i9o1J1w_l5VJU3a)
	- Arrays 
		- This is a Collection Type
		- One of the most commonly used data types in an app, useful for organizing the data. You can also define array of single elements if you like, but there's generally a better way of doing that instead of using Arrays
			- [Learn all about Swift Arrays](https://www.tutorialspoint.com/swift/swift_arrays.htm)
			- [How to use Arrays](https://www.youtube.com/watch?v=rNyTxjGSp8Q)
	- Sets
		- This is a Collection Type
		- Sets are literally collections of unique data, just like Arrays. But the difference lies in the fact that Sets DO NOT ALLOW for duplicates, while Arrays don't have this restriction.
			- [Learn all about Swift Sets](https://www.programiz.com/swift-programming/sets)
			- [Sets in 60 seconds](https://www.youtube.com/watch?v=iotojg2MgGQ)
	- Dictionaries
		- This is a Collection Type
		- Just like Sets, they store unique values but using keys, and also being unordered
			- [All about Dictionaries](https://www.tutorialspoint.com/swift/swift_dictionaries.htm)
			- [How to use Dictionaries in Swift](https://youtu.be/ctBEqA0wh3M?si=En_hX_LczWCAaZM3)

**4. Flow Control in Swift (Loops and Conditionals) - also mentioned inside of the functions video**
-  If Else Conditionals - exist in every language, basic principles of coding
	-  [Conditionals for Beginners](https://www.youtube.com/watch?v=9Snw7polcBU)
	- For, While, Repeat - the three horseman of loops (the fourth one didn't make the cut)
		- [Swift for Beginners - Loops](https://www.youtube.com/watch?v=9Snw7polcBU)
		- [How to use For Loops  in Swift](https://www.youtube.com/watch?v=7hAmXRwBQxc&list=PLwvDm4VfkdpiLvzZFJI6rVIBtdolrJBVB&index=16)
	- Guard Statements - like if statements but it always has an else clause and the condition is checked before entering the closure, were also mentioned in the Functions video
		- [Swift for Beginners - Guard Statements](https://www.youtube.com/watch?v=DTd7HHSAw-4)
		- [Functions - Guard Statements](https://youtu.be/kr3SSplrJlw?si=d1Vo24yGi5jReyrf&t=1442)
	- Defer statement - executed only when the program exits, generally used for cleanup of code
		- [All you need to know about defer](https://www.linkedin.com/pulse/power-defer-swift-ramdhas-m#:~:text=In%20Swift%2C%20the%20%22defer%22,before%20the%20scope%20is%20left.)
		- [Defer Functions Docs](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/controlflow/#Deferred-Actions)

**5. Collection Types Operations (Sort, Filter, Map)**
- Filter - as the name implies, filters a specified collection type by given predicate
	-  [How to Filter an Array in Swift](https://www.logilax.com/swift-filter-array/)
	- Sort - as the name implies, sorts the collection type in a specified order
		- [How to use Sort in Swift](https://www.geeksforgeeks.org/sorting-an-array-in-swift/#:~:text=To%20sort%20the%20array%20we,the%20array%20in%20ascending%20order.)
	- Map - transforms the collection type by performing a specified operation on the type.
		- [How to Map in Swift](https://cocoacasts.com/swift-essentials-1-how-to-use-swift-map-to-transforms-arrays-sets-and-dictionaries)
	- General Resource good for all three of these things
		- [How to Filter, Sort, and Map in Swift](https://youtu.be/NkOU60vwUEY?si=67RJ-Lkc-5Zzk3lY)

**6. Using Protocol in Swift (used for things later down the line, it's a bit high-level but MUST be understood now)**
- A protocol is used to define requirements (think of it as laws) that must be met in order to create a specific functionality of an app
	- [What is a Protocol in Swift](https://youtu.be/nJmrkRlRu88?si=MWDCY5TcLNPBi8L4)
	- [Define and use Protocols](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/protocols)

**7. Closing chapter notes**
- Alright, this is the end of this chapter. If you feel like you don't fully understand something *apart from Protocol which we will get into later again*, please make sure to re-read it and also try writing code with it yourself so that you don't get lost when we get into more complex stuff. From now on, you'll learn all about SwiftUI