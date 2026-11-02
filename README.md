21. Transfer Functions 

A transfer function shows the relationship between input and output. It is written as H(z). It is the ratio of the output to the input in the z-domain. The roots of the numerator are called zeros, and the roots of the denominator are called poles. They affect system stability and frequency response. 

22. Modulation and Demodulation 

Modulation changes a carrier signal to send information. There are three main types: AM, FM, and PM. Demodulation is the process of getting the original information back. These processes are used in radio, TV, and wireless communication. 

23. Coefficient Quantization Effects in Digital Filters 

Coefficient quantization means changing exact filter values into approximate values. This creates small errors. These errors can change the filter response and stability. Using more bits can reduce these errors. 

24. Digital Signal Processing System 

A DSP system processes signals in digital form. It usually has an ADC, a digital processor, and a DAC. First, the ADC changes the analog signal into digital data. Then, the processor works with it. Finally, the DAC changes it back into an analog signal. 

25. Quadrature Modulation – Deviation 

Quadrature modulation uses two signals with a 90-degree phase difference. They are called I (in-phase) and Q (quadrature). They carry information together. It is used in QAM and QPSK. Frequency deviation is the maximum change in carrier frequency. 

26. Spectral Characteristics 

Spectral characteristics show the frequency parts of a signal. The Fourier Transform is used to study them. They help us find the main frequencies, noise, and unwanted signals. They are important in communication and audio systems. 

27. Modulation and Demodulation 

Modulation puts information onto a carrier signal. It can change the amplitude, frequency, or phase. Demodulation gets the original information back. These processes are important in radio and wireless communication. 

28. Discrete-Time Systems 

A discrete-time system works with signals at specific time points. Its input is x(n), and its output is y(n). It changes input signals into output signals. These systems are used in digital signal processing and control systems. 

29. Design of IIR Filter Using Bilinear Z-Transform 

An IIR filter is a digital filter with an infinite impulse response. The bilinear transformation changes an analog filter into a digital filter. It helps keep the system stable. However, it can cause frequency distortion called frequency warping. Prewarping can help correct this problem. 

30. FIR and IIR Filters 

FIR means Finite Impulse Response, and IIR means Infinite Impulse Response. FIR filters do not use feedback. IIR filters use feedback. FIR filters are generally stable and can have linear phase. IIR filters need fewer coefficients but require careful stability checks. 

31. Recursive Smoother 

A recursive smoother is a digital filter that reduces noise. It uses the current input and the previous output. It has feedback. A small alpha gives more smoothing, while a large alpha makes the output change faster. It is used to make signals smoother. 

32. Group Delay, Linear Phase, All-Pass, Minimum Phase 

Group delay is the time delay of different frequencies. Linear phase means all frequencies have the same delay. An all-pass filter changes the phase but not the signal magnitude. A minimum-phase system has the smallest phase delay and a stable inverse. 

33. Analog-to-Digital Conversion 

Analog-to-digital conversion changes an analog signal into digital data. An ADC is used for this process. It has three steps: sampling, quantization, and encoding. It is used in microphones, cameras, and sensors. 

34. A Fundamental Definition of System Stability 

A system is stable if every bounded input gives a bounded output. This is called BIBO stability. If the output becomes unlimited, the system is unstable. For a discrete-time LTI system, the impulse response must be absolutely summable. 

35. Sampling and Quantization 

Sampling takes signal values at regular time intervals. Quantization gives each sample a fixed level. The number of levels depends on the number of bits. For example, 8 bits give 256 levels. More bits give better accuracy. 

36. Aliasing and Anti-Aliasing in Digital Systems 

Aliasing happens when the sampling frequency is too low. High frequencies may look like lower frequencies. This causes signal distortion. An anti-aliasing low-pass filter is used before sampling to remove unwanted high frequencies. 

37. Nyquist–Shannon Sampling Theorem 

The Nyquist theorem says that the sampling frequency must be at least twice the maximum signal frequency. The formula is: fs>=2fmax , If the sampling frequency is too low, aliasing happens. This theorem is important for correct signal sampling and reconstruction. 

38. Correlation Analysis 

Correlation analysis measures the similarity between two signals. Autocorrelation compares a signal with itself. Cross-correlation compares two different signals. It helps find similarities and time delays. It is used in communication and signal processing. 

39. Equalization Filters 

Equalization filters change the frequency response of a signal. They increase or decrease selected frequencies. They can improve audio quality and reduce signal distortion. They are used in audio and communication systems. 

40. Frequency Response and Transfer Function 

