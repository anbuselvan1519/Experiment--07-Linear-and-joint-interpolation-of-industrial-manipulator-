# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator
## Name: Anbuselvan.S
## Reference No: 212223240008

### Aim :
To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
Instrial manipulator , teach pendant and associated program platform 
      
### Theory:
The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
   
### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.

### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.

![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 

### Program : 
DART studio screen shots for linear and joint interpolation 
![image](https://github.com/anbuselvan1519/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139841744/1a0c4996-74e6-48bc-a8c6-e9214e57b7cc)
![image](https://github.com/anbuselvan1519/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139841744/d7ca367a-e849-4c59-b086-b158e9b59460)

### Robot movements 
![image](https://github.com/anbuselvan1519/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139841744/390bd81a-f41f-46a5-970e-04c44c886366)
![image](https://github.com/anbuselvan1519/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139841744/5d94f3ce-17c5-47fa-92e9-9c8cb5b56f45)
![image](https://github.com/anbuselvan1519/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139841744/80ae8708-3eb5-4695-bb68-c1f318d6c483)
![image](https://github.com/anbuselvan1519/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139841744/85b4d240-0f69-447e-8f27-dd1324b38b54)

### Results:
Thus the program for linear and joint interpolation of industrial manipulator has executed successfully.
