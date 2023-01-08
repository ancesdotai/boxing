# Boxing

I have installed a camera in each corner of the gym ring where I practice boxing.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/QrWJ-GtePzc/0.jpg)](https://www.youtube.com/watch?v=QrWJ-GtePzc)

The original idea was to use the recordings as dataset for train a model in order to create a automatic scoring system. 

This system would be able to detect the punches and make a score based on the speed, power and accuracy of the punches. With 4 cameras, there are no problem with blind spots. 

Another idea was to analyze the technique of boxing. Look for strategies to win a fight, or to improve as a athlete.

Up to now, I have more than 30 hours of recordings. With some curation, getting the permission of the people who are in the videos, and performing an anomyzation of the faces, I think I can make a dataset available for the community. 

This has all been a proof of concept, done very informally. I have an agreement with my trainer (the owner of the gym), who currently uses the system to correct technical mistakes in his athletes (I have installed also a TV to be able to watch the recordings in the gym).

I recently found out that [someone had beaten me to it](https://www.linkedin.com/posts/svejstrupnielsen_about-18-months-ago-i-took-a-leap-into-the-activity-6984070467271757824-JiZy/?utm_source=share&utm_medium=member_ios):

So, I need some help. I don't have the time to do this properly. And I'm completely convinced that this is a very good idea. 


## Technical details

The videos are recorded in 2560x1440 (every camera @1280x720 resolution) @60FPS. [(Logitech StreamCam)](https://www.logitech.com/es-es/products/webcams/streamcam.960-001281.html). Every video have 4 audio channels, one for each camera microphone. 

I used a Jetson Nano to record the videos. 

Most of the videos are about sparring sessions. I have developed a way to label the punches in the videos. 