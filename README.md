<h1> Insertion Sort - Reverse Linked List Challenge </h1>


<h2> 1. Provide Big O Notation for each of your solutions</h2>
<p> Reverse Linked List
The solution is efficient with linear time complexity and constant space complexity, making it optimal for reversing a singly linked list.</p>

<p>Insertion Sort 
the time complexity is O(n²) due to the nested loops of the insertion sort algorithm, and the space complexity is O(n²) because of the storage of intermediate states of the array during sorting.</p>

<h2> 2. Research Quick, Bubble and Insertion sort. Describe which algorithm and how they perform.   </h2>

 1. Bubble Sort Algorithm:

Bubble Sort repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
The process is repeated until the list is sorted.
In each pass, the largest unsorted element "bubbles up" to its correct position.<br>

This Algorithm is <br>
Simple to understand and implement.<br>
Inefficient for large lists due to its  time complexity.<br>
Suitable for small datasets or educational purposes.<br>

2. Insertion Sort Algorithm:

Insertion Sort builds the final sorted array one item at a time.
It takes each element from the unsorted portion and inserts it into its correct position in the sorted portion.
The process involves shifting elements to make space for the new element.<br>

This Algorithm is <br>
Efficient for small or nearly sorted datasets.<br>
More efficient than Bubble Sort for small lists.<br>
Simple to implement and understand.<br>

3. Quick Sort Algorithm:

Quick Sort is a divide-and-conquer algorithm. It selects a "pivot" element and partitions the list into two sub-lists: elements less than the pivot and elements greater than the pivot.
The sub-lists are then recursively sorted.
The pivot selection and partitioning strategy can affect performance.<br>

This Algortithm is <br>
Efficient for large datasets and commonly used in practice.<br>
Performance depends on the choice of pivot and partitioning strategy.<br>
Often faster than other O(n log n) algorithms in practice due to smaller constant factors.<br>



<h2> 3. Research Dijkstra's Algorthim. Describe what problem this algorithm solves and list 2 situations, datasets, or real world applications that the algorithm can be used to solve. </h2>
  
   Dijkstra's Algorithm is a powerful tool for solving shortest path problems in weighted graphs with non-negative weights. Its applications in navigation systems and network routing illustrate its importance in optimizing routes and communication paths in various real-world scenarios.

   Navigation Systems:<br>

Situation: GPS navigation systems for driving directions.<br>
Dataset: Road networks where intersections are nodes, and roads are edges with distances or travel times as weights.<br>
Application: Dijkstra's Algorithm can find the shortest route from a starting location to a destination, helping users find the quickest or most efficient path.<br>

Network Routing:<br>

Situation: Data packet routing in computer networks or telecommunications.<br>
Dataset: Network topology where nodes represent routers or switches, and edges represent communication links with associated costs or latencies.<br>
Application: Dijkstra's Algorithm can determine the optimal path for data packets to travel from a source node to a destination node, minimizing the time or cost of data transmission.<br>

  

