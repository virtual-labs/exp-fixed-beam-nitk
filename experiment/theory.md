<div  style="text-align: justify;">

**Learning Objectives**

After completing this simulation experiment on free vibration of a fixed fixed beam one should be able to

<li>Model a given real system to an equivalent simplified model of a fixed fixed beam with suitable assumptions / idealizations.</li>  
<li>Calculate the logarithmic decrement, damping ratio, damping frequency and natural frequency of the system</li>  
<li>Find the stiffness and the critical damping of the system.
Calculate damping coefficient of the system.</li>

**Introduction**

A system is said to be a Fixed-Fixed beam system if it has a fixed connections at both its ends.

Vibration analysis of a fixed-fixed beam system is important as it can explain and help us analyse a number of real life systems. The following few real system can be simplified to a fixed-fixed beam, thereby helping us make design changes accordingly for the most efficient systems.

Following few figures tell us about the significance of analysing Fixed-Fixed beams and their relevance to the real world.

<div style="text-align: center">

[<img src="./images/fixed1.png" width="650" height="250"/>](./images/fixed1.png)

</div>

The above figure depicts a fixed-fixed suspension system and the pillow lock joint at its ends. In machinery too, we can find parts which can be analysed as fixed-fixed beams like in grinding machines and furnaces.

**Natural Frequency of Fixed Fixed Beam**

When given an excitation and left to vibrate on its own, the frequency at which a fixed fixed beam will oscillate is its natural frequency. This condition is called Free vibration. The value of natural frequency depends only on system parameters of mass and stiffness. When a real system is approximated to a fixed fixed beam, some assumptions are made for modelling and analysis (Important assumptions for undamped system are given below):

<li>The mass (m) of the whole system is considered to be lumped at the middle of the beam</li>
<li>No energy consuming element (damping) is present in the system i.e. undamped vibration</li>
<li>The complex cross section and type of material of the real system has been simplified to equate to a fixed fixed beam</li>

The governing equation for such a system (spring mass system without damping under free vibration) is as below:

<div style="text-align: center">

[<img src="./images/fixed2.png" width="150" height="75"/>](./images/fixed2.png)

</div>

k the stiffness of the system is a property which depends on the length (l), moment of inertia (I) and Young's Modulus (E) of the material of the beam and for a fixed fixed beam is given by:

<div style="text-align: center">

[<img src="./images/fixed3.png" width="110" height="50"/>](./images/fixed3.png)

</div>

**Damping in a Fixed Fixed Beam**

Although there is no visible damper (dashpot) the real system has some amount of damping present in it. When a system with damping undergoes free vibration the damping property must also be considered for the modeling and analysis.

Single degree of freedom mass spring damper system under free vibration is governed by the following differential equation:

<div style="text-align: center">

[<img src="./images/fixed4.png" width="210" height="75"/>](./images/fixed4.png)

</div>

c is the damping present in the system and ζ is the damping factor of the system which is nothing but ratio of damping c and critical damping c<sub>c</sub>. Critical damping can be seen as the damping just sufficient to avoid oscillations. At critical condition ζ=1. For real systems the value of ζ is less than 1. For system where ζ < 1 the differential equation solution is a pair of complex conjugates. The displacement solution is given by

<div style="text-align: center">

[<img src="./images/fixed5.png" width="400" height="60"/>](./images/fixed5.png)

</div>

where x<sub>0</sub> and v<sub>0</sub> are initial displacement and velocity and ωd is the damped natural frequency of the system. The damped natural frequency is calculated as below:

<div style="text-align: center">

[<img src="./images/fixed6.png" width="200" height="55"/>](./images/fixed6.png)

</div>

</div>
