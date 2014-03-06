=========
KalmanFilter
=========

Introduction
------------

Another Kalman Filter implementation -- WORK IN PROGRESS -- send us an email if you are after something specific. This is a growing project.

Dependencies
------------

This library depends on the following packages:

    cmake
    Eigen

To download and compile
-----------------------

Get dependencies:

    sudo apt-get install cmake libeigen3-dev

Get KalmanFilter:

    git clone https://github.com/dehann/KalmanFilter.git

Navigate to the build directory:

    cd KalmanFilter/build
    cmake ..
    make -j
    
Planned updates
---------------

These are in the time permitting development pipeline

    Pade approximation for matrix exponentials
    Matrix fractions process noise Qd
    Low level integration with LCM, ROS and potentially MOOS
    EEF integration with use case examples
    Generalized performance and consistency evaluation tools
    Support for Julia/Python and Latex tools
    Low level integration with XPDS for rapid prototyping and real-time deployments
    







