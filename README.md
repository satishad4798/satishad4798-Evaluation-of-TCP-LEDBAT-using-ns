# Evaluation-of-TCP-LEDBAT-using-ns-3

## Course Code: CO300 <br/>
## Assignment: #16

**Overview**<br/>
Low Extra Delay Background Transport (LED-BAT) is a novel one-way delay Internet congestion control
algorithm developed to react to congestion earlier than any of the loss-based TCP congestion control algorithms (e.g. TCP-
NewReno). A LEDBAT source quickly reduces its sending rate when the queue delay experienced in its path is greater than
a fixed pre-defined target value.<br/>

 The threshold of a bottleneck buffer size that leads LEDBAT to revert to a minimum congestion window of only 1
packet in the presence of TCP. That is, for some applications its throughput will be too low. In addition to the fact that intra-
protocol unfairness among multiple LEDBAT sources may occur when using the fixed minimum LEDBAT congestion win-
dow to improve the limited LEDBAT throughput,the average LEDBAT throughput is fixed even as the bottleneck link capacity increases as opposed to TCP throughput that increases proportionally. This therefore necessitates the needfor a dynamic minimum congestion window in the LEDBAT algorithm.<br/>
![](images/Screenshot%20from%202019-11-23%2015-30-10.png)
