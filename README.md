# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)  
****PROCEDURE**
**Natural Sampling**
Refer to the block diagram and carry out the following connections and switch setting.
Connect power supply in proper polarity to the kit DCL-10 and switch it on.
Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer.
and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the connecting chords provided.
Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
Using clock selector switch (S1) select 8khz sampling frequency.
Using switch (Sw2) select 50% duty cycle.
Connect the OUT post of the flat top sampling block to the input IN1 of the second order low pass Butterworth filter and take necessary observations as mentioned below.
Repeat the procedure for the 2khz sine wave signal as input.
**FLAT TOP SAMPLING:**
Refer to the block diagram and carry out the following connection and switch setting.
Connect power supply in proper polarity to the kit DCL-01 and switch it on.
Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the connecting chords provided.
Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
Using clock selector switch(S1) select 8khz sampling frequency.
Using switch (Sw2) select 50% duty cycle. Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low pass Butterworth filter and take necessary observation as mentioned below.
Repeat the procedure for the 2khz, sine wave signal as input
**CIRCUIT DIAGRAM**
![image](https://github.com/user-attachments/assets/ffab4ba0-b968-4efe-bc56-e1619720ff69)

****MODEL GRAPH**
![image](https://github.com/user-attachments/assets/e46d507a-d47d-43e1-8596-f20cc8c8b2fe)
**TABLE**
![ Image ](https://github.com/user-attachments/assets/244918f8-9870-412e-8a4a-9cc83c109d7e)
**OUTPUT GRAPHS**
![ Image ](https://github.com/user-attachments/assets/83726d66-4f2d-4f64-92e2-1617e8afb47b)
**RESULT**
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques was verified successfully.