A transfer function shows the relationship between input and output. It is written as H(z). Frequency response shows how a system changes the amplitude and phase of different frequencies. It helps us understand and design digital filters. 

41. Quantization Error 

Quantization error is the difference between the original sample and its quantized value. It happens because we use a limited number of levels. More bits give more levels and usually reduce the error. It is also called quantization noise. 

42. All-Pass Filters 

An all-pass filter allows all frequencies to pass. It does not change their magnitude, but it changes their phase. Its magnitude response is equal to one. It is used to control phase and group delay. 

43. The Fourier Transform and Discrete Fourier Transform 

The Fourier Transform changes a signal from the time domain to the frequency domain. DFT is used for digital signals with a limited number of samples. FFT is a faster method for calculating DFT. These methods help study signal frequencies. 

44. First-Order Notch Filter 

A notch filter reduces a specific frequency in a signal. It helps remove unwanted noise and interference. The notch frequency is the frequency that is reduced the most. It is used in measurement and communication systems. 

45. Second-Order Unity Gain Resonator 

A second-order resonator is a filter that increases a specific frequency. It has a second-order transfer function. Unity gain means the gain is equal to one. Its poles affect the resonant frequency and bandwidth. It is used in audio and communication systems. 

46. State Space 

State-space is a mathematical method used to describe a system. It uses input, output, and state variables. The state equation shows how the system changes over time. The output equation shows how the output depends on the input and state. It is used in control systems. 

47. Transformation of Random Signals in Discrete-Time Systems 

A random signal is a signal that cannot be predicted exactly. Noise is an example. When it passes through a digital system, its properties can change. These properties include mean, variance, and autocorrelation. This topic is important in communication and signal processing. 

48. High-Pass Filters 

A high-pass filter allows high frequencies to pass. It reduces low frequencies. The cutoff frequency separates the two parts. It is used to remove low-frequency noise and improve signal quality. 

49. Low-Pass Filters 

A low-pass filter allows low frequencies to pass. It reduces high frequencies. The cutoff frequency separates the passband and stopband. It is used to remove high-frequency noise. Butterworth is a common type of low-pass filter. 

50. Band-Pass Filters 

A band-pass filter allows a specific range of frequencies to pass. It reduces frequencies below and above this range. It has two cutoff frequencies: lower and upper. The difference between them is called bandwidth. It is used in radio and communication systems. 

51. Relationship Between Sampling Frequency and Maximum Frequency 

Sampling frequency is the number of samples taken per second. Maximum frequency is the highest frequency in a signal. According to the Nyquist theorem, the sampling frequency must be at least twice the maximum frequency. Fs>= 2f max If it is too low, aliasing happens. 

52. Nyquist Frequency, Aliasing, and Signal Reconstruction 

Nyquist frequency is half of the sampling frequency. Aliasing happens when the sampling frequency is too low. It causes signal distortion. An anti-aliasing filter helps prevent this problem. Signal reconstruction changes discrete samples back into a continuous signal. 

 

54. Fundamental Principles of Digital System Analysis 

Digital system analysis studies how a system works. It shows how a system changes input into output. Difference equations and the Z-transform are used for analysis. Engineers also study linearity, time invariance, causality, and stability. 

55. Role of the Z-Transform in Analyzing Discrete-Time Systems 

The Z-transform is used to study discrete-time signals and systems. It changes a signal into the z-domain. It makes calculations easier. It helps find transfer functions, poles, zeros, and system stability. 

56. Linearity, Time Invariance, Causality, and Stability 

These are four important system properties.Linearity: The system follows addition and scaling rules.,Time invariance: The system works in the same way at any time.Causality: The output depends on present and past inputs, not future inputs. , Stability: Every bounded input gives a bounded output. 

57. Effect of Poles and Zeros on Digital Systems 

Zeros are the roots of the numerator. Poles are the roots of the denominator. They affect the frequency response of a system. Zeros can reduce some frequencies. Poles can increase the response near some frequencies. For a stable causal system, all poles must be inside the unit circle. 

58. Transfer Function of a Discrete-Time Digital System 

A transfer function shows the relationship between input and output. It is written as H(z). It is the ratio of the output Z-transform to the input Z-transform. 

Main formula: h(z)=y(z)/x(z) 

Poles and zeros affect the system's response and stability. 

60. Relationship Between Transfer Function, Poles, Zeros, Stability, and Frequency Response 

The transfer function shows the relationship between input and output. Zeros are the roots of the numerator, and poles are the roots of the denominator. They affect the frequency response. Stability mainly depends on the poles. For a stable causal system, all poles must be inside the unit circle. These concepts help us understand and design digital systems. 
