# PAGE-REPLACEMENT-ALGORITHMS

### AIM: To implement FIFO page replacement technique.
   a) FIFO b) LRU c) OPTIMAL
### DESCRIPTION:
Page replacement algorithms are an important part of virtual memory management and it helps the 
OS to decide which memory page can be moved out making space for the currently needed page. 
However, the ultimate objective of all page replacement algorithms is to reduce the number of 
page faults.

## FIFO

This is the simplest page replacement algorithm. In this algorithm, the operating system 
keeps track of all pages in the memory in a queue, the oldest page is in the front of the queue. 
When a page needs to be replaced page in the front of the queue is selected for removal.
LRU-In this algorithm page will be replaced which is least recently used
OPTIMAL- In this algorithm, pages are replaced which would not be used for the longest duration 
of time in the future. This algorithm will give us less page fault when compared to other page 
replacement algorithms.

### ALGORITHM:
1. Start the process
2. Read number of pages n
3. Read number of pages no
4. Read page numbers into an array a[i]
5. Initialize avail[i]=0 .to check page hit
6. Replace the page with circular queue, while re-placing check page 
availability in the frame Place avail[i]=1 if page is placed in theframe Count page
faults
7. Print the results.
8. Stop the process.
    A) FIRST IN FIRST OUT

## LEAST RECENTLY USED

 ### AIM:
 To implement LRU page replacement technique.

### ALGORITHM:
1. Start the process
2. Declare the size
3. Get the number of pages to be inserted
4. Get the value
5. Declare counter and stack
6. Select the least recently used page by counter value
7. Stack them according the selection.
8. Display the values
9. Stop the process
