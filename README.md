# mode_controller_priority

<h3>Idea: priority</h3>
1. driver mode
2. autornomous driving mode

<h1>1. How to use</h1>

<pre><code>[remote PC]<br>
$ roscore
</code></pre><br>

To activate all sensors:
<pre><code>[TurtleBot SBC] <br>
$ roslaunch turtlebot3_bringup alltogether.launch
</code></pre>

<br>
To activate mode control function
<pre><code>[remote PC]<br>
$ roslaunch turtlebot3_example multiplexer.launch

$ rosrun rviz rviz -d `rospack find turtlebot3_description`/rviz/model.rviz (optional)

