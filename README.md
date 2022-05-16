# Source Code
Since this is a university team project, there are strict instructions from the teaching team to not post any code in a public repository.

# Table of Contents  
1. [Description](#mapability)

2. [Objectives/Milestones](#objectivesmilestones)

3. [How to use Mapability?](#how-to-use-mapability)
     - [About the Map Dialog](#about-the-map)
     - [Color Scheme Box](#color-scheme-box)
     - [Panning the Map](#panning-and-controlling-the-map)

4. [Screenshots and Demo of Mapability](#screenshots-and-demo-of-mapability)
     - [Multiple Locations](#choose-between-different-locations)
     - [Color Scheme Selector](#color-scheme-selector)
     - [Feature Flags / Toggle Elements Box](#toggle-elements-box)
     - [Shortest Path Finding Algorithm](#shortest-path-finding-algorithm)
     - [Ordered Multiple Stops](#ordered-multiple-stops)
     - [Travelling Courier Problem](#travelling-courier-problem)

5. [My Contribution](#my-contribution)

# Mapability
Designed and developed a GIS Mapping System in C++ using data from OpenStreetsMap. This map is designed for general use but also emphasises on making the map accessible to everyone. Thus, the name Mapability -> Maps + Accessibility. The motto for Mapability is to create a GIS Software for the need.

# Objectives/Milestones

*   1.  Using and Creating Efficient APIs.
         - [x] Created a new API of functions.
         - [x] Used STL data structures like ordered and unordered maps, vectors, and lists.
<br>

*   2.  Working on Graphical User Interface (GUI) to create a visual and interactive map.
         - [x] Developed a user interface system to display data in the map.
         - [x] Added many extra features and enhanced visual aesthetic of the mapping system. 
         - [x] Addressed to and Incorporated the accessibility features and themes for people with colorblindness. 

<br>


*   3.  Find the Shortest Path Algorithm.
         - This process involved implementing 4 algorithms.
            - [x] Depth First Algorithm [DFS]
            - [x] Breadth First Algorithm [BFS]
            - [x] Dijkstra's Algorithm
            - [x] A* Algorithm

<br>

*   4.  Solving the Travelling Courier Problem (similar to travelling salesman problem -> Optimize Delivery Routes).
         - Worked on different algorithms and methods to solve the problem.
           - [x] Greedy Method
           - [x] Ant Colony
           - [x] 2-Opt
           - [x] Multi-Dijkstra's Method
<br>
  
# How to use Mapability?
#### About the Map:
   - The team's goal was to make Mapability accessible to all. So, we tried to make all the features in the map easy to access and easy to understand.
     We have set up an About This Map button so that in case anyone gets lost on how to use any feature, they can click on the "About" button and       understand which button performs what action.
    
   <p align="center">

   <img width="1440" alt="About Map Button Location" src="https://user-images.githubusercontent.com/98042082/168441054-30a2df8f-2e7f-48f2-bacd-2c869460b270.png">
   <img width="1440" alt="About Map Dialog" src="https://user-images.githubusercontent.com/98042082/168441058-9ef926fd-429f-4d93-9789-b3fb3454bc3f.png">
   [Figure 1] About the Map Dialog
   <br><br>

   </p>
   
   #### Color Scheme Box:
   - We understand the importance of aesthetics and the visual fatigue caused to some people by looking at a certain color scheme for a long time. In addition to this, people with color-blindness have no alternative to use a color scheme as per their choosing. The team incorporated all these problems in Mapability. In the following steps, a user can understand how to change different color schemes as per their choosing.

   <p align="center">

   <img width="1440" alt="Color scheme button location" src="https://user-images.githubusercontent.com/98042082/168454124-910eb85b-a033-4177-abb9-1cfb02b38b54.png">
   <img width="1440" alt="Color scheme expanded drop down" src="https://user-images.githubusercontent.com/98042082/168454126-82ace0da-7122-4924-99d1-71424dd47cc8.png">
   [Figure 2] About the Map Dialog
   <br><br>
   </p>
   
   #### Panning and controlling the map:
   - In the next steps, we will be looking at how you can pan the map.
        - Control with your keyboard
        - Pan with your mouse
        - Click the buttons to pan
    
   <p align="center">

   <img width="1440" alt="Screen Shot 2022-05-14 at 9 58 11 PM" src="https://user-images.githubusercontent.com/98042082/168454224-6409ab28-fd9d-43c0-b5cb-6c14c8643b5d.png">
   [Figure 3] Panning buttons
   <br><br>
   <img width="1440" alt="Screen Shot 2022-05-14 at 10 14 49 PM" src="https://user-images.githubusercontent.com/98042082/168454228-c71e5d1d-5832-4ae6-a80a-eb4ee597ee51.png">
   [Figure 4] Pan using keyboard instructions
   <br><br>
   </p>
 
- *More info on how to use other features are followed in the next section.*
         <br><br>
# Screenshots and Demo of Mapability

#### Choose between different locations:
* <b>Multiple Locations</b>
   - User can choose to select any map location from the 19 available options.
      <p align="center">
      <img width="244" alt="Collapsed Drop Down" src="https://user-images.githubusercontent.com/98042082/167653332-d2b4d574-7fd3-41b9-af1d-8ac5c16becec.png">
      <br>
      [Figure 5] Collapsed Drop Down Menu to select different cities.
      <br>
      <br>
      <img width="1440" alt="Expanded Drop Down" src="https://user-images.githubusercontent.com/98042082/167653240-133beb54-72b4-4fcb-baac-1e22b13f3b4d.png">
      [Figure 6] Expanded Drop Down Menu to select different cities.
      <br><br>
      </p>

#### Color Scheme Selector:
* <b> Various Color Schemes </b>
   - User can choose from a variety of color schemes as per their perusal.
      <p align="center">
       <img width="1440" alt="Light Mode Scheme" src="https://user-images.githubusercontent.com/98042082/167658435-d0aae3c3-118d-4216-903c-590f26707f99.png">
       [Figure 7] Light Mode. 
       <br><br>
       <img width="1440" alt="Dark Mode Scheme" src="https://user-images.githubusercontent.com/98042082/167657788-ea3ca134-8a78-444c-bb4f-8c2f96fb37f9.png">
       [Figure 8] Dark Mode.
       <br><br>
       <img width="1440" alt="Greyscale Scheme" src="https://user-images.githubusercontent.com/98042082/167659542-8908cc4f-aa34-4d51-a73a-fa0f548fa704.png">
       [Figure 9] Greyscale.
       <br><br>
      </p>
    
   - The color schemes as shown above are seen in most of the maps and applications. However, we went a step beyond and included color schemes that supports people with color blindness as well. Our team identified that there are three major types of color blindness: Protan, Deutan, and Tritan.
      
      <p align="center">
      <img width="1440" alt="Protan" src="https://user-images.githubusercontent.com/98042082/167661451-d962dfa4-e2e0-4917-a6fa-55202f5508ce.png">
      [Figure 10] Protan.
      <br><br>
      <img width="1440" alt="Deutan" src="https://user-images.githubusercontent.com/98042082/167661635-025cd997-583a-4391-8e6e-5d27a7c0ca06.png">
      [Figure 11] Deutan.
      <br><br>
      <img width="1440" alt="Tritan" src="https://user-images.githubusercontent.com/98042082/167661728-8d9bfeca-56c4-45db-a0b4-8dc6f6c96941.png">
      [Figure 12] Tritan.
      <br><br>
      </p>

#### Toggle Elements Box:
* <b> Feature Flags/ Toggle Elements </b>
  
   - Added code to toggle displaying Elements as needed by the developer. These feature flags can help identify if all the different elements like buildings, POIs, POI icons are being drawn and displayed correctly or not.
    <p align="center">
    <img width="1440" alt="Toggle Button" src="https://user-images.githubusercontent.com/98042082/167664266-98800d29-e938-4c25-b935-c37d07f2a180.png">
    [Figure 13] Feature Flag/Toggle Button
    <br><br>
    </p>
    
#### Shortest Path Finding Algorithm:
* <b> Path between two points </b>
   -  Started with Depth First Search Algorithm [DFS]. With this algorithm, we just got a dialog box saying if a path exists or not.
   <p align="center">
   <img width="1100" alt="DFS" src="https://user-images.githubusercontent.com/98042082/167681304-00bb24d8-8178-450d-a9ec-4d35691d95b5.png">
  [Figure 14] Depth First Algorithm result [DFS]
  <br><br>
   </p>
   -  Next, implemented Breadth First Search [BFS], we were able to trace back the route but the algorithm did not avoid re-expansion, which caused the program to crash. So, we implemented Dijkstra's Algorithm to find the shortest and fastest path to get from one point to another. We used a min heap (priority queue) data structure to store the best travel times.
  <p align="center">
  <img width="1440" alt="Dijkstra" src="https://user-images.githubusercontent.com/98042082/167682559-05e4a846-1be1-44d0-bb70-f592a5e9be2f.png">
  [Figure 15] Result generated by using Dijkstra's algorithm
  <br><br>
  </p>
 
#### Ordered Multiple Stops:
* <b> Ordered Multiple Stops </b>
   -  Ordered Multiple Stops is an extra feature that we added to our map. This is useful for people planning trips, cab drivers picking and dropping off passengers in an ordered manner.
  <p align="center">
         </p>

#### Travelling Courier Problem:
* <b> Solving the Travelling Courier Problem </b>
   -  To solve for this problem, we had implemented various algorithms that gave us the best Quality of Result (QoR). <br>
      We used Feature Flags to test our different methods and test which method was the most effective.
  <p align="center">
         <img width="1042" alt="Methods to solve Travelling courier problem" src="https://user-images.githubusercontent.com/98042082/167763682-f33a813c-c2fc-49d4-9143-92808eb55172.png">
         [Figure 16] Different Methods used to solve the problem 
         <br><br>
         
  </p>
        
# My Contribution:
  <p align="center">
         <img width="1440" alt="Git line changes" src="https://user-images.githubusercontent.com/98042082/167908402-c4fcf4ac-1f91-498b-982b-f2ff86e1714a.png">
         [Figure 17] Total line changes I committed while working on this project
         <br><br>
  </p>
