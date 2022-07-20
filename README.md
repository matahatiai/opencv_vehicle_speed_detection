# Vehicle Speed Detection
### RESULT

<img src="">

Technologies used :
- Python
- opencv
- dlib
<br>

Tasks breakdown
1. Vehicle Detection
    - We are using Haarcascade classifier to identify vehicles.
2. Vehicle Tracking - ( assigning IDs to vehicles )
    - We have used corelation tracker from dlib library.
3. Speed Calculation
    - We are calculating the distance moved by the tracked vehicle 
		  in a second, in terms of pixels, so we need pixel per meter
		  to calculate the distance travelled in meters.
	- With distance travelled per second in meters, we will get the 
		  speed of the vehicle.

#### How to run project? 

Follow steps:

1. Clone repo :
`git clone https://github.com/matahatiai/opencv_vehicle_speed_detection.git`

2. cd (change directory) into opencv_vehicle_speed_detection
`cd opencv_vehicle_speed_detection`

3. Create virtual environment
`python speed_check.py`

