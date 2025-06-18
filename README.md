# ASME Go Kart 2024-25
This was a very fun project where I got to work on creating a drivable Go-kart!

## Initial Design Goals
We started off brainstorming ideas for our go-kart with two main goals in mind; maximum speed and good cornering. One factor that plays a 
major role in speed is having a low center of gravity. Our design had downward welds that would lower the middle section of the kart below
the center of the wheels which effectively reduced the center of gravity. Secondly, in order to make the kart more aerodynamic, the spacing
between all the components such as the engine, seat, pedals were all optimized to make the kart as small as possible while still taking into 
consideration the comfort of the driver. We also had to stay under the budget of $1300 for the entire go-kart.

(sketches of car)

In order to ensure good cornering, we decided to implement Ackermann steering geometry to our kart. This would greatly reduce the slippage of tires 
when going around corner, which is essential as our final course consisted of many sharp turns. A lot of mathematical calculations involving
the turning radius, wheelbase, wheel radius resulted in a maximum steering angle of 38° and an Ackermann ratio of 0.522. FEA analysis was also 
performed in order to guarantee that the chassis would not fail under the weight of the driver, engine, and other components of the kart. 

(fea), (cad of car)

## Fabrication Process
After designing and ensuring that our design would be feasible, we moved on to the fabrication process. For the chassis, we utilized a 24' long
metal tube and cut it up into different sections. These sections were then welded together using MIG welds. Some of the angled welds were done by
more experienced welders on the team, and it all worked out as none of the welds gave out during testing.

(rough welding diagram), (making sure it works), (picture of frame)

Then, we moved on to mounting all the parts onto the frame. We started off with the rear axle kit as we had to weld a couple of small pieces at the 
end of the car to attach its mounting brackets. Upon putting it together, we had to get rid of the third horizontal bar across the width of the kart 
as it would intefere with the sprocket of the axle. We replaced that bar with two angled cuts that went from the end of the kart to the middle of the
second bar in order to keep the same structural integrity. The mounting brackets were welded to the small pieces at the end and the rear axle spun
freely with the wheels.

(picture of angled supports), (mounting bracket weld)

The next step was to install the engine. A predator 6.5 HP gas engine purchased from harbor freight was used to power the go-kart. In order to get a 
better edge on our competitors, we decided on upgrading the valve springs, flywheel, caburetor, intake, and exhaust. The engine was taken apart and 
installing the springs were no joke. It took a lot of effort and time in order to pop the springs in as there was no easy way for it to latch onto the
grooves. The flywheel also was very hard to take off and we ended up purchasing a 5 ton flywheel puller in order to remove it and install the new 
aluminum flywheel. 

(front of engine), (spring installation), (final modded engine)

After modding the engine, we went ahead and built the mounts for the engine and the seat. small pieces of tubing were welded to the base in order to prop 
a sheet of metal on which the seat and the engine would lay. These sheets were cut using a angle grinder and mounting holes were drilled using a miling 
machine. Next, it was time to install the brakes and the pedals. The brake was mounted to the back using a 'customized' bracket that was used to connect 
the caliper to the frame. It did not look pretty, but it did its job. The brake lines were hard to connect to the pedals due to its length, however we 
came up with a DIY solution using zip ties to connect the pedal to the master cylinder. Since the it did not reach all the way, we covered the distance 
by using two thin metal slabs that would be connect the pedal with the screws below the cylinder in such a way that the cylinder would compress when the
pedal is pushed.

(drilling hole using lathe), (brake bracket), (zip tie solution)

The steering column was used by cutting up a steel pipe and attaching it to the steering spindles. Since our design had our steering wheel slightly offset
to the side, the spindles were cut using a metal table saw and sanded down to screw on the spindle screw heads. A lot of trial and minor adjustments were
needed in order to make steering smooth and equal in both directions. The front steering knuckle was welded onto the frame and was attached to the front 
wheels. We installed the knuckles at an small angle so that the wheels would have a slight negative camber which would provide more control during cornering.

<table align="center">
  <tr>
    <td style="padding-right: 30px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/1105e063-d82b-4f90-a9bb-fbe41ce6aa9a" width="338.86" height="270" alt="Smoothing out the surface for the knuckle">
      <br>
      <div>Smoothing out the surface for the knuckle</div>
    </td>
    <td style="padding-right: 30px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/5670b965-eaef-430c-81f9-2a2e2b62c020" width="232.37" height="320" alt="Welding steering knuckle">
      <br>
      <div>Welding steering knuckle</div>
    </td>
    <td style="text-align: center;">
      <img src="https://github.com/user-attachments/assets/7c200ebe-4ed1-4a33-9414-4caeb3357fb3" width="232.37" height="320" alt="Front steering system">
      <br>
      <div>Front steering system</div>
    </td>
  </tr>
</table>

| ![Smoothing](https://github.com/user-attachments/assets/1105e063-d82b-4f90-a9bb-fbe41ce6aa9a) | ![Welding](https://github.com/user-attachments/assets/5670b965-eaef-430c-81f9-2a2e2b62c020) | ![Front Steering](https://github.com/user-attachments/assets/7c200ebe-4ed1-4a33-9414-4caeb3357fb3) |
|:--:|:--:|:--:|
| **Smoothing out the surface for the knuckle** | **Welding steering knuckle** | **Front steering system** |

Finally, we put on the chain on the sprocket and connected the gas pedals in order to test our go-kart to see if it runs. Right off the bat, we noticed that
the sprocket was not in line with the engine as it would hit the outer casing of the engine causing wear and tear. Secondly, the chain did not have enough
tension which might cause the sprocket to skip teeth which might damage the chain or sprocket. Also, one of our tie rods snapped in half which could be due
to the fact the our steering column did not have a mounting column which decrease the chance of the driver accidentally breaking the tie rod/steering column
by steering to far out.

<p align="center">
  <img src="https://github.com/user-attachments/assets/e2374a31-e4b5-465c-a8dd-d22b2281d8e6" alt="Steering column holder" width="400" height "500">
  <br/>
  <em>Steering column holder</em>
</p>

After fixing all of these issues, it was time for race day! It went well all things considered as our kart did not fail at all. We did have to tighten the CVT 
bolts after each run but apart from that our kart performed well. I would like to give a special shout out to my team for their collaboration and dedication 
in this project as it made this experience both highly enjoyable and deepy rewarding!


## Video of me driving the Go-kart!

https://github.com/user-attachments/assets/fb845483-d172-4a8d-8a8e-c6a1d2ca0941

