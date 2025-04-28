# EXP.NO.3.-IMPLEMENTATION-OF-DELTA-MODULATION

3.Implementation of Delta Modulation 
  
## AIM:    
 To study the Delta modulation using the Delta Modulation trainer kit.
 
## APPARATUS REQUIRED:
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)

## PROCEDURE:

1.Delta Modulation (DM) is a simple technique for converting analog signals into digital form. In DM, the analog signal is sampled at a rate much higher than the Nyquist rate. Instead of encoding the absolute value of each sample, DM encodes the difference between the current input and the previous output.

2.This difference is represented by a single bit: if the signal is rising, a '1' is transmitted; if it is falling, a '0' is transmitted. The receiver uses this stream of bits to reconstruct the signal by incrementing or decrementing the previous value by a fixed step size.

3.A low-pass filter then smooths the staircase output to recover the analog waveform.

4.DM is simple and requires less bandwidth than PCM but can suffer from slope overload distortion if the signal changes rapidly, and granular noise if the step size is too large for slowly varying signals.

5.Adaptive methods can improve performance.

## CIRCUIT DIAGRAM:
![image](https://github.com/user-attachments/assets/95a45858-8140-4f26-a917-749fc9837bff)

## MODEL GRAPH:
![image](https://github.com/user-attachments/assets/261a8d6a-f957-4089-90b8-9423dd7582c8)


## TABLE:
![WhatsApp Image 2025-04-28 at 15 28 06_792e7247](https://github.com/user-attachments/assets/87db009f-e47b-48b7-a60d-e5218b50bdfa)


## OUTPUT GRAPHS:
![WhatsApp Image 2025-04-28 at 15 30 40_9e7a700e](https://github.com/user-attachments/assets/8e07865a-d1a5-4fb6-b2c8-d590a82f58b0)


## RESULT:
 Thus Delta Modulation is studied and the waveforms are obtained.

