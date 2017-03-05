[![Build Status](https://travis-ci.org/ashish-chopra/Structures.svg)](https://travis-ci.org/ashish-chopra/Structures)

What are we working on?
---------------------
1. Adding elementary sorts and some applications of LinkedList, Trees.
2. Implementing Graph Algorithms
3. Testing Data Structures with huge data.

Welcome to Structures!
------------------------
Structures is a nice compilation of abstract data structures that we could think of! Since its inception, it is growing slowly into a huge collection of ADT journal. We have written the intuition behind developing each structure in its code as introductory comment block with algorithmic analysis and its merits and de-merits.

The de-merits of one ADT leads to the motivation of creating another ADT, so you will find it like a chain story to browse :P

How to use it?
-----------------------
Well, the  repostiory is like a journal. You can browse inside `src` folder and will see the code arranged in intuitive package structure. And, each code file consists of good amount of writeup at the top to motivate the reader about the intuition behind the class design. But, sometimes a table of contents become handy, so checkout the [wiki](https://github.com/ashish-chopra/Structures/wiki) to get a formal introduction to the repo.

PS: You may find that we are not strictly following the JAVA coding conventions (for instance, not using camelcase for variable names everywhere, using u, v, w somewhere etc). This is because, our focus is not on JAVA, but on algorithms, and we want to preserve mathematical expressions for known things, so that it remains connected to Robert Sedgewick book's literature.


How to download?
---------------------------
'Structures' is a maven project. You must have any latest version of Git, Maven installed in your machine and follow the steps mentioned below:

   Clone the repo using command and generate eclipse project files:

    >$ git clone https://github.com/ashish-chopra/Structures.git
    >$ cd Structures                 // browse inside Structures       
    >$ mvn eclipse:eclipse           // it generates the eclipse specific files, so that 
                                     // you can import this project into eclipse

Then, Import the project into Eclipse by File > Import > Existing Maven Project into Workspace.

I have also tried [Visual Studio Code](https://code.visualstudio.com/) as well. Make sure you installed the [Java Langauge Support extension from RedHat](https://marketplace.visualstudio.com/items?itemName=redhat.java) for VS code and then follow following commands to get started:

    >$ git clone https://github.com/ashish-chopra/Structures.git
    >$ cd Structures       # browse inside Structures      
    >$ code .              # open up VS code editor at this location
   
Inside editor,  open the command window using `Ctrl+Shift+p`, type `configure build task`, select `maven`; it will create `.vscode` folder inside your project structure. Then, use command `Ctrl+Shift+b` to run the project maven build. I will add the support for other commands soon. If you can, then send me a pull request.

Other commands:

    >$ mvn compile     		// this will only compile your source code
    >$ mvn test        		// this will run the test suite
    >$ mvn javadoc:javadoc  // generates the java doc of all the ADTs
    							   // at "Structures/target/site/apidocs/"

   You can run these commands from command line inside your `Structures` directory. 
   Or using Eclipse by right click `Structures > Run As > Maven Build ...`


I found a bug/new feature!
---------------------------
Structures' bugs are tracked using [Github Issue tracker system](https://github.com/ashish-chopra/Structures/issues).

Please use issue tracker for following purpose:
 1. to raise a bug request; do include specific details and label it appropriately.
 2. to suggest any improvements in existing features.
 3. to suggest new features or structures or applications.

I want to contribute!
-------------------------
Awesome! Please fork the repository and make a new branch & start developing a new feature or fix a bug. 
Then send a pull request. I will review the submissions and add it into the main repo.
<!--
Active contributors in the repo - 
 1. [Ashish Chopra - @ashish-chopra](http://github.com/ashish-chopra)-->

And also thanks to many contributors for their submissions. I will keep adding them here.
 1. Shivam Goel
 2. Havan Aggarwal
 3. Gansai
 4. Tarun Jain
 5. Miguel Stephane
 

License
----------------
The code is licensed under MIT License. 
Let's have fun coding together!
