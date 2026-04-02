<img width="2879" height="1429" alt="image" src="https://github.com/user-attachments/assets/08ea7a2b-2d51-456e-bc0d-8d711c68731c" />
The problem of the day is - Rotate the linked list right by k places
Find length n using traversal. Reduce unnecessary rotations that may give us the same LL as mid point. Make list circular, connect last node to head. Find new tail using steps that are denoted by length of LL minus the no. of rotation. Break the cycle at the next node to the new tail. This works because rotation is just rearranging pointers, not actually moving nodes one by one.
