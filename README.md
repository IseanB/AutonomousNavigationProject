# Autonomous Trucking Project
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Trucks with trailers are a key constituent of the trucking and transportation services sector. They are one of the life-lines for economies across the world. However, in order to fully utilize the current work done on autonomous vehicles, we need to safely adapt these technologies to autonomous trucks. One such issue is a slower stopping time, compared to cars. This is a big built in weakness when reacting to unpredictable scenarios. (i.e. person walking in front of the truck from an occluded location.)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Our project explores extending auto-pilot software in order to be more suited for autonomous trucks. We introduce a perfectly positioned DVS (Dynamic Vision Sensor) that covers the major blind spots of a truck and also allows for extremely fast real-time algorithms to react to the scenarios listed above. Below is a list of our contributions along with a link to our code.


## Members:
Isean Bhanot, Samara Miramontes, Miguel Gutierrez

### Usage
1. Startup CARLA Server wtih "./CarlaUE4.sh -RenderOffScreen".
2. Spawn Truck Entity w/ autonomous software with "vglrun python automatic_control.py" or "python automatic_control.py".
3. (Optional) Spawn entities with "vglrun python generate_traffic.py"

### Visualize DVS Processed Stream
1. Follow the steps above.
2. Press 2 in the pop-up window.

#### Example DVS Stream
![image](https://github.com/IseanB/AutonomousNavigationProject/assets/44033533/6dc2b107-c6aa-4c36-b4d4-266150494301)
<img width="1284" alt="Screenshot 2024-06-04 at 9 40 50 PM" src="https://github.com/IseanB/AutonomousNavigationProject/assets/44033533/df074e90-a748-4687-bae2-c9220e04658e">

#### Report
https://docs.google.com/document/d/18JBF5FfwvE8_C1p8sU8ETbDwXi0DsRYLULXRwEuaIjI/edit?usp=sharing 
