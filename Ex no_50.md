# EX 50 C function to delete a node from a Doubly Linked List at the beginning of the list.
## DATE:
## AIM:
To write a C function to delete a node from a Doubly Linked List at the beginning of the list.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a function to perform delete operation. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.    

## Program:
```
/*
C function to delete a node from a Doubly Linked List at the beginning of the list.

Developed by: 
RegisterNumber:  
*/
void delete() 
{ 
struct Node *p; 
p=head; 
if(p==NULL) 
{ 
printf("UNDERFLOW \n"); 
} 
else if(head->next==NULL) 
{ 
head=NULL; 
free(head); 
printf("Node deleted\n"); 
} 
else 
{ 
p=head; head=head->next; 
head->prev=NULL; 
printf("Node deleted\n"); 
} 
}
```

## Output:

![image](https://github.com/user-attachments/assets/993cc833-bfa7-4751-b0b9-333ce52ef5a1)



## Result:
Thus the program was executed and the output was verified successfully.
