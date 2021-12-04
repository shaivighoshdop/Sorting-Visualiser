# Sorting-Visualiser

The objective of this project is to create a web application using HTML, CSS and rudimentary Javascript to visualize how various sorting
algorithms work.

Project Context :
We have learnt sorting algorithms like bubble sort, selection sort, insertion sort, quick sort.
But often we fail to understand the core idea of a particular algorithm maybe because we
are unable to visualize how they work. So the most important thing to understand about
these algorithms is visualization.
That’s this project was made to let everyone understand how these algorithms
work and through this project we will also get a deep understanding of such sorting
algorithms.

High-Level Approach
• Creating the website's User Interface (UI) using HTML, CSS and enhancing it further
using Bootstrap.
• Implementation of animations, effects and core functionalities (sorting algorithms)
using JavaScript.
• Publish to GitHub and host the project live using Netlify.


Requirements
• This is a typical JavaScript Project , so I have used the code editor VScode.
 with necessary plugins.
 
 Task 1:
 Creating the website's UI : In this milestone the basic structure of this website will be made. In this milestone you will
mainly use HTML. Then in the next milestone we will add Bootstrap and CSS for styling
purposes.

Task 2:
Improving UI using CSS and Bootstrap
The web app's basic skeleton UI was created in the previous task. To make the app more
attractive and interactive we will employ CSS and Bootstrap for styling purposes.

Task 3:
Creating Bars Using JavaScript
From this milestone onwards we will start implementing the animations and other core
functionalities of the application. In this milestone, we will create bars of different heights;
which basically indicates the array that we will sort. Through these bars, we will visualize
how sorting algorithms work.

Task 4:
Implementing Bubble Sort Algorithm:
Requirements
• The most important thing to do in every sorting algorithm is to swap elements. To
make swap two elements in HTML using JS we do the following:![WhatsApp Image 2021-12-04 at 9 49 25 AM](https://user-images.githubusercontent.com/54748726/144696691-b7cc1820-8bac-453a-9b12-48f238dff4ea.jpeg)

- Now apply the simple bubble sort algorithm.
- At the end of every iteration when the highest bar will be taken to the right corner then
to show that this bar is placed at its perfect position we make the background color Green.
- Now when we run this we will notice that there is no delay in swapping and the other
iterations. So we have to add a delay before the swaps in order to watch how changes
are happening. For delay we may use the following logic -
![WhatsApp Image 2021-12-04 at 9 59 14 AM](https://user-images.githubusercontent.com/54748726/144696933-4e14b075-95a4-42cd-8bb3-3c86312d54c6.jpeg)
- Then we wrap this whole thing in a function and pass this into the event listener of the bubble
sort button.

Task 5:
We implement the remaining sorting Algorithms : Merge Sort, Quick Sort, Selection Sort and Insertion Sort

Task 6:
We change the number of bars and speed.

Task 7:
Host the project live using Netlify.
