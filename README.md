# Project 3 – Pastry

## Team members
Kanika Sharma | UFID : 7119-1343 <br />
Divyatha Satheeshan Edachana | UFID : 0710-8354

## Instructions to run the program :
1. Unzip project3.zip
2. Ensure project3.fsx is included in the compile in .fsproj file
3. Through the command line, run the program using the command :
dotnet fsi --langversion:preview project3.fsx numNodes numRequests
(providing different values for numNodes and numRequests)

## Working Part :

<ul>
<li>The protocol is implemented as per the Pastry paper. Pastry APIs described are called within the program.</li>
<li>The program runs correctly as per requirements</li>
<li>As per the parameter 'numNodes' passed, nodes get added to the network. Each second it starts to request based on the value passed for 'numRequests' for each of the nodes. Each of these requests are routed correctly to the node which has its id numerically closest to the given key requested.</li>
<li>The program terminates exactly when all the nodes have made the given number of requests.</li>  
<li>As per the requirements, the average number of hops or node connections is calculated and printed on to the console.</li>
<li>All the requirements for the project are met and have successfully implemented the protocol.</li>
</ul>

## Largest network managed to deal with :

Largest network that could be managed consisted of 10000 peers and each peer was able to make 100 requests for which we obtained average number of hops as 3.37ms. 
