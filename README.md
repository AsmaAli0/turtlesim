# turtlesim
## Manipulate with turtlesim package in ROS noetic
### -first 
we will start with the ``roscore`` command and please notice that you CAN NOT run the command `` roscore `` in two windows 

![Screenshot 2024-08-02 121820](https://github.com/user-attachments/assets/c008a873-05c0-433c-bc4e-f297c1a91da3)
 as you can see an error accord when i started the roscore command in another window 

### 2-turtlesim
For this tutorial we will also use turtlesim. after you ran the command ``roscore`` Please run the following in a new terminal tab :
```
$ rosrun turtlesim turtlesim_node

```

Then a window will appear as shown below in the screenshot


<img width="614" alt="T2" src="https://github.com/user-attachments/assets/52858666-4270-49d6-b5ad-d17fb1db8996">

### 3-turtle keyboard teleoperation
We'll also need something to drive the turtle around with. Please run in a new terminal:

```
$ rosrun turtlesim turtle_teleop_key

```

you can use the arrows keys to move the turtle around! 


https://github.com/user-attachments/assets/d3e74435-4bf7-4ae5-b289-4b223ef632da

## -Using rqt_graph
rqt_graph creates a dynamic graph of what's going on in the system.
In a new terminal tab :

```
$ rosrun rqt_graph rqt_graph
```

<img width="368" alt="t3" src="https://github.com/user-attachments/assets/6e6377fd-3dfc-4565-896e-748871b4a28c">



# Hope this was a useful toturial,try it out its easy and fun  !! 
