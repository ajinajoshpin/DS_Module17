# Ex23 Depth First Graph
## DATE: 24/04/25
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. Start 
2. Allocate memory for a new node. 
3. Set the vertex field of the new node to the given value v. 
4. Set the next pointer of the new node to NULL. 
5. Return the newly created node. 
6. End
## Program:
```
/*
Program to traverse the graph below in the depth first fashion
Developed by:AJINA JOSHPIN
RegisterNumber:212223230008
*/
#include <stdio.h> 
#include <stdlib.h> 
struct node { 
int vertex; 
struct node* next; 
}; 
struct node* createNode(int v); 
struct Graph { 
int numVertices; 
int* visited; 
// We need int** to store a two dimensional array. 
// Similary, we need struct node** to store an array of Linked lists 
struct node** adjLists; 
};*/ 
struct node* createNode(int v) { 
struct node* newNode=malloc(sizeof(struct node)); 
  
  
newNode->vertex=v; 
newNode->next=NULL; 
return newNode; 
} 
```

## Output:


![image](https://github.com/user-attachments/assets/09151172-032f-4e3c-a997-675cfd63d46b)


## Result:

Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
