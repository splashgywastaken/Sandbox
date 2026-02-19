## Falling sand simulation
Simple falling sand simulation like in early 00's made using C++, OpenGL, 

## Technologies
![OpenGL](https://img.shields.io/badge/-OpenGL-lightgrey?style=for-the-badge&logo=opengl&logoColor=white&logoWidth=30)
![C++](https://img.shields.io/badge/C%2B%2B-lightgrey?style=for-the-badge&logo=cplusplus&logoColor=white)

## How to build
Build using MSVC v145 through Visual Studio

## Hot to use

### Control brush and canvas
* ```MWheelUP```/```MWheelDown``` to control size of brush
* ```RMB``` to clear space under brush
* ```C``` Key to clear drawing space

### Control different elements through numbers:
1. Sand - solid, falls down
2. Water - liquid
3. Stone - solid, stays at one place
4. Salt - solid, could be dissolved by water
5. Fire - burns, can be put out with water
6. Wood - solid, can be burned by fire