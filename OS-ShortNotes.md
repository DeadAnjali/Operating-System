# Operating-System
Educational Notes of Operating system
- Processes and threads
- User level thread vs kernel level thread(threads using system calls)
  Both share the code and data section

### Process Synchronization
processes are of two types 
- cooperative processes- share something like variable memory code or resources
- independent processes
- Context Switching
- ![image](https://github.com/DeadAnjali/Operating-System/assets/122856861/d85dee5e-8f21-4f00-8385-4d9058002749)
### Semaphore
- it is a integer value and can be either `Counting (-infinty to + infinity)` or `Binary(0 or 1)`
- It is entry code called donwn/p()/wait
- It is exit code called up/v()/signal
- ![image](https://github.com/DeadAnjali/Operating-System/assets/122856861/a6e38a7d-2ab7-499a-ac19-d125ed3fe10d)

