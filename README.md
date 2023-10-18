# CS-300

    //// What was the problem you were solving in the projects for this course?
The focus of this course involved focusing on how different algorithms behaved. A particular focus was on several different data structures and how one might implement them in a project. In the first project we were asked to design vector, hash table, and binary search tree data structures and evaluate the efficiency of each whenever it came to inserting, searching, performing a full traversal, and alphabetically outputting the data.
In our second project, we were asked to choose one of the data structures and implement them in C++ for a hypothetical client. This client was a university who was seeking to store basic information about their various courses.
    //// How did you approach the problem? Consider why data structures are important to understand.
My rational is that certain kinds of actions would be performed more often than others and that one ought to implement a solution which optimizes for the more frequent actions. In the scenario, our client would insert or remove courses very infrequently, but search queries and alphabetical outputs might be very frequent if this system interfaces with a website which students search through. I chose to implement two data structures at once: The hash table would (usually) perform searches with O(1) runtime, and an alphabetized vector would enable a speedy O(n) alphabetical output. This alphabetization occurs whenever a new course is added, which I assume would be around three times per year.
    //// How did you overcome any roadblocks you encountered while going through the activities or project?
While writing the project, I decided to be clever and store course objects in a vector and create pointers to those elements. Once the course list vector went out of scope, those objects would be deleted and memory leaks would be avoided without explicitly implementing a removal process for course objects
One of the lessons I learned was that if you have pointers to elements in a vector, those pointers become dereferenced whenever you add elements to that vector; presumably because whenever a vector is resized it needs to find a new spot in memory. 
I should not attempt fancy things.
    //// How has your work on this project expanded your approach to designing software and developing programs?
I am more comfortable with recursive algorithms and slightly more cognizant of efficiency concepts.

    //// How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?
Largely, it didn’t; this was not the focus of the course or the project.
