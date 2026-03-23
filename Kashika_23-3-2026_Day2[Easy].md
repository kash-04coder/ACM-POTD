<img width="2878" height="1404" alt="image" src="https://github.com/user-attachments/assets/c5eef6b2-4773-4e73-a99e-4fda349e06ac" />
The Problem Of The Day was to "Two Sum". In the given problem, we have been gevin a vector and a target. We have to check which 2 elements from the array add up to the target. If no such pair is formed, return -1. 
The approach we used here was to initialise an unordered map pair. Then we run a loop. In the loop we initialize a variable that is the difference between the target and the current element. If we find the difference in the map, we return the index of the current element and the 2nd value of the mapped pair (index of the difference). Otherwise we simply add the index and its value to the map.
If no such pair is found, we return an empty vector.
