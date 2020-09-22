# flash_bike
A custom electric bicycle with a max speed of 60 kph. Inspired by Tesla and built for fun.

## Enclosure Design
The enclosure is made out of a combination of 6oz and 9oz E-Glass material. I made a styrofoam mould based on a CAD design and shaped it using a plastic guideline. The fiberglass was done in two halves using Vaseline as a cheap and innovative release agent.
![Picture of completed bike](/images/bike.jpg)
The low center of gravity of the design lets the bike get up to high speeds making it super fun during the summer. The door is completely flush since it was created by using the existing case as the mould. This makes it water proof and very stylish. It also has an integrated door lock mechanism using a simple furniture lock for added security.

## Electrical Design
One BLDC hub motor drives the rear wheel of the bike with a wheel torque of up to 40 N m. It's connected to a speed controller which uses simple hall effect feedback to engage MOSFETS which output a 3-phase power signal. The enclosure is encased in a steel box seen below. 
![GitHub Logo](/images/controller.jpg)
The controller puts out a whopping 1500 watts of power which is pulled from a 960 watt-hour lithium ion battery. It can travel up to 50 km on a single charge.


