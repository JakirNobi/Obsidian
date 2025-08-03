---
Date: 2025-08-02
Time: 20:24
cssclasses:
  - center-titles
  - center-images
---
#note #dc #analog-to-digital #pcm 

Status:[[Completed]]

Tags:[[Data-Communications]],[[PCM]].[[Quantization]],[[Binary encoding]] 

# Sampling

- Analog signal is sampled every TS secs.

- Ts is referred to as the sampling interval.

- fs = 1/Ts is called the sampling rate or sampling frequency.

- There are 3 sampling methods:

	- Ideal - an impulse at each sampling instant
	
	- Natural - a pulse of short width with varying amplitude
	
	- Flattop - sample and hold, like natural but with single amplitude value

- The process is referred to as pulse amplitude modulation PAM and the outcome is a signal with analog (non integer) values.
---
## Three different sampling methods

![[Pasted image 20250802203523.png]]

# Notes
According to the Nyquist theorem, the sampling rate must be at least 2 times the highest frequency contained in the signal.

# References
[Data communications and networking I Behrouz A Forouzan](https://dpvipracollege.in/wp-content/uploads/2023/01/Data-Communications-and-Networking-By-Behrouz-A.Forouzan.pdf) 