# final_project_486

Language used: 
1. Jquery
2. html

3.javascript

Installation guide:


1. For emotion detector: Download all the files in this repository on your computer(DO NOT INCLUDE THE JSON FILES, THEY ARE MY TEST DATA)

2. For questionnaire building: 

Due to the complex structure of setting up the questionnaire and storing your design in a data base,

please follow the guide on the public repository link below:

https://github.com/surveyjs/survey-library 

Please follow the "Main Features" sections in their README file if you want to build a brand new questionnaire from scratch.

For conveience, if you want to take a closer look at the existing questionnaire I built for the test, please log onto my 

account and see my survey in my file:

Link to the survey: https://surveyjs.io/Service/EditSurvey/78b45adb-a66b-4a82-bfe4-6b39a2848fc1

My loggin info:

Username: lxu33@dons.usfca.edu

passcode: s6c6Xabm@

Once logged in, click on "CREATOR" in the top middle, and "Open my Surveys" ----> "depression test"



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






