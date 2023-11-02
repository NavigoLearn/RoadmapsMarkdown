- [MVVM](https://adevait.com/ios/swift-tutorial-mvvm-design-pattern#) stands for Model-View-ViewModel. What it does is it describes the flow of data within our app and separates application tasks(handling of the UI, the backend such that the view is not dependent on any specific model problem).
	- Model - responsible for representing the data from our backend logic
	- View - responsible for handling all the layouts and displaying the data
	- ViewModel - responsible for transforming data recieved in a View, recieving actions from the View, dealing with logic
- It's really complicated at first, and I recommend to read and watch a bunch of videos on it so that you get the idea, but what we want to achieve by using this design pattern is basically separate the UI of our app with the logic that rests in the back of the app (backend) and using a kind of controller (transformative) layer between them so that the flow of the app is smooth.
	- [MVVM Swift: Model View ViewModel Design Pattern](https://youtu.be/qzXJckVxE4w?si=w2_sskYXJW5PN8s0)
	- [How to use MVVM with Async Await](https://youtu.be/OpJcInSZpc8?si=Qxqn6rgLDMV9X_-F)