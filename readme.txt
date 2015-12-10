- The repository contains raw accelerometer (MMA7260Q) and gyroscope (IXZ-500) data obtained from inertial sensors during performance of 9 gestures for manuscript entitled "Gesture Recognition System for Real-time Mobile Robot Control Based on Inertial Sensors and Motion Strings” which is submitted for possible publication in "Engineering Applications of Artificial Intelligence" journal. 

- It also contains video clip depicting how each gesture was performed so that experiment can easily be reproduced by others. This also enables comparison with similar systems.

- For interpretation of raw data please consult sensor datasheets available at https://www.sparkfun.com/datasheets/Accelerometers/MMA7260Q-Rev1.pdf and http://store.invensense.com/datasheets/invensense/PS-IXZ-0500B-00-03.pdf.

- Gyroscope was set to +-110 deg/s measurement range, while accelerometer was set to +-1.5 g range.

- Data is in comma separated format (.CSV) where each column contains the following data (from left to right): AccelerometerWrist_X, AccelerometerWrist_Y, AccelerometerWrist_Z, GyroscopeWrist_X, GyroscopeWrist_Z, AccelerometerFinger_X, AccelerometerFinger_Y, AccelerometerFinger_Z, GyroscopeFinger_X, GyroscopeFinger_Z, TimeStamp

- Each row represent time instance of the measurement. During one measurement (recorded in the file of general form subjectXX_measurementYY) all 9 gestures were executed once in succession with short pause between gestures (from Gesture 1 to Gesture 9).

- For a details about sensor placement, please consult manuscript in question where this is explained in more detail.

- The database is available under Cretive Commons 4.0 International Public NonComercial Licencse (https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)


