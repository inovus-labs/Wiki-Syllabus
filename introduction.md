# Introduction

Deadlock is a situation where a set of processes is blocked because each process is holding a resource and waiting for another resource, that is acquired by some other process at the current instance. To be precise, it's the situation that occurs in an OS when any process enters a waiting state because another waiting process is holding the demanded resource. Deadlock is a common problem in multi-processing where several processes share a specific type of mutually exclusive resource known as software.

![](https://www.tutorialspoint.com/assets/questions/media/12674/Deadlock%20in%20Operating%20System.PNG)

Here, Process 1 has Resource 1 and needs to acquire Resource 2. Similarly, Process 2 has Resource 2 and needs to acquire Resource 1. Process 1 and Process 2 are in deadlock as each of them needs the other’s resources to complete their execution but neither of them is willing to relinquish their resources.

