# countdown-timer
This is a countdown timer which counts correctly the time left.
It was built with HTML, CSS and JavaScript. As usual, index.html was used to build the structures, while styles.css used to give it its desired looks like outline and colors. Then app.js was used to make it functional.

For future date, I used the JS date functionality to set the current date and year then added number of the day I want it to display. So it'll always display the number of days left till the end of the countdown. And once the count down has expired, it displays h4 which says, "sorry, this giveaway has expired' this is because I set an If statemnt to clearInterval(countdown);

For values array (the countdown display values), I set an array of days, hours, minutes, and seconds. So since I selected multiple itmes I iterated over the items that are coming from HTML and then I used the index since the values have the same index of days, hrs, mins, and secs. So I just added the index into the item of inner.HTML. 

NOTE: It is important that we invoke our remaining time after our set interval because we want to have access to the countdown. If we don't, we have no access to it. So I used majlus (%) to say what my remainder is then I divided that remainder by 1000 millisecond.

And remember that month is zero index based so I set 11 for December instead of 12.
If you have any questions, don't hesitate to contact me.
