# Match_Maker

Matches your Tinder profile with the person who liked you.

# tinder.user.js

Forked from https://gist.github.com/Tajnymag/9de74305f9bb09aa940d26418bd508f1#file-tinder-user-js


Open the Tinder website and run tinder.user.js file in the console of the web page using Inspect to deblur the profile image of the person in the Matches section who liked you and snip it using snipping tool for further feature comparision.

Save the image as saved_image.jpg file.

# TinderMatchMaker.py 

Open the Tinder website in full screen and run the TinderMatchMaker.py in Python IDE of your choice in the minimised display format.


Make sure the floating python IDE screen does not cover the Tinder profile area on the display screen.


This script compares the features of the previously saved_image from the Matches section with the profile images and looks for the particular match using FLANN based Matcher.


If the potential match is found it likes the profile and makes a Tinder match. Otherwise, it will dislike and check further profiles.


Check for the dimensions of your display and the location of the like, dislike and next image icons in the display and edit those positions in the TinderMatchMaker.py script if necessary.


Note: Interrupt the Loop with Sleep command using keyboard or by moving cursor to any corner of the screen.

