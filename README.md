The article is being published in collaboration with JLCPCB. They supply high quality PCBs at a very reasonable price. They also can provide SMT circuit assembly.

We thanks to our sponsor JLCPCB  https://jlcpcb.com/RTA for sponsoring us PCBs for this project circuit.

For SMT Service, Click  here - https://cart.jlcpcb.com/quote?orderType=1&stencilLayer=2&stencilWidth=100&stencilLength=100&stencilCounts=5

Thanks To JLCPCB.

$2  for 1-4 Layer PCBs.

Get SMT Coupons - https://jlcpcb.com/RTA


The project about making an adjustable LED flasher circuit. LED flashers are semiconductor integrated circuits used to turn on and off groups of light emitting diodes either sequentially or according to a programmed pattern.

All LED flashers including the solid state flashers, are compatible for use with regular bulbs, as well LED bulbs, mix of LED and regular bulbs.

High efficiency with low voltage makes it easy for LEDs to gain an edge over incandescent lamps, consuming 80% less electrical power.

There are many cheap LED flashers on the market that will simply go up in smoke when you put regular bulbs in.
This is the most efficient and convenient way to upgrade to LED turn signals, but unfortunately many vehicles no longer use replaceable flasher modules.
 	

Component List

To make this adjustable LED flasher circuit, we need some simple electronics component. You also can order assembled PCBs form JLCPCB. JLCPCB have its parts library. To check JLCPCB parts library, click here - https://jlcpcb.com/parts


All Component list have to been given below – 

Component List – 

•	CMOS Decade counter IC – CD 4017

•	Timer IC – NE555

•	Capacitor - 10µf / 25v

•	Ceramic Capacitor – 100 nf

•	Resistor – 10 K Ω
•	Variable Resistor - 10 K Ω
•	LED – 5 mm (40 Pieces)
•	Power Source – DC 12v



Feature of CD 4017 IC


•	The supply voltage of this IC is 3V to 15V.

•	It is compatible with TTL (Transistor -Transistor Logic).

•	The clock speed or operational speed of  CD4017 IC is 5 MHz.

•	It provides support to10 outputs that are decoded.

•	It is available in different packages like 16-pin GDIP, PDIP & PDSO

•	Input high time 30 ns

•	Output current is 10 mA

•	Noise immunity is high typically 0.45 VDD

•	Operation is completely static

•	Low power like 10 µW

•	High speed 16 pin CMOS Decade counter

•	Speed operation is medium like 5.0 MHz with 10V VDD

•	Input Voltage or Vin ranges from −0.5 VDC to VDD +0.5 VDC

•	TS or Storage Temperature ranges from −65°C to +150°C

•	VDD or DC Supply Voltage ranges from −0.5 VDC to +18 VDC

•	PD or Power Dissipation is Dual-In-Line is 700 mW

•	TL or Lead Temperature is 260°C


Pin out of CD 4017 IC

•	Pin-1: It is the output 5. It goes high when the counter reads 5 counts.

•	Pin-2: It is the output 1. It goes high when the counter reads 0 counts.

•	Pin-3: It is the output 0. It goes high when the counter reads 0 counts.

•	Pin-4: It is the output 2. It goes high when the counter reads 2 counts.

•	Pin-5: It is the output 6. It goes high when the counter reads 6 counts.

•	Pin-6: It is the output 7. It goes high when the counter reads 7 counts.

•	Pin-7: It is the output 3. It goes high when the counter reads 3 counts.

•	Pin-8: It is the Ground pin that should be connected to a LOW voltage (0V).

•	Pin-9: It is the output 8. It goes high when the counter reads 8 counts.

•	Pin-10: It is the output 4. It goes high when the counter reads 4 counts.

•	Pin-11: It is the output 9. It goes high when the counter reads 9 counts.

