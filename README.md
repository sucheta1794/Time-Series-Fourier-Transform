## Time-Series-Fourier-Transform
Time series is a series of data indexed over time. Time series forecasting is a way of predicting future events based on past patterns of data over time.
Time series analysis and forecasting are crucial for predicting future trends, behaviors, and behaviours based on historical data. Mostly useful to make informed decisions and identify potential risks. It aids in planning, budgeting, and strategizing across various domains of idustries, healthcare, etc.

## What is Discrete Fourier Transform (DFT)? 
DFT transforms or decomposes an discrete set of points (indexed in time-series) into its sine and cosine components, tranforming it from its spatial domain to frequency domain. The frequency domain determines any seasonal components (short-term seasonal cycle which repeats itself multiple times or seasonal variances in data) in the time-series data and the position of occurences and how to separate them. DFT is the transformation and the algorithm used to achieve this is called Fast Fourier Transform (FFT). Therefore, we will used FFT to do Fourier analysis of time-series using Numpy/Scipy packages.

## Why Fast Fourier Transform (FFT) ?
It transforms the data into the frequency domain allows to gain insights into the underlying patterns and characteristics of the signal.

## Packages Used
-  Pandas (2.1.1)
-  Numpy (1.26.4) 
-  Scipy (1.11.3)
-  Matplotlib (3.8.0)
