Using the right-click-inspect, I selected console and saw that the error message
included "script.js:40".  This tells me that the error is in script.js on
line 40.  So I went to line 40 and saw that the function being called was called
showGlobal which does not exist. Looking above I saw that there was a function
called showGlobals, so I added an s to the end of where it called the function
showGlobal. I saved the file, refreshed the tab in Chrome and everything seems
to be working now.
