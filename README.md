# PaintWithFriends
- A fully featured collaborative painting app writen in C++ that features built in networking, text, audio, and video chat.

- Created Fall 2021 for Mike Shah's CS5500 Software Engineering Course at Northeastern University. By request of the professor, the source code is not publicly available.

- Authors are Tom Wiseman, Dennis Ping, Michael Maquera, and Rajwinder Singh.

![PaintWithFriends](https://user-images.githubusercontent.com/77803506/148086189-a1544e01-7ba3-41c5-b5a5-b44455650858.JPG)

# Features
- Multiple paint tools, undo/redo, color picker, export to PNG, screenshot, auto-reconnect, and more!

![AnimatedUndo](https://user-images.githubusercontent.com/77803506/148088043-90dd2d85-93f9-452f-9a7f-1e8fc6e411b1.gif)

![PaintWithFriendsColorPicker](https://user-images.githubusercontent.com/77803506/148088174-6520ff88-2719-4897-934b-d11a4811f5d2.JPG)

- Independent server application that manages multiple TCP and UDP connections for any number of clients.  

- Video and Audio Chat

- Text Chat

![PaintWithFriendsTextChat](https://user-images.githubusercontent.com/77803506/148088207-cf4257c1-1e3f-4b17-a769-4a14076f83b3.JPG)

- Windows/MacOS Compatible

# UML

![Group 3 CS5500  (2)](https://user-images.githubusercontent.com/77803506/148146815-35b56e75-7276-4371-aad0-724bca0bc39f.png)


# External Libraries

- SFML Library used for capturing user input, creating and displaying a Window, sound capture/output, and sending/recieving custom network packets. 

- Nuklear Library used for certain GUI elements

- OpenCV used for video capture and compression.

- CMake used to build the C++ code. 
