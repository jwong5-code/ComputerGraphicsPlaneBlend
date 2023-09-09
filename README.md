# Outline
I used the same airplane model created in another repository and designed a flight simulation using Python code and the bpy library. 

In this video link (https://drive.google.com/file/d/1wa8iYpxr1hXZ2dJ58MMRqp7ATvJcdIBw/view?usp=drive_link), I had to choose between two flight samples from the video clip sequences of six samples (one simple and one complex).

The simple flight simulation will be the first. It has the simple straight motion in the flight, but the camera angle changes back and forth at a smooth angle.
The more complex will be sample 3 with the plane moving up while the plane twists

There must be four cameras positioned during the flight.
Camera A: Mounted to the pilot position of the plane
Camera B: Stationed on the ground will record the takeoff and landing.
Camera C: Floating in the air, recording one of the attempts at simulating one of the flight samples (the simpler of two).
Camera D: Stationed in the air, recording the second attempt at simulating the other of the flight samples (the more complicated of two.) 

There were three cloud instances in the sky created using the cloud generator.
There was a light object representing the position of the sun.

# Customization
I chose to modify and customize my plane model by using python and the bpy library to change the color of the plane depending on its translation in the 3D map. Essentially the plane is like a chameleon. The color coding used will be in the RGB diffuse scale (for more information see appendix B). The x axis represents R, the y axis represents G, and the z axis represents B. For example, if the plane were to translate in the x axis, it would turn more red. The color of the plane will only change as long as it translates in the positive axis. If it goes in the negative direction, it will automatically be set to 0 as negative numbers are not read. For example, if the plane went straight up it would turn blue, if it went straight down it would be black. Furthermore, the color white is generated on the RGB scale if there is an equal ratio or value in RGB and it is higher or equal to 1. In short, this would happen to a plane but very temporarily if it was translating in all axes positive at an equal amount.
