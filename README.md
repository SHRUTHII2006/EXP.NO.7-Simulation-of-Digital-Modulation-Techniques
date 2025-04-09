# EXP.NO.7-Simulation-of-Digital-Modulation-Techniques
7. Simulation of Digital Modulation Techniques Such as
   i) Amplitude Shift Keying (ASK)
   ii) Frequency Shift Keying (FSK)
   iii) Phase Shift Keying (PSK)

# AIM

To perform simulation of Digital Modulation Techniques Such as 

i) Amplitude Shift Keying (ASK) 

ii) Frequency Shift Keying (FSK) 

iii) Phase Shift Keying (PSK) and analyze their waveforms


# SOFTWARE REQUIRED

Python Software 

-> Numpy Library 

-> Matplotlib Library 

-> Scipy Library (for signal processing)

# ALGORITHMS


1.Define binary data sequence

2.Set bit duration and sampling rate

3.Generate time vector based on total bits and sampling rate

4.Create carrier signal

      ASK/PSK: single frequency

      FSK: two frequencies (for '0' and '1')

5.ASK: Multiply carrier with binary data

6.FSK: Switch between two carriers based on binary data

7.PSK: Apply phase shift (π) for bit '0'

8.Plot original message and modulated signals (ASK, FSK, PSK)


# PROGRAM

ASK

![ASK ](https://github.com/user-attachments/assets/e9b54002-d06b-4286-a88f-f1eebc169dce)



FSK

![FSK](https://github.com/user-attachments/assets/91a87b1f-6048-44a1-bfd9-02981223a1ad)



PSK


![PSK](https://github.com/user-attachments/assets/061c0f91-3c95-47a4-bb2e-aaf7c152c7a9)




# OUTPUT

ASK

![ASK OUTPUT](https://github.com/user-attachments/assets/e6bcca06-2146-45f6-b3b4-d0bc5e7f0425)


FSK


![FSK OUTPUT](https://github.com/user-attachments/assets/ae4885e3-0092-4cb8-bf47-8e7016c02644)


PSK


![PSK OUTPUT](https://github.com/user-attachments/assets/a7bfaf07-f86a-4a6a-981d-f2e2867c2de4)



 
# RESULT / CONCLUSIONS

The digital modulation techniques ASK, FSK, and PSK were successfully simulated using Python.


The simulation demonstrated how ASK, FSK, and PSK modulate a carrier signal to transmit binary data. Each modulation technique has its own method of altering the carrier wave, which is essential in digital communication systems.
