# Social Network Friendship Representation Using an Adjacency Matrix

## Description
This project represents a social network using a graph and an adjacency matrix. Each user is represented as a vertex, and each friendship is represented as an edge. The matrix stores `1` when two users are friends and `0` otherwise.

The program is developed in Python and allows users to display the friendship matrix, view the friends of a particular user, and check whether two users are friends.

## Objectives
- Understand graph representation using a two-dimensional array.
- Implement an adjacency matrix in Python.
- Display friendship connections between users.
- Check friendships and list the friends of a selected user.
- Analyze the time and space complexity of the representation.

## Data Structure Used
**Graph:** A graph consists of vertices and edges. In this project, vertices represent users and edges represent friendships.

**Adjacency Matrix:** A two-dimensional matrix represents connections between users. A value of `1` indicates a friendship, while `0` indicates no friendship.

## Features
- Display the friendship adjacency matrix.
- Show all friends of a selected user.
- Check whether two users are friends.
- Handle invalid usernames.
- Provide a simple menu-driven interface.

## Algorithm
1. Initialize the list of users.
2. Create an adjacency matrix representing their friendship connections.
3. Display the menu.
4. Accept the user's choice.
5. Display the matrix, list a user's friends, or check a friendship as requested.
6. Repeat until the user chooses Exit.

## Sample Input
Users: Aarav, Priya, Rohan, Neha.

Friendship connections:
- Aarav and Priya
- Aarav and Rohan
- Priya and Neha
- Rohan and Neha

## Sample Output

```text
Friends of Aarav : Priya, Rohan
```

## Complexity Analysis
Let `V` represent the number of users.

- **Space Complexity:** O(V²), because the adjacency matrix contains V × V entries.
- **Check Friendship:** O(1), because the matrix entry can be accessed directly.
- **Display Matrix:** O(V²), because every matrix entry is displayed.
- **Show Friends:** O(V), because the selected user's row is scanned.

## Applications
- Representing friendship connections in social networks.
- Modeling communication networks.
- Representing relationships between users.
- Analyzing connections in small, dense graphs.

## Advantages
- Simple and easy-to-understand representation.
- Fast checking of direct connections.
- Suitable for dense graphs.
- Easy to implement using Python lists.

## Limitations
- Requires O(V²) memory.
- Less suitable for very large, sparse social networks.
- The current program uses a predefined set of users and friendships.

## Future Scope
- Add new users and friendship connections dynamically.
- Allow users to remove friendships.
- Store network information in a file or database.
- Extend the system to suggest mutual friends.
- Develop a graphical interface.

## Conclusion
This project demonstrates how an adjacency matrix can represent friendship connections in a social network. It provides basic operations for displaying connections, listing friends, and checking friendships. The implementation helps explain graph representation, two-dimensional arrays, and algorithm complexity.

## References
1. Python Documentation: https://docs.python.org/3/
2. GeeksforGeeks – Graph Data Structure: https://www.geeksforgeeks.org/graph-data-structure-and-algorithms/
3. Programiz – Graph Data Structure: https://www.programiz.com/dsa/graph
