# final_project_486

Language used: 
1. Jquery
2. html
3。javascript

Installation guide:
Download all the files in this repository on your computer
===========================================================

This is a program that analyze the facial expressions detected in your video files.

Once the download is complete, you can just open up the "affectiva_emotion_detectore.html" file in your text editor. 

To choose the video file you want to analyze, change the name of the file in line 34:
-------------------
  var filename = 'data/test3.anecdotes.mov';
  
 ----------------
 
 For example, the video file name is "xxxx.mp4", just change that in the filename as following:
 
 ------------------
 
var filename = 'data/xxxx.mp4';

- ----------------

Next, just double click on your "affectiva_emotion_detectore.html" file, it will start analyzing your video

and output a json file containing the results for expression and emotion level.

-------------------

You can change the size of extracting emotions in seconds in line 42
------------------------

var sec_step = .7; (in this example, the file will be analyzed every 0.7 sec. You can change that based on your needs)

You can choose what emotions and facial expressions to detect from line 60 - 65 :

----------------------------------------

// detector.detectAllEmotions();
  // detector.detectAllExpressions();

  detector.detectExpressions.smile = true;

  detector.detectEmotions.joy = true;

---------------------------------------






