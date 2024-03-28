# SME-Assignment

1st Part - 40 min
2nd Part - 3 hours

In the 2nd Part the definition of PlayerView required #include PlayerController.h and for the definition of PlayerController it required #include PlayerView.h 
hence both tried to access the complete definition of each other which resulted in the error. I just removed the #include PlayerController.h statement from PlayerView.h 
and just defined the class(PlayerController) name in it.
