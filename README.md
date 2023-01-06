# Emergency Vehicle Dispatch System
Dispatching an emergency vehicle according to the requirement (Ambulance(A), Fire Truck(F), 
Police Car(P)) to the desired zip code by calculating the minimum distance between the zip codes 
(desired location and all the other zipcodes where emergency vehicles are available). Dispatching 
the type of emergency vehicle which is available and is closest to the destination point.

## Motivation 
> In an emergency, it is very necessary to get help on time. But due to unavailability or delay in arrival, the situation becomes worse. So, we thought about the dispatch of emergency vehicles and tried to find the minimum path so that the required vehicle reaches on time.

We are using ***Dijkstra's algorithm*** for finding the shortest paths between nodes in a graph i.e between the areas using zip code

![Zipcode Flowchart](https://user-images.githubusercontent.com/110801658/211108061-70572fab-a39b-4500-ac15-ba4d2f36d84e.jpeg)

```
Vehicle Types:
        1 - Ambulance
        2 - Fire Truck
        3 - Police Car        
``` 
Vehicles which are available at zip codes with their distint vehicle ID is given here -->

![image](https://user-images.githubusercontent.com/110801658/211108655-78ea6aae-d6ef-4b96-a800-f2c128db5959.png)

# Screenshots
![image](https://user-images.githubusercontent.com/110801658/211107966-c637719b-f230-4540-8ea8-e5ec8a93d803.png)

![image](https://user-images.githubusercontent.com/110801658/211107795-1575d074-3ec8-4f4b-9eb9-d8810dfd3c5e.png)

![image](https://user-images.githubusercontent.com/110801658/211107885-b2525150-9cbf-4302-906d-73090edba58a.png)

## Learn more about Dijkstra's Algorithm
+ [GFG](https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/)
+ [Wikipedia](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