•	Pin-12: This is divided by 10 output which is used to cascade the IC with another counter to enable counting greater than the range supported by a single IC 4017. By cascading with another 4017 IC, we can count up to 20 numbers. We can increase and increase the range of counting by cascading it with more and more IC 4017s.

Each additional cascaded IC will increase the counting range by 10. However, it is not advisable to cascade more than 3 ICs as it may reduce the reliability of the count due to the occurrence of glitches. If you need a counting range of more than twenty or thirty, I advise you to go with the conventional procedure of using a binary counter followed by a corresponding decoder.

•	Pin-13: This pin is the disabled pin. In the normal mode of operation, this is connected to ground or logic LOW voltage. If this pin is connected to logic HIGH voltage, then the circuit will stop receiving pulses and so it will not advance the count irrespective of several pulses received from the clock.

•	Pin-14: This pin is the clock input. This is the pin from where we need to give the input clock pulses to the IC to advance the count. The count advances on the rising edge of the clock.

•	Pin-15: This is the reset pin that should be kept LOW for normal operation. If you need to reset the IC, then you can connect this pin to HIGH voltage.

•	Pin-16: This is the power supply (Vcc) pin. This should be given a HIGH voltage of 3V to 15V for the IC to function.


Pin out of NE - 555

Pin 1: GND Pin
Ground pin directly connected to the negative terminal of the power source. It is suggested that it should not be connected using any resistor because all the IC will heat up due to stray voltage (it is the occurrence of electrical potential between any two objects that ideally should not have any voltage difference between them at all) in it.

Pin 2: Trigger Pin
A trigger pin is used to activate the IC’s timing cycle for operating. It is a low signal pin and the timer is triggered when the voltage is below one-third of the supply voltage (1/3 V). It is connected to the Inverting input of the comparator inside the IC and accepts negative signals for the operation.

Pin 3: Output Pin
It is the output pin. As the IC triggered the output pin goes high depending on the duration of the timing cycle provided to it. In the case of logic zero o/p; it is a sinking current with voltage greater than zero (0 V). Whereas, in the case of logic high output, it is sourcing current with the output voltage lesser than Vcc.

Pin 4: Reset Pin
The reset pin is used to reset. It should be connected to the positive terminal to work the IC properly. If this pin is grounded, the IC won’t work at all. The required reset voltage is 0.7 volts at a current rating of 0.1mA to work.

Pin 5: Control Voltage
It is used for reliable operation. When not in use, it should be connected to the ground through a capacitor; otherwise, the IC will show erratic responses (deviating from the desired value).

Pin 6: Threshold Pin
It detects when the voltage on the timing capacitor rises above 0.66Vcc. The timing cycle is only completed when the voltage on this particular pin is equal to or greater than 2/3 of Vcc.

Pin 7: Discharge pin
It is used to provide a discharge path from the timing capacitor to the ground when the output is low. The discharging current should be less than 50 mA in order to prevent it from damaged.

Pin 8: Supply Terminal
It is a positive (+ve) terminal that is connected to the positive terminal of the power supply in order to power up. It is used to take power supply voltage from the power source for operating.



Hardware of Flip-flop Project Circuit

To make this adjustable led flasher circuit, we might need some electronics component. JLCPCB has its own parts library. JLCPCB has 200k+ in stock components, 24 hours rapid SMT assembly.

You can check SMT parts library here - https://jlcpcb.com/parts


Circuit Connection - Step 1

To make this adjustable led flasher circuit, we need to connect CD-4017 IC with timer IC NE-555.We connect CD-4017 IC 8no, 13no, 15no leg.

Then we connect 2no and 6no leg of timer IC and 4no and 8no leg of timer IC. Connect CD-4017 IC 8no leg with NE-555 IC 1no leg.
And connect NE-555 IC 8no leg with CD-4017 IC 16no leg. 


Circuit Connection - Step 2

