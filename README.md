# cse316-experiment-3-basic-use-of-adc-and-an-lcd-display-with-atmega32-solved
**TO GET THIS SOLUTION VISIT:** [CSE316 Experiment 3-Basic use of ADC and an LCD display with ATmega32. Solved](https://www.ankitcodinghub.com/product/cse316-experiment-3-basic-use-of-adc-and-an-lcd-display-with-atmega32-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96797&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE316 Experiment 3-Basic use of ADC and an LCD display with ATmega32. Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Basic use of ADC and an LCD display with ATmega32.

Goal:

To understand the basic working principle of ADC and the LCD display.

Fig. 1: Potentiometer, LCD display, Atmega32

Experimental Tools And Materials:

ATmega32, Potentiometers (POT-HG), 16×2 LCD display (LM016L), DC voltmeter.

Experiment:

In this experiment you will have to generate a variable voltage from 0 Volt to X Volt (X is provided in the individual specification) using a potentiometer. You will measure this voltage using ADC and display the voltage in the LCD segment. You will also continuously monitor the voltage using a voltmeter. You should use the DC voltmeter of Proteus. We will change the voltage using the pot and the reading of ADC from the LCD segment should be within ± 0. 02𝑉to the value shown in the DC voltmeter.

Individual Specification: MC Experiment 3 – Individual Spec

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
LCD Display Basics:

You should check out this tutorial: Interfacing 16×2 LCD with Atmega32 Microcontroller using Atmel Studio. You will be using the 4 bit mode. Essentially, you will use their library file lcd.h and connect your LCD display according to the given diagram. You do not need to use crystal. The connection summary is given in the following table.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
LCD Display Pin

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Connection

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
VSS

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
GND

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
VDD

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
5V

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
VEE (Contrast, see below)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Can vary within 0V-5V

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
RS

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
PC6

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
RW

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
GND

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
E

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
PC7

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
D0-D3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Ground

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
D4-D7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
PD4-PD7

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Contrast: VEE is used for contrast. In the real world, you can vary this from 0V to 5V depending on how clearly you can see the characters. VEE is varied with a potentiometer. This video clip will show a demo of how varying VEE changes the contrast of the LCD display. Although, in Proteus, we will not be able to experience that. https://www.youtubetrimmer.com/view/?v=Pq6-PGPdl_c&amp;start=41&amp;end=54

ADC Basics:

The basics were covered in the theory class.

<ol>
<li>Do necessary calculations according to your clock speed and configuration.</li>
<li>Use the internal 5V as the ADC source. You will have to connect AVCC to 5V.</li>
<li>Just to test your understanding, you are not allowed to use the ADC register
for this experiment. Instead, you must use both ADCH and ADCL registers. We encourage you to use the ADC register to calculate the analogue voltage in your spare time.
</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Procedure:

1. First create an X Volt source. You can use the voltage division rule to extract X Volt from a 5V source. Then create a variable voltage source VS in range 0V-XV using the potentiometer. Ensure the potentiometer is working by checking its output in the DC voltmeter.

<ol start="2">
<li>Connect the LCD display to your microcontroller. Write the necessary code to display a simple string, e.g., “Patience!!” to check the LCD display is working.</li>
<li>Complete the necessary ADC connections. Write necessary code to calculate the voltage VS.</li>
<li>Display the voltage in LCD display in the format “Voltage: #.##” i.e. one digit before the decimal point and two digits after the decimal point. In other words, you have to show the text “Voltage: ” and the value of the voltage VS.</li>
</ol>
Demo Video:

This is a demonstration of what we expect. Here, max voltage X = 4V.

MC Experiment 3 – ADC Demo.mkv

Miscellaneous:

<ol>
<li>You may not be able to create exactly X Volt source. A source of X±0.05V is acceptable too.</li>
<li>Be careful while reading ADCL and ADCH. You must read ADCL first. We encourage you to try reading ADCH first and see what happens. Try to find out the reason.</li>
</ol>
</div>
</div>
</div>
</div>
