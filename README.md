# P2P-Application
I created a P2P (Peer-to-Peer) application that consisted of a singular index server and a number of peers. In this application, peers can exchange content among themselves through the support of the index server. The index server will communicate using UDP connections with the peer networks, and the peer networks will communicate amongst each other using TCP connections. The index server's purpose is to act as a menu to the user and point the peers towards the corresponding TCP functions. The index server is able to list available content, register content from the peer to the server to be accessible for download, and be able to de-register content. This project was completed using socket programming and coded in C. 
