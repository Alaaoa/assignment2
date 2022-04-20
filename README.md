# assignment2 : 

Starting with assignment 1 as a starting point, add in code to re-exec the server’s child process after forking. You will need to determine how to pass the socket file descriptor between the forked child and the new exec’ed child, so that the new exec’ed child can process the incoming child request.
          
          Work with Team : Alaa AbuShqeir ( 015528305 ) and Name: Venkata Siva Prasad Kakkera ( 015935101 ) 


          gcc -o server server.c && sudo ./server
          gcc -o client client.c && ./client
          Both run on port 8080
