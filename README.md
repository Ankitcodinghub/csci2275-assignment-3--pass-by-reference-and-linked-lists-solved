# csci2275-assignment-3--pass-by-reference-and-linked-lists-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2275 Assignment 3- Pass by Reference and Linked Lists Solved](https://www.ankitcodinghub.com/product/csci2275-csci-2270-ae-data-structures-assignment-3-pass-by-reference-and-linked-lists-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119704&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2275 Assignment 3- Pass by Reference and Linked Lists Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Objectives

1. Creating a geometric progression series.

2. Create, traverse, add nodes to a linked list

3. Get practice implementing classes

Instructions

Write code to complete Parts 1 and 2. Implement the solution for each part as a separate program. To receive credit for your code, you will need to pass the necessary test cases. Use the following steps to test your code as you work on the assignment:

1. Open up your Linux terminal, navigate to the build directory of this assignment (e.g. cd build).

2. Run the cmake .. command.

3. Run the make command.

4. If there are no compilation errors, three executables will be generated within the build directory: run_app_1, run_app_2, and run_tests.

5. If you would like to run your program including your app implementation in the main function, execute run_app_2 from the terminal by typing ./run_app_2.

6. To run the grading tests, execute run_tests from the terminal by typing ./run_tests.

NOTE: Make sure to run your program ./run_app_2 WITHOUT command line arguments.

Part 1 – Creating a geometric progression series: Append to an array

Overview: A sequence of numbers is called a Geometric progression if the ratio of any two consecutive terms is always the same. In simple terms, it means that the next number in the series is calculated by multiplying a fixed number to the previous number. For example, 2, 4, 8, 16 is a GP because ratio of any two consecutive terms in the series (common difference) is same (4 / 2 = 8 / 4 = 16 / 8 = 2).

For this exercise you are requried to generate a geometric series by appending to an array. A reference-to-array parameter is to be passed to your function generateSeries, so that you can modify the pointer to the array itself.

NOTE: You do not need to implement the main function. It can however be used to test your code out. The main_1.cpp is not being graded for this assignment.

Use the function prototype provided below: void generateSeries(int* &amp;arr, int &amp;n, int &amp;m, int &amp;arraySize);

INPUT PARAMETERS:

arr is an empty array of type int in which you insert elements. A reference to this array pointer is passed to your function.

n is starting element of the series array.

m is the ratio between a number and its previous number. arraySize variable stores the size of your array.

EXAMPLE: n = 3, m = 4, arraySize = 4 arr = [3, 12, 48, 192]

Here the starting element is n and arr[i]/arr[i – 1] = m. Total size of the array is arraySize.

Part 2 – Linked Lists: Communication Between Satellites

Building your own communications network

Implement a class to simulate a linear communication network between CU launched satellites. You will have to complete the TODOs in both the class implementation in CUSatelliteNetwork.cpp and the driver file main_2.cpp. Do not modify the header file!

NOTE: When experimenting with your program, make sure to run your program ./run_app_2 WITHOUT command line arguments. Also, do not modify the code in main_2.cpp where the comments indicate // DO NOT MODIFY THIS .

The linked list itself will be implemented using the following node struct:

