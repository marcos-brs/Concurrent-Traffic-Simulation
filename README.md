<h1 align="center">Welcome to Concurrent Traffic Simulation Project 👋</h1>
<p>
  <a href="LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/mbrsantana" target="_blank">
    <img alt="Twitter: mbrsantana" src="https://img.shields.io/twitter/follow/mbrsantana.svg?style=social" />
  </a>
</p>

> A multithreaded program made in C++ and OpenCV that simulates traffic

![](.github/traffic_simulation.gif)

A traffic simulation in which vehicles move along the streets and cross intersections. With the increase in traffic in the city, traffic lights are treated for traffic safety. Each intersection is therefore equipped with a traffic light. In this project, an adequate thread-safe communication protocol between vehicles and intersections was implemented to complete a simulation. Simultaneous programming concepts (such as mutexes, locks and message queues) were used to implement the traffic lights and integrate them into the code base.


## Dependencies for Running Locally
* cmake >= 2.8
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* OpenCV >= 4.1
  * The OpenCV 4.1.0 source code can be found [here](https://github.com/opencv/opencv/tree/4.1.0)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./traffic_simulation`.

## Author

👤 **Marcos Santana**

* Twitter: [@mbrsantana](https://twitter.com/mbrsantana)
* Github: [@zerocoolbr](https://github.com/zerocoolbr)
* LinkedIn: [@marcosbrs](https://linkedin.com/in/marcosbrs)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Marcos Santana](https://github.com/zerocoolbr).<br />
This project is [MIT](LICENSE) licensed.