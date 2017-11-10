## illustration of method and model

SHE switching angles rapid generation algorithm is proposed based on neural network and quasi Newton iteration, which makes a compromise among the memory consumption, executing efficiency and the solution precision. The algorithm uses neural network to predict the switching angles of iterative initial value, and then switching angles of precise solution are obtained though quasi-Newton algorithm. This hybrid method better solves problems of the look-up table method occupying large memory, and small scale neural network method being difficult to achieve precise control. Compared to the look-up table method, data storage space of the algorithm was decreased by 95%. The algorithm execution time is approximately 70ms in STM32F407 board. The experimental results illustrate the generated switching angles can effectively eliminate the target harmonics.

### simulation

Modulation is 0.48

<div align="Modulation is 0.48">

<img src="modulation_0.48.png" width= "50%">  <img src="fft_modulation_0.48.png" width= "50%">


Modulation is 0.8

<div align="Modulation is 0.8">
<img src="modulation_0.8.png" width= "50%">   <img src="fft_modulation_0.8.png" width= "50%">


Modulation is from 0.48 to 0.8 at 0.01s

<div align="Modulation is from0.48 to 0.8">
<img src="modulation_0.48_0.8.png" width= "75%">


