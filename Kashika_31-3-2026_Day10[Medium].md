<img width="2879" height="1423" alt="image" src="https://github.com/user-attachments/assets/d5ddca6d-582f-4978-a866-301dbd0b8b14" />
We have to add 2 given number which are presented in the form of linked list ( i.e., 123 is represented as 1->2->3->NULL). 
Use a dummy node to build the result list easily. Keep a variable carry. Continue until both lists end AND no carry is left.
Start from the head (first node). Add digits from both lists. Keep track of carry (9+1 = 10 and we can't keep 10 in a single node, therefore we keep 0 in the node and carry 1 over). Create a new node for the result. Move to the next nodes.
