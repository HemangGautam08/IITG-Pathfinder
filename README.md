# IITG-PATHFINDER


## Overview

This project is a web application designed to display the shortest path between any two places within IIT Guwahati. It utilizes a weighted-undirected graph where each intersection is treated as a node, and the shortest path is calculated using Dijkstra's Algorithm. The front-end of the application is built with React, while the back-end, responsible for the pathfinding algorithm, is implemented in Python.


## Features 

* Interactive map of IIT Guwahati.
* Displays the shortest path between selected start and end points.
* Utilizes Dijkstra's Algorithm for efficient pathfinding.
* Responsive and user-friendly interface.




## Prerequisites

* Node.js and npm installed.
* Python installed.
* Basic knowledge of React and Python.

## Usage

1. **Clone the repository**  
   ```bash
   git clone https://github.com/HemangGautam08/IITG-Pathfinder.git
   cd IITG-Pathfinder
2. **Set up the Python backend**
    ```bash
    python -m venv venv
    source venv/bin/activate 
    pip install flask flask-cors
3. **Start the backend server**    
    ```bash 
    python server.py
4. **Set up & launch the React frontend**
    ```bash
    npm install
    npm start

* You will see a map of IIT Guwahati.
* Select the start and end points on the map.
* Click on the "Find Path" button to display the shortest path between the two points.

## Frontend 
<img width="1433" alt="image1" src="https://github.com/HemangGautam08/IITG-Pathfinder/blob/main/assets/Screenshot%202025-06-20%20at%2011.47.32%E2%80%AFAM.png">

## Example

* If you entered your starting point 2 and ending point 51 then it will show you the path with shortest distance from the sorce i.e. 2 to destination i.e. 51.
<img width="1440" alt="image2" src="https://github.com/HemangGautam08/IITG-Pathfinder/blob/main/assets/Screenshot%202025-06-20%20at%2011.47.06%E2%80%AFAM.png">

 
