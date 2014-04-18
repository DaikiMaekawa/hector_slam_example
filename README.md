## Install the dependency packages


    sudo aptitude install ros-<distro>-hector-slam-launch
    sudo aptitude install ros-<distro>-depthimage-to-laserscan

#### openni

    sudo aptitude install ros-<distro>-openni2-launch
    
#### UTM-30LX

    sudo aptitude install ros-<distro>-hokuyo-node

## Usage

#### openni

    roslaunch hector_openni.launch
    
#### UTM-30LX

    roslaunch hector_hokuyo.launch

[![rviz](http://img.youtube.com/vi/xo64T0jgKKQ/0.jpg)](https://www.youtube.com/watch?v=xo64T0jgKKQ)

## License

Copyright (c) 2013, Daiki Maekawa. (MIT License)

See LICENSE for more info.
