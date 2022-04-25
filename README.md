# A* Phase 2
## Badges
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Authors
- [Sameep Pote](https://github.com/Sameep2808) - Graduate student at University of Maryland pursuing M.Eng. Robotics.Loves to watch animes.

URL: https://github.com/Sameep2808/A_star.git
## License
```
MIT License

Copyright (c) 2022 Sameep Pote

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```


## Output

### Inputs
Start Point = (10,10)
Goal = (389,239)

### Visualization
![g1](https://github.com/Sameep2808/A-/blob/main/Videos/g1.gif)
### Path
![p1](https://github.com/Sameep2808/A-/blob/main/Videos/p1)

## Dependencies and Technologies used

- Programming language : Python
- Operating System : Ubuntu 20.04
- Packages : OpenCV, numpy

## Run

## FOR Phase 1 Map
1. Download the repository in src folder of catkin workspace
```
git clone https://github.com/Sameep2808/A-
```
2. Run the python file
```
python3 A.py 
```
3. Enter the Initial And goal values
```
Enter Clearence:
5
Enter Initial X (Range: 0 - 399):
10
Enter Initial Y (Range: 0 - 249):
10
Enter Start Angle:
0
Enter Goal X (Range: 0 - 399):
389
Enter Goal Y (Range: 0 - 249):
239
Enter RPM1: (5 - 10)
5
Enter RPM2: (5 - 10)
10
```
4. Wait For the Output

## FOR ROS MAP

1. Download the repository in src folder of catkin workspace
```
git clone https://github.com/Sameep2808/A-
```
2. Run the python file
```
python3 ros_map.py 
```
3. Enter the Initial And goal values
```
Enter Clearence:
5
Enter Initial X (Range: 0 - 1000):
10
INVALID X SETTING INITIAL X AS LEAST RADIUS
Enter Initial Y (Range: 0 - 1000):
10
INVALID Y SETTING INITIAL Y AS LEAST RADIUS
Enter Start Angle:
0
INVALID POINTS SETTING INITIAL POINT AS [0,0]
Enter Goal X (Range: 0 - 1000):
1000
INVALID X SETTING GOAL X AS 1000
Enter Goal Y (Range: 0 - ymax):
1000
INVALID Y SETTING GOAL Y AS 1000
Enter RPM1: (5 - 10)
5
Enter RPM2: (5 - 10)
10
```
4. Wait For the Output

