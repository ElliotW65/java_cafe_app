# F21AS Advanced Software Engineering Group Coursework

This is a multi-threaded application that manages a queue of orders at a cafe.

When the app is started a queue of order is read into the application and servers begin fulfilling the orders. Each server is run on a different thread allowing the application to scale and handle a large number of orders simultaneously.

To manage the multiple threads, the observer-subscriber design pattern is used where orders are pushed to a shared object and are picked up by server threads when they complete their previous order.

The application is interactive as users have the ability to add new servers (and therefore new threads), add orders to the queue and change the time taken for servers to process orders.

The Model View Controller (MVC) design pattern is used to manage the applications interaction with the GUI.

To run the app, run the Executable Jar File “app”.

