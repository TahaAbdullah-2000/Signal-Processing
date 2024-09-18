### Hey there!
<p>Today, we will explore some foundational concepts of signal processing. We’ll begin by importing essential libraries, including:
<ul>
    <li>Numpy</li>
    <li>Matplotlib.pyplot</li>
</ul>
We then apply the Fast Fourier Transform (FFT), which returns both real and imaginary values stored in a variable called spectrum. In Cell 14, we define a new variable called frequency resolution, representing the step size on the x-axis (frequency).

From the spectrum variable, we extract the magnitude and phase values using functions like abs(), deg2rad(), and angle(). To obtain the correct magnitude values, we multiply (2/N) with the spectrum, where the scaling is done with respect to energy.

It’s important to note that phase values are often different because they are calculated relative to a cosine function. Therefore, we apply the formula <b>sin(θ) = cos(θ + 90)</b> to determine the actual phase values.

Finally, we calculate the index number of the first signal, allowing us to easily find its magnitude and phase without relying solely on visual inspection of the plots.
</p>
### The End... Bye