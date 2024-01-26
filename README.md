# R - Peak Detection using Altered Pan-Tompkins Algorithm

Related published paper: [Y. Palaniappan, V. A. Vishanth, N. Santhosh, R. Karthika and M. Ganesan, "R - Peak Detection using Altered Pan-Tompkins Algorithm," 2020 International Conference on Communication and Signal Processing (ICCSP), Chennai, India, 2020, pp. 1501-1505, doi: 10.1109/ICCSP48568.2020.9182298.](https://ieeexplore.ieee.org/document/9182298)

Electrocardiogram (ECG) evaluation is performed by signal processing in majority of the systems. Accurate QRS (r-peak) detection is a vital step for analyzing variations in heart rate. Algorithms based on the differentiated ECG signals can be computed efficiently and are useful for real-time analysis. The data from the MIT database consists of time-domain data of the electric potentials from the heart. In this work the data is processed and analyzed to detect and diagnose cardiac problems. ECG wave is used to detect and diagnose abnormalities in blood pressure, blood cholesterol and blood sugar. Variations in ECG is used in stress analysis and emotional activity. This modified Pan- Tompkins algorithm used in our work achieved a sensitivity of 94.54%.

To analyse a QRS detection algorithm we use standard arrhythmia databases. The MIT/BIH database is the most familiar database in the clinical society. This database helps in the comparison of detection algorithm based on the accuracy and performance.

In this modified algorithm the raw signal is first sent to a filter where its DC components are cancelled i.e. the DC offset is removed and then passed through a band-pass filter, derivative filter, squaring function. Before passing it to the integrator it is passed through an averaging filter in-order to increase the strength of the signal relative to noise that is obstructing it. Then it is passed through an Integrator and the R-peak is detected by the process of thresholding. The figure below shows the modified Pan-Tompkins algorithm employed in our work.

!<img src="https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/9177229/9182042/9182298/vishan2-ICCSP593-large.gif" width="400" height="250">
