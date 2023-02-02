# Lab 2

[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) 
this repo and clone it to your machine to get started!

## Team Members
- Melissa Shund
- Donya Badamchi

## Lab Question Answers

## Drive PDF
Answer for Question 1: 

   With 50% loss added, 
   
Answer for Question 2: 
   
   
   
Answer for Question 3: 
  
  
  

## tcp_server.c

1. What is argc and *argv[]?

    argc and *argv are the arguments taken by the main function, which sepcify the amount of 
    inputs/arguments and an array containing them.
    
2. What is a UNIX file descriptor and file descriptor table?



3. What is a struct? What's the structure of sockaddr_in?



4. What are the input parameters and return value of socket()

    Pv4, sequenced 2-way, connection-based, set prot
    
5. What are the input parameters of bind() and listen()?

    bind(s, a): binds socket s to addy a
    listen(s, x): listen to connections on a socket s with x space on queue
    
6. Why use while(1)? Based on the code below, what problems might 
   occur if there are multiple simultaneous connections to handle?
   
   
   
7. Research how the command fork() works. How can it be applied here 
   to better handle multiple connections?
   
    fork(): creates a new process concurent w parent
    
8. This program makes several system calls such as 'bind', and 'listen.' 
   What exactly is a system call?
        
        
        

   
     
