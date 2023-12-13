INTRODUCTION

A Digital clock is a type of clock that displays the time digitally, as opposed to an analog clock, where the time is indicated by the positions of rotating hands. The times derived by analog clocks come from either a pendulum or a spring. Pendulums are unusable on moving platforms, such as ship, and springs unwind more and more slowly as they released stored up tension. The use of sweep hands allowed these mechanical time bases to be presented in a mechanically driven display. With the perfecting of multivibrator chips, electrical circuits could be build that could accurately keep time under a wide range of conditions. As the time base had switched from mechanical to electrical, the time display had to follow suit. Display devices called 7 segment display were designed to allow the time to be shown numerically.

BLOCK DIAGRAM 

This is a simple Block Diagram of the Stopwatch  

LOGIC CIRCUIT
In this Section, we going through the diagram how it connects and how it works!
 
![image](https://github.com/caoxuannghiem/Digital_Stopwatch_Logic/assets/144471135/2767c7d4-f943-4ce8-88f1-16726c328a76)

ANALYSIS
FULL CIRCUIT:
Now to understand it deeper we have to analyze how it works, so we can understand more deeper, image down here is a common circuit diagram of stopwatch 

 ![image](https://github.com/caoxuannghiem/Digital_Stopwatch_Logic/assets/144471135/39261ffb-f57b-49f6-adc8-b8213b06be2e)


So. How it works? First is the Clock, we can adjust the time how fast it run by changing the frequency (Hz) for best results here 10k is good enough. Down here we going to use D flip flops OR and AND gates

![image](https://github.com/caoxuannghiem/Digital_Stopwatch_Logic/assets/144471135/af45910a-c1e9-46bb-bd87-1e3866b2a2a7)

 
(D Flip flops) 

 ![image](https://github.com/caoxuannghiem/Digital_Stopwatch_Logic/assets/144471135/76142572-4ee1-46c1-af92-550546190e36)


(OR gate and truth table) 

![image](https://github.com/caoxuannghiem/Digital_Stopwatch_Logic/assets/144471135/e29ddf79-e669-452c-bc7a-bbf46392deb4)

 

(AND gate and truth table) 
All of Above we now create a counter

 ![image](https://github.com/caoxuannghiem/Digital_Stopwatch_Logic/assets/144471135/ad649ef3-b44a-4228-b28e-f37c6c4df51a)


First is the counter will transmit all the signals through AND gate and will have to go through Inverter to create a signal 0 and 1, we can see here green on is 1 and green off is 0

 ![image](https://github.com/caoxuannghiem/Digital_Stopwatch_Logic/assets/144471135/bdcec4ae-bdbf-413f-99cb-0a829d7818cb)

By using that will have results as we can see above a,b,c,d,e,f,g are OR gates, these signals will move into 7 segments come out the results.

 ![image](https://github.com/caoxuannghiem/Digital_Stopwatch_Logic/assets/144471135/4ddd8d7d-84a3-467a-bc1b-b4d5b28711e1)


we connect all of it into this 7 segments. Results we can see image above. 


Please import it to this website https://www.falstad.com/circuit/

