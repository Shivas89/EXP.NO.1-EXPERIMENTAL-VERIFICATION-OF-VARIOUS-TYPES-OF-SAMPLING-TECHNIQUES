# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES

## 1.Experimental Verification Of Signal Sampling Using Various Types Such as i) Natural Sampling ii) Flat Top Sampling

### AIM

The primary goal of this experimental investigation is to practically validate different methodologies for acquiring discrete samples from a continuous signal. Specifically, we will focus on examining the characteristics of natural sampling and flat-top sampling techniques.

### APPARATUS REQUIRED

Experimental Training Platform, Digital Oscilloscope (minimum bandwidth: 10 MHz), Interconnecting Leads, and a Variable DC Power Source (range: 0-30V).

### PROCEDURE

1.  Generate a continuous-time analog input waveform (e.g., a sinusoidal signal at 1 kHz) using a function generator.
2.  Utilize a dedicated sampling circuit that provides the capability to switch between natural and flat-top sampling operations.
3.  Employ a second function generator or a timing control unit to produce the sampling pulse train (typically a rectangular wave with a frequency significantly higher than the input signal, for example, 8 kHz or more).
4.  Connect the output of the sampling circuit to the input channel of the digital storage oscilloscope to visualize the resulting sampled signal.
5.  Optionally, for signal reconstruction analysis, connect the sampled output to the input of a low-pass filter and observe the recovered waveform.
6.  Initialize the sampling circuit to operate in the natural sampling mode.
7.  Apply the 1 kHz sine wave (or a similar analog signal) as the input to the sampling circuit.
8.  Introduce the sampling pulse train (a rectangular waveform with a narrow duty cycle, such as 10%) as the sampling control signal.
9.  Observe and record the output waveform displayed on the oscilloscope.
10. You should observe segments of the input signal being transmitted during the active intervals of each sampling pulse.
11. Analyze the form of the sampled signal and compare its characteristics with the original continuous input waveform.
12. If a low-pass filter is connected, examine its output to determine the effectiveness of the original signal's recovery.
13. Repeat the above steps for both sample-and-hold and flat-top sampling modes of operation.
14. Generate appropriate graphical representations of the observed waveforms for each sampling method and interpret the results.

### CIRCUIT DIAGRAM

![image](https://github.com/user-attachments/assets/a5c214c5-951b-4f92-adfd-7b0e9962376e)
![image](https://github.com/user-attachments/assets/35974274-6d79-4b82-9d39-321b678ec2e3)


### MODEL GRAPH
![image](https://github.com/user-attachments/assets/fd2fc4bc-c983-4377-a83e-bfd3755e623f)

![image](https://github.com/user-attachments/assets/790b3728-edf4-4560-9170-bb22808d95d6)


### TABLE
![image](https://github.com/user-attachments/assets/43a0d587-b2db-44f3-8df3-ef58241fa94f)



### OUTPUT GRAPHS
![WhatsApp Image 2025-04-20 at 10 50 22_ab62ea38](https://github.com/user-attachments/assets/848dd04c-9a83-41fa-b278-b44c29ac8195)
![WhatsApp Image 2025-04-20 at 10 50 51_a3a0c1b2](https://github.com/user-attachments/assets/d60ca6b5-d6de-4aa3-822c-6bae7809a933)
![WhatsApp Image 2025-04-20 at 10 51 09_6c5723df](https://github.com/user-attachments/assets/5447f526-fe3c-48e8-a8b0-a5bacfd00424)


### RESULT

In conclusion, the process of discretizing and subsequently reconstructing the provided analog input signal was successfully carried out using different types of sampling methodologies.
