# eduardomachinelearning
Max/msp patches for features extractions

This extractor can be used for getting video and audio data in real time. In fact, it's a very simple max patch, extracting RGB numbers from a web cam and two audio features - centroid and RMS.

-configure your audio  in/output, also the cam

-open the max file (cam turns on automatically)

Zsa. descriptors and CNMAT externals are needed on this project.

I used to capture video and audio from a busy street , getting RGB data , centroid and RMS. 
In other situation I captured hand movements in from of the cam, associated with different percussion sounds played by the other hand.

In Wekinator I used linear progression for the video features
inputs and k nn classification for centroid and RMS info.
