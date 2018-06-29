## Threading

1. ### Download Manager
Difficulty: Expert

Allow your program to download various files and each one is downloading in the background on a separate thread. The main thread will keep track of the other thread’s progress and notify the user when downloads are completed.

2. ### Create A Progress Bar for Downloads
Difficulty: Intermediate

Create a progress bar for applications that can keep track of a download in progress. The progress bar will be on a separate thread and will communicate with the main thread using delegates.

3. ### Chat Application (remoting style)
Difficulty: Intermediate

Create a chat application which allows you to connect directly to another computer by their IP through the use of remoting and allow your “server” application handle multiple incoming connections.


4. ### Bulk Thumbnail Creator
Difficulty: Intermediate

Picture processing can take a bit of time for some transformations. Especially if the image is large. Create an image program which can take hundreds of images and converts them to a specified size in the background thread while you do other things. For added complexity, have one thread handling re-sizing, have another bulk renaming of thumbnails etc.

5. ### Multi-Threaded Logger
Difficulty: Intermediate

Imagine developing a very heavily multi-threaded application, and there is a bug that you cannot seem to figure out where it's from because almost everything is multi-threaded and running in the background. You figured out that what you need is a Logger class that logs errors, exceptions and successful completion of background tasks and supports multiple threads  writing to the logs at any point in time. Write the logger class and a simple multi-threaded application to test that the logger works. The advantage is that you will understand synchronization in multi-threaded applications and also how to structure applications that run lots of background tasks.
