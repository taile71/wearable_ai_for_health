Part 1: Pulse Rate Algorithm  Overview
Algorithm Specifications
- estimates pulse rate from the PPG signal and a 3-axis accelerometer.
- assumes pulse rate will be restricted between 40BPM (beats per minute) and 240BPM
- produces an estimation confidence. A higher confidence value means that this estimate should be more accurate than an estimate with a lower confidence value.
- produces an output at least every 2 seconds.


Part 2: Clinical Application
Use algorithm to compute more clinically meaningful features and discover healthcare trends.
Use 24 hours of heart rate data from 1500 samples to try to validate the well-known trend that average resting heart rate increases up until middle age and then decreases into old age.

The data from this project comes from the Cardiac Arrhythmia Suppression Trial (CAST), which was sponsored by the National Heart, Lung, and Blood Institute (NHLBI). CAST collected 24 hours of heart rate data from ECGs from people who have had a myocardial infarction (MI) within the past two years. This data has been smoothed and resampled to more closely resemble PPG-derived pulse rate data from a wrist wearable.

