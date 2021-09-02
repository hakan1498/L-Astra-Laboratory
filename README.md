# Meeting Indicator
Home office: Let your people know when you are in a meeting.

<img width="643" alt="Screen Shot 2021-09-02 at 11 42 23 AM" src="https://user-images.githubusercontent.com/22894897/131874898-e1c4e843-610e-4b4a-b68f-300c96184da2.png">

Arduino file: https://github.com/lastralab/L-Astra-Laboratory/blob/master/MeetingIndicator.ino <br />
Tinkercad project: https://www.tinkercad.com/things/0seiGmH2P1Q-meeting-indicator

# Electronics Laboratory
A virtual laboratory for random experiments.

<img width="1111" alt="screenshot 2017-04-09 11 37 49" src="https://cloud.githubusercontent.com/assets/22894897/24838188/5cc6e974-1d19-11e7-9a42-a2bba056ee78.png">

Schematics:

<img width="798" alt="screenshot 2017-04-09 12 18 20" src="https://cloud.githubusercontent.com/assets/22894897/24838466/b1b21c1a-1d1e-11e7-927d-e351dc05d2e2.png">

Code:

<pre>
<font color="#aaaaaa">//OSCILLOSCOPE LAB + ArduinoUno</font>
<font color="#aaaaaa">//Author: Niam Moltta</font>
<font color="#5e6d03">#define</font> <font color="#ffffff">Potentiometer</font> <font color="#ffffff">A2</font>
<font color="#5e6d03">#define</font> <font color="#ffffff">LED</font> <font color="#ffcd22">13</font>
 &nbsp;&nbsp;
<font color="#00979c">int</font> <font color="#ffffff">val</font> <font color="#aaaaaa">=</font> <font color="#ffcd22">10</font><font color="#ffffff">;</font> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

<font color="#00979c">void</font> <font color="#5e6d03">setup</font><font color="#aaaaaa">(</font><font color="#aaaaaa">)</font> <font color="#aaaaaa">{</font>
 &nbsp;<font color="#d35400">pinMode</font><font color="#aaaaaa">(</font><font color="#ffffff">LED</font><font color="#aaaaaa">,</font> <font color="#00979c">OUTPUT</font><font color="#aaaaaa">)</font><font color="#ffffff">;</font> &nbsp;
<font color="#aaaaaa">}</font>

<font color="#00979c">void</font> <font color="#5e6d03">loop</font><font color="#aaaaaa">(</font><font color="#aaaaaa">)</font> <font color="#aaaaaa">{</font>
 &nbsp;<font color="#ffffff">val</font> <font color="#aaaaaa">=</font> <font color="#d35400">analogRead</font><font color="#aaaaaa">(</font><font color="#ffffff">Potentiometer</font><font color="#aaaaaa">)</font><font color="#ffffff">;</font> &nbsp;&nbsp;&nbsp;
 &nbsp;<font color="#d35400">digitalWrite</font><font color="#aaaaaa">(</font><font color="#ffffff">LED</font><font color="#aaaaaa">,</font> <font color="#00979c">HIGH</font><font color="#aaaaaa">)</font><font color="#ffffff">;</font> &nbsp;
 &nbsp;<font color="#d35400">delay</font><font color="#aaaaaa">(</font><font color="#ffffff">val</font><font color="#aaaaaa">)</font><font color="#ffffff">;</font> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 &nbsp;<font color="#d35400">digitalWrite</font><font color="#aaaaaa">(</font><font color="#ffffff">LED</font><font color="#aaaaaa">,</font> <font color="#00979c">LOW</font><font color="#aaaaaa">)</font><font color="#ffffff">;</font> &nbsp;
 &nbsp;<font color="#d35400">delay</font><font color="#aaaaaa">(</font><font color="#ffffff">val</font><font color="#aaaaaa">)</font><font color="#ffffff">;</font> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<font color="#aaaaaa">}</font>

