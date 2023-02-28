# Make the Robot Move

**Xy Fang (xf48)**

>   Collaborator: Yuxiang Chen (yc825) & Yutong Zou (yz2664)



# 0 VNC Viewer Screenshots

 <img src="https://s2.loli.net/2023/02/28/fyuizSpwGImt4nY.jpg" alt="detection.jpg" style="zoom:30%;" />



# 1 Reflection

1.   **For your favorite prototyped interaction that you have thought of so far, reflect upon how a camera connected to your Pi could be useful.**

     Out favirite prototyped interaction so far is the Mobile Working Station Bot, which carries a mobile power and a steady desktop at the top of it where you can work on, with multiple types of charging ports. The bot will wander around an open working area (say a sidewalk cafe) without many sockets. It will go to people once it sees them and wait for people to use the chargers or the desktop. Therefore, we need the camera to see people. Moreoever, we might want the robot to go to people only if people are waving to it, which needs the camera to capture people's waving move.

2.   **What issues do you foresee with this setup?**

     *   The desktop might not be very stable on the wheels.
     *   The size and the shape of the mobile power might be difficult to fit on the wheels.

3.   **How is the temperature? How is the speed? How is the connection?**

     The temperature shouldn't be too high since it carries a mobile power. Because it's used in daily lifes, the temperatures would be fine within the range that a mobile power could tolerate.  The speed of the bot should be equal or less than that of a person walking, or it could bump into people and hurt them. For this bot, we don't need an internet connection since we can integrate the algorithms in Pi.

4.   **How is the view? Would it capture what you might need to see for your prototyped interaction (in question 1)?**

     The bot's view should be mostly seeing people sitting, but sometimes seeing people standing. Therefore, the current view of the camera should be enough. However, as the view is broad with a lot of people captured in the view at the same time, the camera might not be able to detect people waving.
