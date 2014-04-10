## Install the dependency packages


    sudo aptitude install ros-<distro>-hector-slam-launch
    sudo aptitude install ros-<distro>-depthimage-to-laserscan

### openni

    sudo aptitude install ros-<distro>-openni2-launch
    
### UTM-30LX

    sudo aptitude install ros-<distro>-hokuyo-node

## Usage

### openni

    roslaunch hector_openni.launch
    
### UTM-30LX

    roslaunch hector_hokuyo.launch
