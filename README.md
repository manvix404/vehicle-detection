# vehicle-detection
Detecting and counting vehicles using opencv cascade classifier 

## Proposed System
The system uses cameras to capture images of the traffic flow at each intersection and analyzes them on the microcomputer. The system then uses the on-board Raspberry Pi computer to run a highly efficient model which analyzes video frames from the camera to determine the number of cars in the frame. It handles input from 4 different camera systems and decides optimal traffic light timings based on the inputs. <br>
The data is analyzed and calculated according to the traffic congestion in each road and traffic light duration for each intersection an algorithm is used to decide which road gets the right of way. The system then sends commands to the traffic lights via Wi-Fi to adjust their timing accordingly.

## GPIO pins used for the traffic light
### Traffic Light 1:
Red - 26<br>
Green - 21

### Traffic Light 2:
Red - 23<br>
Green - 3

## Steps to setup the Project
1. Make the LED connections based on the given pin numbers.
2. Upload cars.xml, main.ipynb and testing folder to your raspberry pi.
3. Run the last chunk in the notebook to start the project.
