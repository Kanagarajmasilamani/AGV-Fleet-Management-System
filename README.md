# AGV-Fleet-Management-System

**Project Description:**

The current industrial revolution mainly focuses on automation, artificial intelligence, and interconnectivity to optimize and manage the production processes and supply chain. As a result of it, AGVs are used in a range of industries to handle and transport items from one place to another. Currently, most of the AGVs in operations are portable and follow marking lines or magnets on the floor for navigation from one location to another. Since this type of AGV is restricted to travels only on dedicated paths, is less flexible, and gets stopped when comes in contact with obstacles, our project focuses on improving the flexibility of AGVs by decision making and navigating to the desired goal location with im-mobile and mobile obstacle avoidance. Implementation of our objective is divided into three main parts - mapping, localization, and navigation of an AGVs in the environment. **ROS framework is used to code, coppeliasim and Rviz tool is used to visualize the simulation process.**


**Methodology :**<br />

Mapping - Simultaneous Localisation And Mapping <br />
Navigation Stack - Move base <br />
Global planner - NavfnROS ( Based on dijkstra algorithm ) <br />
Local planner - Dynamic Window Approach <br />
Localisation - Adaptive Monte Carlo Localisation<br />

**Installation**

Tested with ROS 1 neotic under ubuntu 20.04

**Works**

**1) Warehouse Environment created in Coppeliasim and mapping is done with SLAM alogirthm**

![image](https://user-images.githubusercontent.com/109582119/179721854-d05c20b1-498d-44d2-b3d0-2aefa252f19e.png)

**2) Localisation of Robot using AMCL**

![image](https://user-images.githubusercontent.com/109582119/179722045-2e174537-448a-47f8-843f-cc49e661111d.png)

**3) global and local planner visualisation in Rviz**

![image](https://user-images.githubusercontent.com/109582119/179722361-48a79c76-e48a-4601-b0ff-2aabe92589ce.png) <br />

Fig:-3.1 Setting up of navigation goal <br />


![image](https://user-images.githubusercontent.com/109582119/179722407-34868edf-5d18-46e2-a7bb-e81537649260.png) <br />

Fig:-3.2 global plan visualisation <br />


![image](https://user-images.githubusercontent.com/109582119/179722692-75085d21-b249-4b24-a38b-aeb8645ea1cb.png) <br />

Fig:-3.3 Local plan visualisation<br />


**4) Updating Obstacles in the map visualisation**

![image](https://user-images.githubusercontent.com/109582119/179723266-1dca073c-0651-4795-8a95-e9ccb21106bb.png) <br />

**5) working of multi-bot navigation**

![image](https://user-images.githubusercontent.com/109582119/179723467-7f18bf94-0921-46e9-95ce-71644369059e.png)




