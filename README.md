# De-noising-the-audio-signal-Kaiser-window-method

In order to design a fir filter to achieve the de-noising of the speech signal processing, following steps must be carried out:
  
        • Collecting and sampling the speech signal
 
        • Adding random noise to the speech signal
 
        • Designing the parameters of fir filter
 
        • Completing the design and simulation via matlab
 
        • Verifying whether the simulation results meet the requirements.
        
# Simulation results:

# Figure 1
                    the original input audio signal is shown both in Time domain and in Frequency domain. By observing the time-domain diagram from the simulation results, it can be seen that the speech signal lasts about 40 seconds long and the amplitude A is not more than 0.5. From the above frequency domain diagram of the simulation results, which can be seen that the frequency of the speech signal is mainly concentrated in the low frequency part, the maximum amplitude of the speech signal frequency does not exceed 1000.
![image](https://user-images.githubusercontent.com/69566068/124389620-a2c00400-dd05-11eb-8817-8893f464eaf7.png)




# Figure 2
                   the effect is very obvious when adding noise into the signal by using randn(), Which can be clearly seen in the time domain graph that the original speech signal almost could not be revealed, deeply buried in the noise.
![image](https://user-images.githubusercontent.com/69566068/124389678-d26f0c00-dd05-11eb-85fb-d8ff56adb1ca.png)




# Figure 3
                   It is notable that when the audio signal with noise is filtered, the original signal is received back with reduction in noise level.
![image](https://user-images.githubusercontent.com/69566068/124389686-dd29a100-dd05-11eb-84cf-f92e0b54e01b.png)


