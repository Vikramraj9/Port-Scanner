# Port-Scanner
The port scanner project involves developing a network utility tool capable of scanning a range of IP addresses for open ports. It utilizes socket programming in Python to establish connections to target IP addresses and specific ports. The technical workflow includes:

Input Handling: The user provides the target IP address/es and port range/s to scan.
Port Iteration: The scanner iterates over each IP address and port combination to test for open ports.
Socket Creation: For each IP address and port combination, a socket is created using Python's socket module.
Connection Attempt: The scanner attempts to establish a connection to the target IP address and port.
Response Handling: Depending on the response received, the scanner determines whether the port is open or closed.
Output Generation: The results of the port scan are generated and displayed to the user, indicating which ports are open on the target IP addresses.

To run the port scanner simply using command line *python PortScan.py*.
