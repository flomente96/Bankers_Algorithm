# Bankers_Algorithm

**How to run the program:**
Just click the Lomente_Bankers.exe file. IF THE EXECUTABLE FILE WON'T WORK PLEASE USE THE JAR FILE AND FOLLOW THE INSTRUCTION BELOW:
            To run the file, MUST use the TERMINAL and run the .jar file:  
            Run this command inside the Bankers_Algorithm/dist directory  
                        "java -jar Bankers_Algorithm.jar" 

This do not have a **.exe file** because the **.jar file** that was compiled and build in my **Linux machine** won't run properly in **Windows**. The **.jar file** will only run in windows using its command prompt.  


**During program execution**
THE INPUTS:
      allocation = holds the allocation values of each RESOURCES to each PROCESSES
      masAlloaction = holds the maximum allocation of each RESOURCES to each PROCESSES
      available = array of holds the total available RESOURCES (unused resources)
      
1. It will ask the user to choose between:  
  1. DEADLOCK PREVENTION  
  2. DEADLOCK AVOIDANCE  
2. Then, it will ask for the required inputs of the choice made.  
   For DEADLOCK PREVENTION:  
     + The number of processes (NOTE: THE Name of the processes are the input NUMBER ORDER e.g. first process input will take the name of Process 1, second process input will take the name Process 2 and so on.)  
     + The value of the available resources  
     + The time for each process  
   For DEADLOCK AVOIDANCE:  
     + The number of processes and resources  
     + The available resiurces  
     + The process details for each process: allocation and maximum demand  
     + The new request details: process ID and request for resources  
     
LIMITATIONS:
     + allows negative values to occur in the matrices and "available" array
     + does not check for proper inputs
