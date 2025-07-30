# Design
In our first session, we established the core parameters for our project: a battery-powered mini car that must drive a specific distance in a specific time (X distance in X seconds), with the added complexity of optionally curving around two obstacles placed along the perpendicular bisector of the course. This means our vehicle not only needs precise speed control, but also the ability to execute turns on command.

After reviewing various drivetrain and chassis configurations, we decided on a three-wheel design: two independently powered front wheels, each driven by its own motor and axle, and a single caster ball at the rear for passive support. This layout allows for differential steering — by varying the relative speed of the two motors, the vehicle can curve effectively without the need for a steering linkage. This also simplifies the mechanical design and minimizes weight.

To visualize our concept, I created a rough CAD model to map out the geometry of the vehicle, including wheel placement, motor mounts, and battery housing. While the CAD is still in early development, it gave us a clearer sense of the dimensions we’re working with and revealed potential spacing issues that we’ll need to address in later iterations. Here is the CAD:

<img width="850" height="731" alt="Screenshot 2025-07-29 at 9 26 02 PM" src="https://github.com/user-attachments/assets/2d430950-045e-43cb-a96a-6cf51382bb12" />

We have not yet decided on a battery pack, nor have we decided on what motors to use.

Looking ahead, we plan to begin prototyping the frame and testing basic forward motion. For this, we anticipate needing hardware such as motor controllers (for precise speed regulation), an onboard microcontroller (likely an Arduino or similar), and a reliable rechargeable battery system. 

**Time Spent: 4 hours**
