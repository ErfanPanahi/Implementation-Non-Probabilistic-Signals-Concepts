# Implementation-Non-Probabilistic-Signals-Concepts
"In this repository, I intend to implement and investigate mathematical relationships related to signal and system concepts, as well as analyze the interdependencies of non-probabilistic signals, throughout a sound processing task. Ultimately, I will also focus on the validation of input-output correlation relationships for LTI systems."

*The aim of conducting this project is to investigate the fuzzy distortion created in an audio signal, design an equalizer, and find the original and real signal. For this purpose, we intend to analyze a signal containing two harmonics, remove its harmonics, and obtain the original signal. In the end, we also strive to achieve a better understanding of correlation relationships during the passage through an LTI system in a numerical processing.*

The completed sections of the project are as follows: (CA1_Matlab_810198369.mlx)

**1- Please perform the Fourier transformation on the audio file "data.wav"**

**2- Reading the signal from "y.wav"**

**3- Calculate the coefficients $\alpha$, $\beta$, and the delays $k_1$ and $k_2$**

$𝑦(𝑡) = 𝑥(𝑡) + 𝑎𝑥(𝑡 − 𝑘_1) + 𝛽𝑥(𝑡 − 𝑘_2)$

The correlation of two signals, denoted as $x(t)$ and $y(t)$, is obtained by the convolution of the shifted signal $x(t)$ with signal $y(t)$. Therefore, the more similar the shifted $x(t)$ signal is to $y(t)$, the larger the correlation coefficient will be for that particular shift value. Consequently, the most similar signal to $y(t)$ for a given value of $\tau$ is the one that maximizes the correlation.

**4- Obtaining the frequency response and group delay**

**5- Comparison of the time-domain impact response resulting from manual calculations and the "ifft" command**

**6- Obtaining the input signal $x(t)$**

**7- Analyzing the Difference Generated in Signal $x(t)$**

**8- Obtaining the output of an echo system using the convolution command "conv" and the relationship $x(t) * h(t)$.**

**9- The process of creating an echo**

**10- Analyzing Relationships Related to Coherence During Passage through an LTI System**

