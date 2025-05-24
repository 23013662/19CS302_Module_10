# EX 46 C function to traverse the linked list and display it in the following format.
## DATE:
## AIM:
To write a C function to traverse the linked list and display it in the following format.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a functions to traverse the linked list and display it in the following format. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End .   

## Program:
```
/*
C function to traverse the linked list and display it in the following format.

Developed by:santhiya c 
RegisterNumber: 212223060247 
*/
struct Node{ 
char data; 
struct Node *next; 
}*head;  
void display() 
{ 
struct Node *temp; 
temp=head; 
while(temp!=NULL) 
{ 
printf("%c\n",temp->data); 
temp=temp->next; 
} 
 
}
```

## Output:

![image](https://github.com/user-attachments/assets/1ac698c9-e830-4a5a-88be-4b2c5ca19022)



## Result:
Thus the program was executed and the output was verified successfully.
