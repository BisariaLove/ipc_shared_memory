# ipc_shared_memory
Inter Process Communication using shared Memory(Language - C)

# Server
gcc -o cli shm-client.c -lpthread

# Client
gcc -o ser shm-server.c -lpthread

# Steps to Run
- First run the server.  ./ser 
- Then run the client.  ./cli 

# Expected Output
Server writes to shared memory, client reads the data from shared memory.
