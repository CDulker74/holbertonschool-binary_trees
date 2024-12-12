Sorting Algorithms Project
Background Context
This project focuses on implementing various sorting algorithms and understanding their time complexities. It is designed to be completed in pairs, emphasizing the importance of pair programming for the mandatory tasks.
Learning Objectives
Upon completion of this project, you should be able to:
Implement at least four different sorting algorithms
Understand Big O notation and evaluate algorithm time complexity
Select the most appropriate sorting algorithm for a given input
Identify stable sorting algorithms
Requirements
Allowed editors: vi, vim, emacs
Compilation: Ubuntu 20.04 LTS, gcc with options -Wall -Werror -Wextra -pedantic -std=gnu89
Coding style: Betty style (checked using betty-style.pl and betty-doc.pl)
File structure:
All files should end with a newline
Maximum 5 functions per file
Header file: sort.h (include guarded)
Restrictions:
No global variables
Standard library functions (e.g., printf, puts) are forbidden unless specified
Arrays/lists with less than 2 elements do not need sorting
Data Structures
Doubly Linked List
c
typedef struct listint_s
{
    const int n;
    struct listint_s *prev;
    struct listint_s *next;
} listint_t;
Provided Functions
Two print functions are provided:
print_array: Prints an array of integers
print_list: Prints a list of integers
Include their prototypes in your sort.h header file.
Big O Notation
For complexity analysis, use the short notation without constants:
O(1)
O(n)
O(n!)
O(n^2) for n square
O(log(n)) for log(n)
O(nlog(n)) for n * log(n)
O(n+k) for n + k
Testing
For testing with large sets of random integers, consider using Random.org.
GitHub Repository
Ensure one project repository per group. Cloning or forking a project with the same name before the second deadline may result in a 0% score.
