=========
KalmanFilter
=========

Introduction
------------

C++ Kalman Filter implementation send us an email if you are after something specific. This is a growing project -- work in progress.

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

    1.  Convert martix inverse computations to linear system solves 
        (current dependence on Eigen3 .inverse() functions for MatrixXd)
    2.  Pade approximation for matrix exponentials
    3.  Add Matrix fraction based process noise computation for Qd
    4.  Low level integration with LCM, ROS and potentially MOOS
    5.  EEF integration with use case examples
    6.  Generalized performance and consistency evaluation tools
    7.  Support for Julia/Python and Latex tools
    8.  Low level integration with XPDS for rapid prototyping and real-time deployments.
    







