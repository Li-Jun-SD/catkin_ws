# catkin_ws
my steps on ROS tutorials!
if using in other computer, please run this command-line:
"source /ur address/catkin_ws/devel/setup.bash"

2017/09/19/16:28
关于ROS与C++入门教程-写简单服务端和客户端
有个问题啊，/src/beginner_tutorials/CMakeLists.txt最后要加上
add_dependencies(add_two_ints_server ${beginner_tutorials_EXPORTED_TARGETS})
add_dependencies(add_two_ints_client ${beginner_tutorials_EXPORTED_TARGETS})
否则会提示找不到头文件，这个CMake不太懂啊
