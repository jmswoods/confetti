# confetti
Feel free to use this in your website

include this to body section :
<script src="https://cdn.rawgit.com/jmswoods/confetti/main/confetti.min.js"></script><script>confetti.start()</script>


FUNCTIONS :
confetti.start();                  //starts the confetti animation (keeps going until stopped manually)
confetti.start(timeout);           //starts confetti animation with confetti timeout in milliseconds (if timeout is 0, it will keep going until stopped manually)
confetti.start(timeout, amount);   //like confetti.start(timeout), but also specifies the number of confetti particles to throw (50 would be a good example)
confetti.start(timeout, min, max); //like confetti.start(timeout), but also the specifies the number of confetti particles randomly between the specified minimum and maximum amount
confetti.stop();        //stops adding confetti
confetti.toggle();      //starts or stops the confetti animation depending on whether it's already running
confetti.pause();       //freezes the confetti animation
confetti.resume();      //unfreezes the confetti animation
confetti.togglePause(); //toggles whether the confetti animation is paused
confetti.remove();      //stops the confetti animation and remove all confetti immediately
confetti.isPaused();    //returns true or false depending on whether the confetti animation is paused
confetti.isRunning();   //returns true or false depending on whether the animation is running


PARAMETERS
confetti.maxCount = 150;     //set max confetti count
confetti.speed = 2;          //set the particle animation speed
confetti.frameInterval = 20; //the confetti animation frame interval in milliseconds
confetti.alpha = 1.0;        //the alpha opacity of the confetti (between 0 and 1, where 1 is opaque and 0 is invisible)
confetti.gradient = false;   //whether to use gradients for the confetti particles
