<img width="2879" height="1393" alt="image" src="https://github.com/user-attachments/assets/0b174115-a2c4-4b77-a352-b005d670f0d1" />
Today's problem is similar to the one sorted earlier but kinda easier?? for me it was easier so yea anyways. This problem asked us to find two elements in the array that add upto the given target (Two Sum) but in a sorted array.
For me, this was easier as my first approach to solve the original Two Sum approach was similar, infact exactly the one that would satisfy this. 
I tried the binary search solution (kinda) where i take the first index (0) and the last index (n-1) and then add the elements present on the indexes and check whether it is equal to/less than/more than the target given. If equal, return the indexes. If less than, then increment low by 1. Otherwise, decrement high by 1.
If no such pair exists, return empty vector {}.
