# Ventilator-Pressure-Prediction
Google Brain - Ventilator Pressure Prediction
Simulate a ventilator connected to a sedated patient's lung

What do doctors do when a patient has trouble breathing? They use a ventilator to pump oxygen into a sedated patient's lungs via a tube in the windpipe. But mechanical ventilation is a clinician-intensive procedure, a limitation that was prominently on display during the early days of the COVID-19 pandemic. At the same time, developing new methods for controlling mechanical ventilators is prohibitively expensive, even before reaching clinical trials. High-quality simulators could reduce this barrier.

Current simulators are trained as an ensemble, where each model simulates a single lung setting. However, lungs and their attributes form a continuous space, so a parametric approach must be explored that would consider the differences in patient lungs.

Partnering with Princeton University, the team at Google Brain aims to grow the community around machine learning for mechanical ventilation control. They believe that neural networks and deep learning can better generalize across lungs with varying characteristics than the current industry standard of PID controllers.

If successful, you'll help overcome the cost barrier of developing new methods for controlling mechanical ventilators. This will pave the way for algorithms that adapt to patients and reduce the burden on clinicians during these novel times and beyond. As a result, ventilator treatments may become more widely available to help patients breathe.

The competition will be scored as the mean absolute error between the predicted and actual pressures during the inspiratory phase of each breath. The expiratory phase is not scored. The score is given by:

![](https://github.com/ramkiran55/Ventilator-Pressure-Prediction/blob/main/images/img1.JPG)

where X is the vector of predicted pressure and Y is the vector of actual pressures across all breaths in the test set.

Submission File
For each id in the test set, you must predict a value for the pressure variable. The file should contain a header and have the following format:

![](https://github.com/ramkiran55/Ventilator-Pressure-Prediction/blob/main/images/img2.JPG)

## Outputs :

![](https://github.com/ramkiran55/Ventilator-Pressure-Prediction/blob/main/outputs/output4.png)

![](https://github.com/ramkiran55/Ventilator-Pressure-Prediction/blob/main/outputs/output6.png)
