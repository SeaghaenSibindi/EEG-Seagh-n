This is my entry for TECS

The EEG specificiation are derived from this here[https://www.instructables.com/Mind-Control-3-EEG-Monitor/] 

I was using pretty subpar hardware which meant I really had to support it with post processing in order to get anything that worked. 
( I am not yet familiar with Github, but I will try make this readable.)


# **WEEK 4 overview** (earlier weeks are to be added.) 

![Week 4](Figure_1.png)
This graph showed the relative changes in ampliude of the right and left modules. Both of which were unconnected, the very small changes in amplitude were probably as a result of noise.

The bottom graph is a bit malformed, but it shows the signal after significant filtering using l1 minimisation, making the signals much more accurate and as expected when not reading from a person, there is neglible signals being read. 


# ( A bit of validation)

I compared the signals from an electrode that was connected to my friends forehead and one that was just rested on a table. 
![comparison](comparisonofactiveelectrodegroupandinactiveelectrodegroup.png)

The lower amplitudes and higher frequencies my just be noise, but the blinking activity was detected as being more than just the noise.
