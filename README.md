# Algorithm Analysis Homeworks

## What Does It Include

* findMaxArray

This code is finding the maximum subarray in an array using both brute force and divide and conquer methods. The brute force method goes through every possible subarray in the given array and checks the sum of each subarray, storing the maximum sum and the corresponding subarray indices in an array called `lmom`. The divide and conquer method uses recursion to divide the array into smaller subarrays, and finds the maximum subarray sum by comparing the maximum subarray sum in the left half, right half, and the maximum subarray sum that crosses the middle of the array. The function `buyukSayiIndis` compares the values of two integers and returns the larger one. The function `minimum` finds the minimum value in an array. The function `maximum_sum` finds the maximum subarray sum using the divide and conquer method and stores the maximum sum and corresponding subarray indices in the `lmom` array. The main function initializes an array, calls the `findMaxValueBruteForce` and `maximum_sum` functions, and prints the results using the `printData` function.

* hashing

This is C code which seems to be implementing a hash table data structure. The code appears to read in data from a file `Sample.txt`, store it in a linked list, and then use the elements of the linked list to populate a hash table. The hash table uses chaining to handle collisions. The code also includes a function to print the contents of the linked list and a function to find an element in the hash table using its key. It is not clear what the purpose or functionality of the code is without more context.

* graphApplication

This code is an implementation of a social network. It reads data from a file called `socialNET.txt`, which contains the names and surnames of people and the IDs of people they follow. The code creates an array of people and a linked list of IDs for each person representing the IDs of the people they follow. It also includes functions to add and remove people from the queue, creating a new person, printing a person's information, and reading data from the file.

The main function reads the data from the file, creates an array of people, and a linked list of IDs for each person. Then it calculates the indegree of each person in the network, which is the number of people following a person, and uses this information to find the people with the most followers. Finally, it prints the names of the people with the highest indegree.

* backTracking

This code is an implementation of a backtracking algorithm for solving a color puzzle. The puzzle consists of a square board where each cell can be colored with one of the given number of colors. The goal is to color the board in such a way that no two adjacent cells have the same color. The code allows the user to input the size of the board and the colors for each cell, and then uses backtracking to find a solution for the puzzle or determine that no solution exists.

The main function allows the user to choose between two modes: a detailed mode that shows the steps of the backtracking algorithm and a normal mode that only displays the final solution. The function `sifirDizisi` allocates memory for an array of integers and initializes all elements to 0. The function `menu` prompts the user to input the size of the board and the colors for each cell, and stores them in a 2D array called `masa`. The function `renkleriYazdir` prints the current state of the board. The function `cozumVarMi` uses backtracking to find a solution for the puzzle or determine that no solution exists. The function `validMi` checks if a given color can be assigned to a cell based on the current state of the board.

## How It Works
You can use with numerical commands in terminal. 

## How Can I Run

### Prerequisites

* Use `C99` standart 
* Download `GCC`  or `MingW32` Compiler 

```
git clone https://github.com/kaayra2000/algorithm-analysis-homeworks/
cd algorithm-analysis-homeworks
gcc xxxx.c -o main.exe
main.exe
```