struct CUSatellite{ string name; // name of the satellite string message; // message this satellite has received int numberMessages; // no. of messages passed through this satellite CUSatellite *next; // pointer to the next satellite int distanceFromEarth; // distance of satellite from earth in light years };

Class Specifications

The CUSatelliteNetwork class definition is provided in the file CUSatelliteNetwork.hpp. Do not modify this file! Fill in the file CUSatelliteNetwork.cpp according to the following specifications.

CUSatellite* head; + Points to the first node in the linked list

CUSatelliteNetwork() + Class constructor; sets the head pointer to NULL + This is given in the starter code. Do not modify it.

void printNetwork(); + This function is given in the starter code. Do not modify it. + Print the names of each node in the linked list. Below is an example of correct output using the default setup. (Note that you will cout &lt;&lt; â€œNULLâ€ at the end of the path)

== CURRENT PATH == TESS(2) -&gt; KEPLER(10) -&gt; GALILEO(6) -&gt; PIONEER(5) -&gt; JUNO(4) -&gt; MAVEN(9) -&gt; NULL ===

If the network is empty then print “nothing in path”

TO DO: Complete the definitions for the following member functions in CUSatelliteNetwork.cpp. Make sure you complete the functions in the order they are given here.

1. void addSatelliteInfo(string previous, string satelliteName, int distance)

2. Insert a new satellite with name satelliteName in the linked list after the satellite with the name previous.

3. If previous is an empty string (“”), then add the new satellite to the beginning of the list.

4. If previous does not exist in the list, display a message and do nothing.

5. Print the name of the satellite you added according to the following format:

“` // If you are adding at the beginning use this: cout &lt;&lt; “adding: ” &lt;&lt; satelliteName &lt;&lt; ” (HEAD)” &lt;&lt; endl;

// Otherwise use this: cout &lt;&lt; “adding: ” &lt;&lt; satelliteName &lt;&lt; ” (prev: ” &lt;&lt; previous-&gt;name &lt;&lt; “)” &lt;&lt; endl;

// If the previous node cannot be found, display this message: cout &lt;&lt; “Cannot add new node; previous node not found ” &lt;&lt; endl; “`

1. void loadDefaultSetup()

2. Add the following six satellites to the network using addSatelliteInfo. Do so by adding each node at the head of the Linked List (i.e.

start with “MAVEN”, then add “JUNO” as the new head, and so on).

“TESS” -&gt; “KEPLER” -&gt; “GALILEO” -&gt; “PIONEER” -&gt; “JUNO” -&gt; “MAVEN”

Add the following distances corresponding to the satellites added above, in order, to the network with addSatelliteInfo:

“2”, “10”, “6”, “5”, “4”, “9”

1. CUSatellite* searchForSatellite(string satelliteName)

2. Return a pointer to the node with name satelliteName. If satelliteName cannot be found, return nullptr

3. void transmitInfo(string receiver)

4. Traverse the linked list from the head to the node with name receiver. For each node in this path (including the head), set the nodeâ€™s message to “distance of “+ satelliteName + ” from earth is ” + distanceFromEarth and increment the nodeâ€™s numberMessages field. If the list is empty, print “Empty list” and exit the function. If the node is not present, print â€œSatellite not foundâ€.

5. As you traverse the list, at each node report the message received and the number of messages received using the following cout: (See the end of this document for example output)

cout &lt;&lt; node-&gt;name &lt;&lt; ” [# messages received: ” &lt;&lt; node-&gt;numberMessages &lt;&lt; “] received: ” &lt;&lt; node-&gt;message &lt;&lt; endl;

1. int main(int argc, char* argv[])

2. Your program will start by displaying a menu by calling the displayMenu function included in main_2.cpp. The user will select an option from the menu to decide what the program will do, after which, the menu will be displayed again. The specifics of each menu option are described below.

Option 1: Build Network

This option calls the loadDefaultSetup function, then calls the printNetwork function. You should get the following output:

“`

&gt; 1

adding: MAVEN (HEAD) adding: JUNO (HEAD) adding: PIONEER (HEAD) adding: GALILEO (HEAD) adding: KEPLER (HEAD) adding: TESS (HEAD) == CURRENT PATH == TESS(2) -&gt; KEPLER(10) -&gt; GALILEO(6) -&gt; PIONEER(5) -&gt; JUNO(4) -&gt; MAVEN(9) -&gt; NULL

=== “`

Option 2: Print Network Path

Calls the printNetwork function. Output should be in the format below: “` // Output for the default setup

&gt; 2

== CURRENT PATH == TESS(2) -&gt; KEPLER(10) -&gt; GALILEO(6) -&gt; PIONEER(5) -&gt; JUNO(4) -&gt; MAVEN(9) -&gt; NULL ===

// Output when the linked list is empty == CURRENT PATH == nothing in path === “`

Option 3: Broadcast Info

Prompt the user to enter the name of a satellite to receive the broadcast. Pass the satellite name to the transmitInfo function. Donâ€™t forget to add a newline before the output is printed. This is done for better readability.

For example, the following should be the output if the linked list contains the default setup from option (1) and the broadcast is sent to

“GALILEO”:

“` Example 1: Enter name of the recipient to receive the message: GALILEO

TESS [# messages received: 1] received: distance of TESS from earth is 2 KEPLER [# messages received: 1] received: distance of KEPLER from earth is 10 GALILEO [# messages received: 1] received: distance of GALILEO from earth is 6 “`

If the user then decides to broadcast the message to “JUNO”, the output will be:

“` Example 2: Enter name of the recipient to receive the message:

JUNO

TESS [# messages received: 2] received: distance of TESS from earth is 2 KEPLER [# messages received: 2] received: distance of KEPLER from earth is 10 GALILEO [# messages received: 2] received: distance of GALILEO from earth is 6 PIONEER [# messages received: 1] received: distance of PIONEER from earth is 5 JUNO [# messages received: 1] received: distance of JUNO from earth is 4 “`

If the user then decides to broadcast the message to â€œMARSâ€, the output when the satellite is not present will be:

“` Example 3: Enter name of the recipient to receive the message: MARS

Satellite not found “`

Option 4: Add Satellite

Prompt the user for three inputs: the name of a new satellite to add to the network, newSatellite, distance of satellite from the earth, distanceFromEarth, and the name of a satellite already in the network, previous, which will precede the new satellite. Use the member functions searchForSatellite and addSatelliteInfo to insert newSatellite info into the linked list right after previous.

If the user wants to add the new satellite to the head of the network then they should enter â€œFirstâ€ instead of a previous satellite name. If the user enters an invalid previous satellite (not present in the linked list), then you need to prompt the user with the following error message and collect input again until they enter a valid previous satellite name or â€œFirstâ€:

cout &lt;&lt; “INVALID(previous satellite name)…Please enter a VALID satellite name!” &lt;&lt; endl;

Once a valid previous satellite name is passed and the new satellite is added, call the function printNetwork to demonstrate the new linked-list.

All letters of the recipient to be added should be Uppercase (sentence case) e.g. If you want to add â€œsputnik, it should be stored as â€œSPUTNIKâ€ in linked list.

For example, the following should be the output if the linked list contains the default setup from option (1) and the user wants to add SPUTNIK after GALILEO:

Enter a new satellite name: SPUTNIK Enter distance of satellite from earth: 13 Enter the previous satellite name (or First): GALILEO adding: SPUTNIK (GALILEO) == CURRENT PATH == TESS(2) -&gt; KEPLER(10) -&gt; GALILEO(6) -&gt; SPUTNIK(13) -&gt; PIONEER(5) -&gt; JUNO(4) -&gt; MAVEN(9) -&gt; NULL===

Option 5: Quit

Print the following message:

cout &lt;&lt; “Quitting…” &lt;&lt; endl;

Finally, print the following before exiting the program:

cout &lt;&lt; “Goodbye!” &lt;&lt; endl; Example run for Part 2

“` Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast Info 4. Add Satellite 5.

Quit +———————–+

&gt; 2

== CURRENT PATH == nothing in path === Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast Info 4. Add Satellite 5. Quit +———————–+

&gt; 3

Enter name of the recipient to receive the message: SPUTNIK

Empty list Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast Info 4. Add

Satellite 5. Quit +———————–+

&gt; 1

adding: MAVEN (HEAD) adding: JUNO (HEAD) adding: PIONEER (HEAD) adding: GALILEO (HEAD) adding: KEPLER (HEAD) adding: TESS (HEAD) == CURRENT PATH == TESS(2) -&gt; KEPLER(10) -&gt; GALILEO(6) -&gt; PIONEER(5) -&gt; JUNO(4) -&gt; MAVEN(9) -&gt; NULL === Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast Info 4. Add Satellite 5.

Quit +———————–+

&gt; 4

Enter a new satellite name: SPUTNIK Enter distance of satellite from earth: 10 Enter the previous satellite name (or First): First adding: SPUTNIK

(HEAD) == CURRENT PATH == SPUTNIK(10) -&gt; TESS(2) -&gt; KEPLER(10) -&gt; GALILEO(6) -&gt; PIONEER(5) -&gt; JUNO(4) -&gt;

MAVEN(9) -&gt; NULL === Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast

Info 4. Add Satellite 5. Quit +———————–+

&gt; 3

Enter name of the recipient to receive the message: MAVEN

SPUTNIK [# messages received: 1] received: distance of SPUTNIK from earth is 10 TESS [# messages received: 1] received: distance of TESS from earth is 2 KEPLER [# messages received: 1] received: distance of KEPLER from earth is 10 GALILEO [# messages received: 1] received: distance of GALILEO from earth is 6 PIONEER [# messages received: 1] received: distance of PIONEER from earth is 5 JUNO [# messages received: 1] received: distance of JUNO from earth is 4 MAVEN [# messages received: 1] received: distance of MAVEN from earth is 9 Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast Info 4. Add Satellite 5. Quit +———————-+

&gt; 3

Enter name of the recipient to receive the message: TESS

SPUTNIK [# messages received: 2] received: distance of SPUTNIK from earth is 10 TESS [# messages received: 2] received: distance of TESS from earth is 2 Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast Info 4. Add

Satellite 5. Quit +———————–+

&gt; 3

Enter name of the recipient to receive the message: JUNO

SPUTNIK [# messages received: 3] received: distance of SPUTNIK from earth is 10 TESS [# messages received: 3] received: distance of TESS from earth is 2 KEPLER [# messages received: 2] received: distance of KEPLER from earth is 10 GALILEO [# messages received: 2] received: distance of GALILEO from earth is 6 PIONEER [# messages received: 2] received: distance of PIONEER from earth is 5 JUNO [# messages received: 2] received: distance of JUNO from earth is 4 Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast Info 4. Add Satellite 5. Quit +———————–+

&gt; 4

Enter a new satellite name: AERO2 Enter distance of satellite from earth: 40 Enter the previous satellite name (or First): JUNO adding: AERO2

(prev: JUNO) == CURRENT PATH == SPUTNIK(10) -&gt; TESS(2) -&gt; KEPLER(10) -&gt; GALILEO(6) -&gt; PIONEER(5) -&gt; JUNO(4) -&gt;

AERO2(40) -&gt; MAVEN(9) -&gt; NULL === Select a numerical option: +=====Main Menu=========+ 1. Build Network 2. Print Network Path 3. Broadcast Info 4. Add Satellite 5. Quit +———————–+

&gt; 5

Quitting… Goodbye! “`

Submitting your code:

Write your code and push the changes to your private repository. Log onto Canvas and go to Assignment 3. Paste your GitHub repository link and submit.
