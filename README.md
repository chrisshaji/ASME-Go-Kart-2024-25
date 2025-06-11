# ASME-Go-Kart-2024-25
This was a very fun project where I got to work on creating a drivable Go-kart.

## Initial Design Goals
We started off brainstorming ideas for our go-kart with two main goals in mind; maximum speed and good cornering. One factor that plays a 
major role in speed is having a low center of gravity. The design had downward welds that would lower the middle section of the kart below
the center of the wheels which effectively reduced the center of gravity. Secondly, in order to make the kart more aerodynamic, the spacing
between all the components such as the engine, seat, pedals were all optimized to make the kart as small as possible while still taking into 
consideration the comfort of the driver. 

(sketches of car)

In order to ensure good cornering, we decided to implment Ackermann steering geometry to our kart. This would greatly reduce the slippage of tires 
when going around corner, which is essential as our final course consisted of a lot of sharp turns. A lot of mathematical calculations involving
the turning radius, wheelbase, wheel radius resulted in a maximum steering angle of 38° and an Ackermann ratio of 0.522. FEA analysis was also 
performed in order to guarantee that the chassis would not fail under the weight of the driver, engine, and other components of the kart. 


(fea), (cad of car)

## Video of me driving the Go-kart!

https://github.com/user-attachments/assets/4cc92635-a495-468a-8d7d-2a40a7170ef8

