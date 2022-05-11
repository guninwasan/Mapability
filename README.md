# City-Mapper [Mapability]
Designed and developed a GIS Mapping System in C++ using data from OpenStreetsMap. This map is designed for general use but also emphasises on making the map accessible to everyone. Thus, the name Mapability -> Maps + Accessibility. The motto for Mapability is to create a GIS Software for the need.

## Source Code
Since this is a university team project, there are strict instructions from the teaching team to not post any code online.

## Objectives/ Milestones

*   1.  Using and Creating Efficient APIs.
         - Created a new API of functions.
         - Initially used STL data structures like ordered and unordered maps, vectors, and lists.
<br>

*   2.  Working on Graphical User Interface (GUI) to create a visual and interactive map.
         - Developed a user interface system to display data in the map.
         - Added many extra features and enhanced visual aesthetic of the mapping system. 
         - Addressed to and Incorporated the accessibility features and themes for people with colorblindness. 

<br>


*   3.  Find the Shortest Path Algorithm.
         - This process involved implementing 4 algorithms.
            - Depth First Algorithm [DFS]
            - Breadth First Algorithm [BFS]
            - Dijkstra's Algorithm
            - A* Algorithm

<br>

*   4.  Solving the Travelling Courier Problem (similar to travelling salesman problem -> Optimize Delivery Routes).
         - Worked on different algorithms and methods to solve the problem.
           - Greedy Method
           - Ant Colony
           - 2-Opt
           - Multi-Dijkstra's Method
<br>


## Screenshots and Demo of Mapability

* <b>Multiple Locations</b>
   - User can choose to select any map location from the 19 available options. (Figure 1 and Figure 2).
      <p align="center">
      <img width="244" alt="Collapsed Drop Down" src="https://user-images.githubusercontent.com/98042082/167653332-d2b4d574-7fd3-41b9-af1d-8ac5c16becec.png">
      <br>
      [Figure 1] Collapsed Drop Down Menu to select different cities.
      <br>
      <br>
      <img width="1440" alt="Expanded Drop Down" src="https://user-images.githubusercontent.com/98042082/167653240-133beb54-72b4-4fcb-baac-1e22b13f3b4d.png">
      [Figure 2] Expanded Drop Down Menu to select different cities.
      <br><br>
      </p>

* <b> Various Color Schemes </b>
   - User can choose from a variety of color schemes as per their perusal.
      <p align="center">
       <img width="1440" alt="Light Mode Scheme" src="https://user-images.githubusercontent.com/98042082/167658435-d0aae3c3-118d-4216-903c-590f26707f99.png">
       [Figure 3] Light Mode. 
       <br><br>
       <img width="1440" alt="Dark Mode Scheme" src="https://user-images.githubusercontent.com/98042082/167657788-ea3ca134-8a78-444c-bb4f-8c2f96fb37f9.png">
       [Figure 4] Dark Mode.
       <br><br>
       <img width="1440" alt="Greyscale Scheme" src="https://user-images.githubusercontent.com/98042082/167659542-8908cc4f-aa34-4d51-a73a-fa0f548fa704.png">
       [Figure 5] Greyscale.
       <br><br>
      </p>
    
   - The color schemes as shown above are seen in most of the maps and applications. However, we went a step beyond and included color schemes that supports people with color blindness as well. Our team identified that there are three major types of color blindness: Protan, Deutan, and Tritan.
      
      <p align="center">
      <img width="1440" alt="Protan" src="https://user-images.githubusercontent.com/98042082/167661451-d962dfa4-e2e0-4917-a6fa-55202f5508ce.png">
      [Figure 6] Protan.
      <br><br>
      <img width="1440" alt="Deutan" src="https://user-images.githubusercontent.com/98042082/167661635-025cd997-583a-4391-8e6e-5d27a7c0ca06.png">
      [Figure 7] Deutan.
      <br><br>
      <img width="1440" alt="Tritan" src="https://user-images.githubusercontent.com/98042082/167661728-8d9bfeca-56c4-45db-a0b4-8dc6f6c96941.png">
      [Figure 8] Tritan.
      <br><br>
      </p>

* <b> Feature Flags/ Toggle Elements </b>
  
   - Added code to toggle displaying Elements as needed by the developer. This functionality can be extended as an extra feature to the user if the user       wants to make the map more simplistic.
    <p align="center">
    <img width="1440" alt="Toggle Button" src="https://user-images.githubusercontent.com/98042082/167664266-98800d29-e938-4c25-b935-c37d07f2a180.png">
    [Figure 9] Feature Flag/Toggle Button
    <br><br>
    </p>
    
* <b> Path between two points </b>
   -  Started with Depth First Search Algorithm [DFS]. With this algorithm, we just got a dialog box saying if a path exists or not.
   <p align="center">
   <img width="1100" alt="image" src="https://user-images.githubusercontent.com/98042082/167681304-00bb24d8-8178-450d-a9ec-4d35691d95b5.png">
  [Figure 10] Depth First Algorithm result [DFS]
  <br><br>
   </p>
   -  Next, implemented Breadth First Search [BFS], we were able to trace back the route but the algorithm did not avoid re-expansion, which caused the program to crash. So, we implemented Dijkstra's Algorithm to find the shortest and fastest path to get from one point to another. We used a min heap (priority queue) data structure to store the best travel times.
  <p align="center">
  <img width="1440" alt="image" src="https://user-images.githubusercontent.com/98042082/167682559-05e4a846-1be1-44d0-bb70-f592a5e9be2f.png">
  [Figure 11] Result generated by using Dijkstra's algorithm
  <br><br>
  [Demo 1] Demoing Dijkstra Algorithm
  <br><br>
  </p>
 
* <b> Ordered Multiple Stops </b>
   -  Ordered Multiple Stops is an extra feature that we added to our map. This is useful for people planning trips, cab drivers picking and dropping off passengers in an ordered manner if it is required.
  <p align="center">
       [Demo 2] Demoing Ordered Multiple Stop
         <br><br>
         </p>
* <b> Solving the Traveling Courier Problem </b>
   -  To solve for this problem, we had implemented various algorithms that gave us the best Quality of Result (QoR). <br>
      We used Feature Flags to test our different methods and test which method was the most effective.
  <p align="center">
         <img width="1042" alt="image" src="https://user-images.githubusercontent.com/98042082/167763682-f33a813c-c2fc-49d4-9143-92808eb55172.png">
         [Figure 12] Different Methods used to solve the problem 
         <br><br>
         <img width="1012" alt="image" src="https://user-images.githubusercontent.com/98042082/167908524-2430219d-a8ce-4660-83e7-1c01f6bf0a7a.png">
         [Figure 13] QoR of different methods 
         <br><br>

  </p>
        
        
## My Contributions:
  <p align="center">
         <img width="1440" alt="image" src="https://user-images.githubusercontent.com/98042082/167908402-c4fcf4ac-1f91-498b-982b-f2ff86e1714a.png">
         [Figure 14] Total line changes committed while working on this project
         <br><br>
  </p>
