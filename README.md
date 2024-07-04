# MediaPlayer-Controller
detects hand signs to control vlc media player

#Step - 1  -Import Libraries and capture camera<br  />
#Step - 2  -Convert frames Into hsv<br  />
#Step - 3  -Track hand on color basis <br  />
#Step - 4  -Create mask on the basis of color and filter actual color <br  />
#Step - 5  -Invert pixel value and then enchance the result for better output<br  />
#Step - 6  -Find Contours for specific colored object<br  />
#Step - 7  -Find Max area contour and draw it on live feed<br  />
#Step - 8  -Find Convexity detect  for counting Values and Apply Cosin method<br  />
#Step - 9  -Bind hand gestures with keyboard keys.<br  />
#Step -10  -Enjoy your output<br  />

works based on number of hand digits detected<br  />
    0 digits :- no action 
    1 digits :- Play/Pause 
    2 digits :- Volume Up
    3 digits :- Volume Down 
    4 digits :- Forward 
  
