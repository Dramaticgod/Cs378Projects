CS378: Framework-Based Software Development for Hand-Held Devices
Project #4
Due time: 11:59 pm on 11/17/2024
Submit using Blackboard web site
Total points: 100
Instructors: Ugo Buy, Snigdha Ghosh Dastidar, Muhsin Adan and Umar Khan
Copyright © Ugo Buy, 2024. All rights reserved.
The text below cannot be copied, distributed or reposted without the copyright owner’s written consent.
For this project you will design and code a new Flutter app that simulates Android fragments. That is, at
any point in time the app will show two widgets arranged horizontally. The widget on the left side will display a
list of animations. Examples will include “bouncing ball”, “spinning wheel”, “rotating cube” and so on. Users
will be able to choose one of the animations from the list. When this happens, the chosen animation will be
displayed in the right-side widget.
Your implementation is subject to the following constraints:
1. When the app is started, the left-side widget occupies the entire width of the screen.
2. As soon as a user makes a selection in the left-side list, the list’s width (i.e., the width of the left-side
widget) is shrunk to about 1/3 of the screen and the item selected is highlighted. The remaining 2/3 of
the screen will now show the selected animation in the right-side widget. The selected list item should
be highlighted by showing an elevation and a different background color.
3. Your app should contain at least 2 explicit animations, 2 implicit animations and 6 animations total.
4. Define your two explicit animations in such a way that these animations could not be implemented as
implicit animations.
5. Your explicit animations should add buttons for the following functionality: (1) Pausing and resuming
the animation and (2) reversing the direction of the animation. The two buttons will be displayed in the
right-side widget.
6. Your app will show an AppBar with a small elevation and dark grey shadow. Choose an appropriate title
to be shown in the AppBar. The appBar also contains an action button that resets the app to initial state,
whereby the left-side widget occupies the entire width of the screen and no animations are shown.
7. The bottom of the AppBar shows center-aligned text indicating the name of the animation that’s currently
playing. In the initial state, the text will read “No animation currently playing”.
8. The text in the bottom of the AppBar should also indicate whether an animation is currently playing or
completed. For instance, the text could read “Bouncing ball animation is playing” or “Bouncing ball
animation is complete” depending on the status of a hypothetical bouncing ball animation.
Implementation notes. To test your app use the usual Pixel 5 device running Android 14 (API 34). Design
your app in such a way that it will display optimally in landscape mode; don’t worry about portrait mode.
You must work alone on this project. Submit the entire Studio project as a zip archive using the submission
link in the assignment’s page on Blackboard. The name of your zip archive should include your first and last
names, followed by the string “mp4.zip”.
