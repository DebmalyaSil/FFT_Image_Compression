# FFT_Image_Compression
This is more of an excercise than a project to implement and better understand the concepts of Digital Signal Processing learnt in class.
## Fast Fourier Transform
Fast Fourier transform is an efficient algorithm to calculate the Discrete Fourier Transform (DFT) of a signal.  
In converts data from the time (or spatial) domain into the frequency domain, allowing to analyze the different frequency components that make up the signal.  
In simple terms:
1. It breaks a complex signal(like an image, audio or sensor data) into its individual frequency.
2. This helps identify patterns, filter noise or data compress effectively.
## How can FFT be used to compress image?
Using FFT we can represent the original signal as a summation of its component frequencies. The higher order harmonics of the fundamental frequency of the signal generally has very less magnitude. So, we can comfortably discard the contribution of these higher order harmonics to compress the signal.  
If we want to highly compress the signal, we need to start discarding from lower oder harmonics of fundamental frequency itself.