<font color="#aaaaaa">/*OP AMP:</font>
<font color="#aaaaaa"></font>
<font color="#aaaaaa">To use the oscilloscope with other components you have to wire the positive input</font>
<font color="#aaaaaa">of the oscilloscope to the Vout of the Operational Amplifier and the negative</font>
<font color="#aaaaaa">input of the oscilloscope to the positive input of the Op Amp (to get an Inverter Circuit).</font>
<font color="#aaaaaa"></font>
<font color="#aaaaaa">*/</font>

</pre>

Circuits.io Simulator:

![l astralab](https://cloud.githubusercontent.com/assets/22894897/24838330/84a70264-1d1c-11e7-8261-c870e9721355.gif)

# 555 TIMER experiment:

![paprika](https://cloud.githubusercontent.com/assets/22894897/26334858/545969d2-3f3e-11e7-9d96-87c87d86523e.gif)

Schematics:

<img width="796" alt="screenshot 2017-04-09 14 46 49" src="https://cloud.githubusercontent.com/assets/22894897/24839582/bff348c0-1d33-11e7-8aaf-8aa7e1e048a7.png">

**LT Spice Simulator:**

<img width="50%" alt="screenshot 2017-04-09 14 48 15" src="https://cloud.githubusercontent.com/assets/22894897/24839585/c6095362-1d33-11e7-8e81-14ed13adb5ae.png"><img width="50%" alt="screenshot 2017-04-09 14 48 42" src="https://cloud.githubusercontent.com/assets/22894897/24839587/caed9af0-1d33-11e7-9947-3ff15d6ae116.png">

Circuits.io Simulator:

<img width="70%" src="https://cloud.githubusercontent.com/assets/22894897/24839683/9151d39a-1d35-11e7-88a8-b16a3f195fe3.gif">

# Bike Dynamo Basics

Parts:

4 diodes 1N4007

1 Capacitor 10,000uF min 0.4V

1 LED

<img width="50%" alt="screenshot 2017-04-24 15 49 24" src="https://cloud.githubusercontent.com/assets/22894897/25353470/b7345304-2905-11e7-80f3-b17fbbcf04c7.png">

Let the 3V battery be the voltage generated by the rotating wheel.

<img width="60%" src="https://cloud.githubusercontent.com/assets/22894897/25353685/884a1550-2906-11e7-8c30-5e5484d871fc.gif">

# RGB color reference

![rgb](https://cloud.githubusercontent.com/assets/22894897/25641617/72d78ea8-2f6b-11e7-9035-39b5ee739fb3.gif)

# Reversing a DC motor direction with two SPDT relays

![dcr](https://cloud.githubusercontent.com/assets/22894897/26065112/49ca8332-3969-11e7-903d-391ef67d7696.gif)

Code for Arduino:

```C++
// Bird trap test
// Author: Niam Moltta
// L'Astra Lab

#include <IRremote.h>

int ActuatorF = 11;
int ActuatorR = 10;
int val = Serial.read();
int RECV_PIN = 7; 
IRrecv irrecv(RECV_PIN);
decode_results results;

  void setup(){
      pinMode(ActuatorF, OUTPUT);
      pinMode(ActuatorR, OUTPUT);
	  digitalWrite(ActuatorF, LOW);
      digitalWrite(ActuatorR, LOW);
      Serial.begin(9600);
      irrecv.enableIRIn();
    }

  void loop(){
    
        if (irrecv.decode(&results))
        {
         Serial.println(results.value, DEC);
         digitalWrite(ActuatorF, HIGH); //forwards
         digitalWrite(ActuatorR, LOW);
        }
       else 
       { digitalWrite(ActuatorF, LOW); //backwards
         digitalWrite(ActuatorR, HIGH);
       }
	}

```
<br>
<br>
<p align="center"><a href="https://lastralab.github.io/website/" target="_blank"><br><button><img src="http://i.imgur.com/ERyS5Xn.png" alt="l'astra lab icon" width="50px" background="transparent" opacity="0.5" padding="0;"/></button></a></p><br><br>