Now we connect 10KΩ resistor with 7no leg of timer IC NE-555. Then connect it’s other terminal with same IC 8no leg and 16no leg of CD-4017 IC. We connect 10µf / 25v capacitor with the circuit. Connect this capacitor positive leg with 6no leg of timer IC and it’s negative terminal with 1no leg of timer IC.

Circuit Connection - Step 3

Now we need to connect Ceramic Capacitor – 100 nf with the circuit. We connect this ceramic capacitor with 5no leg of timer IC and it’s other terminal with 1no leg of timer IC. To adjust flash, now we need to connect a potentiometer. 
We connect it’s one terminal with 6no leg and it’s other terminal with 7no leg of timer IC.


Circuit Connection - Step 4

To make this flasher circuit, we are using 40 pieces LED light. We connect all LED negative terminal. Then connect it’s negative terminal with 1no leg of timer IC. This is a 10 channel adjustable led flasher. For this, we divide this 40 LEDs  by 10. Then each side will get 4 led and we connect this 4 led positive leg.


Circuit Connection - Step 5

Now we connect 1st channel led light with 3no leg, 2nd channel led light with 2no leg, 3rd channel led light with 4no leg, 4th channel led light with 7no leg, 5th channel led light with 10 no leg, 6th channel led light with 1no leg, 7th channel led light with 5no leg, 8th channel led light with 6no leg, 9th channel led light with 9 no leg and 10th channel led light with 11no leg of CD-4017 IC.


Circuit Connection - Step 6

To operate this LED flasher circuit, we need to connect a power supply circuit. For power supply, we are using DC-12v. Connect DC-12v positive cable with 8no leg of timer IC and it’s negative terminal with 1no leg of timer IC.


Steps to Order PCBs from JLCPCB

If you complete design of your PCBs, then it is time to order PCBs. To order best quality PCBs, just visit JLCPCB and click on the “QUOTE NOW” button.

Since 2006, JLCPCB continuously driven to become more efficient and to reduce costs. They promise to offer customers the most economic PCBs forever. JLCPCB makes cheapest but top quality PCBs possibly because of scale effect, extremely high production efficiency and less manpower cost.

You can order minimum 5 pieces PCBs for only $2 costs.

To order PCBs, make your Gerber file. Then drag and drop the Gerber file on the following box.

Click on “Gerber Viewer” button you can check the PCBs design. Make sure everything is good, then choose color, quantity and order your PCBs at very reasonable prices.

If you are a new user, then you can order 10 pieces PCBs, costing only $2. To place your order click on “Save to Cart” button. Confirm your shipping address and shipping method.


Steps to Order SMT PCBs From JLCPCB


To order your SMT PCBs, visit JLCPCB.

1.	 Drag and drop SMT PCBs file on site.

2.	 Choose your PCBs color and quantity.

3.	 To free SMT assembly for your PCB click on “SMT Assembly” button and then confirm.

4.	 Add your Bom file and CPL file.

5.	 Place your order click on “Save to Cart” button.

6.	 Confirm your shipping address and shipping method.
7.	 Pay your payment
8.	 Wait for confirmation mail.
9.	 For SMT Service, Click here.


 Shipping and Billing

JLCPCB supported all shipping method can be seen below.

Estimated Delivery Time

DHL International Express 3-5 business days

UPS Worldwide Saver 3-6 business days

S.F Express(Standard) 5-8 business days

S.F Express(Economy) 8-15 business days

Singapore EMS 8-15 business days

PostLink Registered Mail 15-20 business days

ePacket 15-25 business days

Registered Air Mail 15-20 business days

JLCPCB supported Payment method.

•	PayPal

•	Credit/Debit Care

•	Prepaid wire transfer


Confirm PCBs Order

To confirm your order, pay your payment. Then accept PayPal, Credit/Debit Card, prepaid Wire Transfer. To manufacture your PCBs, it’ll take about 2 days. DHL will be fastest shipping method to arrive your ordered PCBs at your location.
All PCBs were well packed and quality was really good.
Thanks to JLCPCB for best quality PCBs.
