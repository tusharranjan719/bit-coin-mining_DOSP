# bit-coin-mining_DOSP
The aim of the project is to mine bitcoins using the distributed systems. Bitcoin mining using SHA256 hashing is a heavy computational process that consumes plenty of time but by implementing actor-model framework we can split the workload and use multiple cores for faster computation. 

Steps to Run:
•	To run the server type: dotnet fsi server.fsx {k}
    o	k – is a command line argument that takes the no. of leading zeroes
•	To run the client type: dotnet fsi client.fsx {k} {server’s IP} {port}
    o	k – is a command line argument that takes the no. of leading zeroes
    o	Server’s IP – address of host machine
    o	Port – port at which server is running
