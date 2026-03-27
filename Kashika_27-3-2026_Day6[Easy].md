<img width="2878" height="1400" alt="image" src="https://github.com/user-attachments/assets/61bed22e-254a-41ac-baa4-b16340b9542f" />
This problem asks to tell whether an elements double is present or not.
Brute force would include 2 loop (inner and outer) that would check a element and then double or half every other element so as to make sure whether the element has a double or is a double itself for some other element.
Better solution would be to use a hashset. We start a loop that picks up every element present in the array. The condition within then checks whether the element has a double or half present in the hashset. If yes, return true. If not, then add that element into the hashset. 
If the loop ends without returning, then return false.
