## Install the dependency packages

```sh
$ sudo aptitude install ros-<distro>-hector-slam-launch
$ sudo aptitude install ros-<distro>-depthimage-to-laserscan
```

#### openni

```sh
$ sudo aptitude install ros-<distro>-openni2-launch
```
    
#### UTM-30LX

```sh
$ sudo aptitude install ros-<distro>-hokuyo-node
```

## Usage

#### openni

```sh
$ roslaunch hector_openni.launch
```    

#### UTM-30LX

```sh
$ roslaunch hector_hokuyo.launch
```

[![rviz](http://img.youtube.com/vi/xo64T0jgKKQ/0.jpg)](https://www.youtube.com/watch?v=xo64T0jgKKQ)

## License

Copyright (c) 2014, [Daiki Maekawa](http://daikimaekawa.strikingly.com/). (MIT License)

See LICENSE for more info.
