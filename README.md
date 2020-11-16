# \<ros-service\>
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jstnhuang/ros-service)

An element for calling ROS services using roslibjs.
Version 2 is a hybrid element that supports Polymer 1 and Polymer 2.

- [Documentation](https://www.webcomponents.org/element/jstnhuang/ros-service/elements/ros-service)
- [Demo](https://www.webcomponents.org/element/jstnhuang/ros-service/demo/demo/index.html).
  Note that the demo requires a secure websocket server, since it is served over HTTPS.

## Installation
`bower install --save jstnhuang/ros-service`

## Running
1. Run the websocket 
`roslaunch rosbridge_server rosbridge_websocket.launch`
2. Run the rosservice tutorial
`rosrun rospy_tutorials add_two_ints_server`
3. Polymer run
`polymer serve`
