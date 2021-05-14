# Deadlock Conditions

The deadlock situation can only arise if all the following four conditions hold simultaneously:

### 1. Mutual Exclusion

There should be a resource that can only be held by one process at a time. In the diagram below, there is a single instance of Resource 1 and it is held by Process 1 only. 

![](https://www.tutorialspoint.com/assets/questions/media/12674/Mutual%20Exclusion.PNG)

### 2. Hold and wait

A process can hold multiple resources and still request more resources from other processes which are holding them. In the diagram given below, Process 2 holds Resource 2 and Resource 3 and is requesting Resource 1 which is held by Process 1. 

![](https://www.tutorialspoint.com/assets/questions/media/12674/Hold%20and%20Wait.PNG)

### 3. No preemption

A resource cannot be preempted from a process by force. A process can only release a resource voluntarily. In the diagram below, Process 2 cannot preempt Resource 1 from Process 1. It will only be released when Process 1 relinquishes it voluntarily after its execution is complete.

![](https://www.tutorialspoint.com/assets/questions/media/12674/No%20Preemption.PNG)

### 4. Circular wait

A process is waiting for the resource held by the second process, which is waiting for the resource held by the third process and so on, till the last process is waiting for a resource held by the first process. This forms a circular chain.

Here, Process 1 is allocated Resource 2 and it is requesting Resource 1. Similarly, Process 2 is allocated Resource 1 and it is requesting Resource 2. This forms a circular wait loop.

![](https://www.tutorialspoint.com/assets/questions/media/12674/Circular%20Wait.PNG)

