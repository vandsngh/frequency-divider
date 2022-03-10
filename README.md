# Frequency-divider using CMOS
# Abstract
This paper is about a frequency divider.It is a circuit that takes the
input and divide it by specified value. It is also called clock
divider. There are many circuit which use frequency dividers
to generate a frequency that is a multiple of a reference
frequency. It has a vital role in Phase locked loop frequency
synthesizers. Frequency dividers can be implemented for both
analog and digital application.

# Refrence circuit diagram
![frequency divider](https://user-images.githubusercontent.com/101287326/157681447-26b43955-8ac3-4b64-8968-b2f53a86d8d6.png)


# Circuit Details
D type flip flop is used as a frequency divider .It can be seen
from the figure below frequency waveforms above, that by “feeding
back “the output from q bar to the input terminal d, the
output pulses at q have a frequency that are exactly one half
(f/2) that of the input clock frequncy.The circuit function is
to divide or drop the frequency of the high frequency signal
to get the lower frequency signal for a given frequency signal
by division. Analog frequency dividers are less common and
used only at very high frequencies. Digital dividers
implemented in modern IC technologies can work up to tens
of GHz. An arrangement of flip flop is a classic method for
integer-n division.The following ciruit uses Nmos,Pmos,input source and output. 


# Software Used
 # eSim
 It is an Open Source EDA developed by FOSSEE, IIT Bombay.
 It is used for electronic circuit simulation. 
 It is made by the combination of two software namely NgSpice and KiCAD.
For more details refer:
https://esim.fossee.in/home
 # NgSpice   
 It is an Open Source Software for Spice Simulations. For more details refer:
http://ngspice.sourceforge.net/docs.html
 # Makerchip   
 It is an Online Web Browser IDE for Verilog/System-verilog/TL-Verilog Simulation. Refer
https://www.makerchip.com/
# Circuit Diagram in eSim
![Frequency_Divider_ckt dig](https://user-images.githubusercontent.com/101287326/157680952-530ad376-d1cd-4eef-b446-6632ea4fa125.png)
# Waveforms
![Frequency_waveform](https://user-images.githubusercontent.com/101287326/157679753-eea74be3-b4c0-4611-831f-0eab1bdeb408.png)
# Acknowledgment
1.Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. - kunalpghosh@gmail.com
2.Sumanto Kar, eSim Team, FOSSEE
  # References
  [1] G. Eason, B. Noble, and I. N. Sneddon, “On certain integrals of
Lipschitz-Hankel type involving products of Bessel functions,” Phil.
Trans. Roy. Soc. London, vol. A247, pp. 529–551, April 1955.
(references)
[2] J. Clerk Maxwell, A Treatise on Electricity and Magnetism, 3rd ed.,
vol. 2. Oxford: Clarendon, 1892, pp.68–73.
[3] I. S. Jacobs and C. P. Bean, “Fine particles, thin films and exchange
anisotropy,” in Magnetism, vol. III, G. T. Rado and H. Suhl, Eds.
New York: Academic, 1963, pp. 271–350.
 

   
