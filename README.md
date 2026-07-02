# Ugv_Autonomous_Approach

Using the **Follow the gap** Approach As it is more simpler than making a map, then motion planning, then avoiding static obstacles.

we use a Free Map Approach (Dont Need A Map).

We Define The following concepts : 

1- Reactive Navigation : Using realtime Sensor Data to decide Driving Command

2- Planning for obstacle Avoidance : 

## How it works : 

**First** :  we find the nearst LIDAR Point 

**Second** : We Put Around this point An inflation Circle Equal to RB(Raduis of Robot Circle)

**Third** : We make all the points inside it Equal to 0 (Treat it like immedaite threat As inf means No Obstacle, 0 Means an Obsticale)

**Fourth** : Find the maximum lenght or distance (Max gap).

Using linear Relation between distacne and the Velocity 




## Simulation : 

## Real Hardware : 
