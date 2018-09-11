# Cardiac Rehab Exercise
The data presents an efficient self-cardiac rehabilitation(CR) exercise system. The system consists of a wearable device, a smartphone application, and a medical station. A patient performs self-CR exercise with the worn wearable device which enables the patient to do self-CR exercise by informing current exercise stage and recommending appropriate exercise intensity in real-time. 

The exercise stage order consists of warm-up, main exercise, rest, and cool-down as recommended by ACSM guidelines. A patient performs the self-CR exercise with the worn wearable device on wrist. The wearable device measures instantaneous HRs during the exercise, and informs a patient an appropriate exercise intensity based on the comparison between the current HR and the Target Heartrate Zone(THZ) in real-time. 

The system was validated with 16 healthy subjects: a CR specialist remotely monitors the exercise records and prescribes the CR exercise through a medical station, which automatically ransmits the prescription to a patient's wearable device via smartphone application. 


Cardiac Rehabilitation Exercise Data with Matlab
==================================================
Heewon Chung, Hooseok Lee, and Jinseok Lee (Professor) a member of BAMI LAB.   
https://sites.google.com/site/bamilab/biosignal-lab   
Last updated 2018.09.11 (September 11, 2018)


CR Exercise Experiment Protocol
==================================================
Measurements were taken using an ECG placed on the chest together with a PPG placed on the wrist during CR Exercise. ECG data were recorded simultaneously using a 24-hour Holter monitor (SEER Light; GE Healthcare, Milwaukee, WI, USA). PPG and motion data were recorded using a wearable device which we developed. Participants were asked to perform the exercise according to the exercise protocol, we have designed. 
  1) Stay (Resting)      : 1minutes
  2) Walking             : 2minutes, treadmill (3km/h)
  3) Running             : 3minutes, treadmill (7km/h)
  4) Walking             : 2minutes, treadmill (3km/h)
  5) Running             : 3minutes, treadmill (8km/h)
  6) Walking             : 2minutes, treadmill (3km/h)
  7) Stay (Resting)      : 1minutes

Matlab Data
==================================================
This database contains wrist PPGs recorded during stay, walking, and running.
Accelerometers and Gyroscopes are collected to remove the motion artifact from the PPGs.
A reference chest ECG is included to allow a gold-standard comparison of heart rate during CR exercise.

ECG sampling rate : 125Hz   
PPG sampling rate : 50Hz  
Acc sampling rate : 50Hz  
Gyro sampling rate : 50Hz   

Data Description
==================================================
bpmECG    : ECG heart rate  
timeECG   : ECG times   
sigPPG    : PPG signal  
sigAcc    : Accelerometer signal  
sigGyro   : Gyroscope signal  
