# wk10-binray-search

Search for the first letter of a user provided string in the letters fo the alphabet.  Provide a 0-based index of the letter (ignoring case).  
For example if the first letter of a user-provided seach string is "C", the web page reports its index as 2, since "C" is the third letter of the alphabet located at index 2.  
This repo uses 2 search algorithms--linear search and binary search.  It reports on the web page the number of searches needed to find the target character or report that it was not found using each search algorithm.

# To execute this repo

1. Clone this file.
2. In file binarySeach.js, scroll to bottom of file to function: window.on.load.  In it, uncomment one call to searchForAlphabeticalIndex() with your choice of a searchString as input.
3. Save binarySearch.js and load index.html in a browser.
4. The browser will display the location of the first character of the string.  For example, calling searchForAlphabeticalIndex("Way of Kings"); displays following output on the webpage:
```
    Linear Search Iterations: 23  
    Binary Search Iterations: 3  
```
**Credit: MIT xPRO: Professional Certificate in Coding: Full Stack Development with MERN - September 2021**
