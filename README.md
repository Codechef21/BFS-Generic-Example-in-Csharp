# BFS-Generic-Example-in-Csharp

Here is the pseudo code for the BFS implementation part: 

BFS(Graph, StartNode) 
  
  let Q be queue 
  Q.enqueue(StartNode)
mark StartNode as visited 
while(Q is not empty) 
 vertex = Q.dequeue()
for all neighbours w in vertex in Graph 
    if w is not visited 
        Q.enqueue(w)
        mark w as visited
 finish 
 
 
 #Here hashset has been used and <T> is a generic type parameter 
