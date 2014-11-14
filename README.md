ElevatorSystem
==============
design elevator system

use the following design pattern:

1. command pattern<br>
passengar send command object to control center, the control center send the command to different elevators.

2. observer pattern<br>
there is monitor in elevator or at the floor to display the elevator status, which need are like subscriber to the elevator status, this can push.

3. status pattern<br>
the elevator handle open door request, close door request in different way depends on the current status is moving or stay, so it's differnt behavior for different status, can use status pattern here. 
