TITLE:  Implementation of Adaptive Kalman Filter Based BPSK Demodulator  
AIM:To develop an Adaptive Kalman Filter based BPSK demodulation system capable 
of accurately recovering transmitted audio data under noisy communication conditions 
affected by phase offset, frequency offset, and channel noise  
OBJECTIVES: 
1. Audio Signal Processing: Read and process digital audio signals using MATLAB 
and Python, converting the audio samples into a binary bit stream suitable for 
digital communication. 
2. BPSK Modulation and Transmission: Implement Binary Phase Shift Keying 
(BPSK) modulation by mapping binary data into phase-shifted carrier symbols 
and transmitting them through a simulated noisy communication channel. 
3. Frequency and Phase Offset Estimation: Introduce practical communication 
impairments such as carrier frequency offset, phase offset, and additive noise 
into the transmitted signal, followed by coarse estimation and correction 
techniques. 
4. Adaptive Kalman Filter Synchronization: Implement an Adaptive Kalman Filter for 
dynamic phase and frequency tracking to improve carrier synchronization 
accuracy and reduce Bit Error Rate (BER). 
5. BER and Signal Quality Analysis: Evaluate system performance by comparing 
BER values before and after Kalman correction and analyzing the recovered 
signal quality. 
6. Embedded Implementation on Jetson Nano: Deploy the developed demodulator 
algorithm on NVIDIA Jetson Nano for real-time embedded signal processing.
