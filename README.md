# FUS-Sham
Auditory stimulus for recreate auditory artifact for Sham-FUS

We used a Matlab script to generate a .wav file with pulses of a 20 kHz tone (sine wave). Pulse duration, pulse repetition interval, and total duration of a session were identical to the experimental ultrasound stimulation protocol. The exported .wav file was played using a bone-conducting headphone during the sham stimulation. 


#ultrasound_sham.m
Matlab file generating rectangular pulses (no ramping)


#ultrasound_sham.wav
example output of the routine above. 


#ultrasound_tukey.m
Matlab file generating ramped pulses with the parameter of ramp duration indicating the duration of the ramping-up phase at the beginning and the ramping-down phase at the end of a pulse.
