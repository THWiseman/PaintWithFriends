# PaintWithFriends
# Introduction
A C++ collaborative painting app with built in networking code, as well as text, audio, and video chat. Created Fall 2021 for Mike Shah's CS5500 Software Engineering Course. Authors are Tom Wiseman, Dennis Ping, Michael Maquera, and Rajwinder Singh. By request of the professor, the source code is not publicly available.


![PaintWithFriends](https://user-images.githubusercontent.com/77803506/148086189-a1544e01-7ba3-41c5-b5a5-b44455650858.JPG)

# Features
- Full featured, collaborative and synchronous painting app, including color picker, undo/redo and paint tools.

![AnimatedUndo](https://user-images.githubusercontent.com/77803506/148088043-90dd2d85-93f9-452f-9a7f-1e8fc6e411b1.gif)

![PaintWithFriendsColorPicker](https://user-images.githubusercontent.com/77803506/148088174-6520ff88-2719-4897-934b-d11a4811f5d2.JPG)

- Independent server application that manages multiple TCP and UDP connections for any number of clients.  

- Video and Audio Chat

- Text Chat

![PaintWithFriendsTextChat](https://user-images.githubusercontent.com/77803506/148088207-cf4257c1-1e3f-4b17-a769-4a14076f83b3.JPG)

- Windows/MacOS Compatible

# External Libraries

- SFML Library used for capturing user input, creating and displaying a Window, sound capture/output, and sending/recieving custom network packets. 

- Nuklear Library used for certain GUI elements

- OpenCV used for video capture and compression.

- CMake used to build the C++ code. 
