Roll no : BT20CSE083

Name : Vaibhav Mokale

==========================================================

To run the code :

FOr windows: type in terminal :

pyhton DVR.py

For Ubuntu :

python3 DVR.py

==========================================================

The file takes input from inp.txt, also i gave one text file "Inputs for testing.txt" in which I added various test cases.

So you can copy from there and can paste in inp.txt file.


===========================================================


Short info about code ;


1.The code implements the Distance Vector Routing (DVR) protocol, which is a distributed routing algorithm used in computer networks to determine the shortest path for data transmission.

2.The algorithm is executed in each node or router of the network and works by calculating the distance to all other nodes based on the shortest path, where each node maintains a routing table that lists the distance to all other nodes in the network.

=============================================================

The program uses the following functions:

    1. update_queue: updates the queue of each router with the updated DVR table of its neighbours after every 2 seconds.

    2. bellman_ford: updates the DVR table of the router by executing the Bellman-Ford algorithm.

    3. task: thread function which updates the DVR table of the router, prints the updated table and waits until all other routers have also updated their tables.

    4. print_init: prints the initial DVR table for each router.

    5. main: reads the input file, initializes the router dictionary, creates threads for each router and executes the Bellman-Ford algorithm to calculate the shortest path to all other nodes.








