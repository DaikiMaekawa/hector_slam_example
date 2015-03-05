## Install the dependency packages

```sh
$ rosdep install hector_slam_example
```

## Usage

#### openni

```sh
$ roslaunch hector_slam_example hector_openni.launch
```    

#### UTM-30LX

```sh
$ roslaunch hector_slam_example hector_hokuyo.launch
```

#### UST-10LX/20LX

```sh
$ roslaunch hector_slam_example hector_hokuyo_eth.launch
```

[![rviz](http://img.youtube.com/vi/xo64T0jgKKQ/0.jpg)](https://www.youtube.com/watch?v=xo64T0jgKKQ)

## License

Copyright (c) 2014, [Daiki Maekawa](http://daikimaekawa.strikingly.com/). (MIT License)

See LICENSE for more info.
