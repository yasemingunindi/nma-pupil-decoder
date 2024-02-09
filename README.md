# nma-pupil-decoder
Neurons Project for Neuromatch Academy 2024: Computational Neuroscience
Group Magical Moose

This project includes a GLM predicting different aspects of occular motion from neural activity of a mouse's primary visual cortex recorded while in the dark (Stringer et al. 2019).
This spontaneous activity occurred without visual stimuli yet the original authors were still able to encode behaviours into spike counts in visual areas. 
To investigate what about this behaviour could be encoded in V1, we built a decoder for the pupil's position/ change of positition / magnitude of the movement and the direction of movement.
Comparing these different aspects allows us to infer what kind information is represented in V1. In our case there were significant differences between the variance explained of the different aspects of the ocular motion 
and  pupil's position and magnitude of movement were most accurately predicted.
This was repeated for nine different cortical depths and three time gaps. The time gaps introduced asycnhrony between the time series of neural activity and behavior and were investigated to gain 
insight whether the information in V1 is present before or after behavior. Best performance was achieved for synchronous activity, however, future neural spike counts were better at decoding present pupil inforamtion compared to past spike counts.
The cortical depths were investigated to see where in V1 this information is represented, but no significant differences were observed.


[Presentation](https://docs.google.com/presentation/d/1x7VEihgfQRQ2Yg0mqw_QGaB-aGzEjEcc/edit?usp=sharing&ouid=109602866614278695540&rtpof=true&sd=true)
