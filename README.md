## Buffer-Overflow

A buffer overflow occurs when more data are written to a buffer than it can hold. The excess data is written to the adjacent memory, overwriting the contents of that location and causing unpredictable results in a program. Buffer overflows happen when there is improper validation (no bounds prior to the data being written. It is considered a bug or weakness in the software

We are given a program that has the buffer-overflow problem, and we need to exploit the vulnerability to gain the root privilege. Moreover, we will experiment with several protection schemes that have been implemented in Linux, and evaluate their effectiveness.

<img width="397" alt="screen shot 2018-10-27 at 1 22 39 am" src="https://user-images.githubusercontent.com/32382556/47601516-d78d3200-d986-11e8-91b0-62923269deec.png">
