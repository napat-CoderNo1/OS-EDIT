## Introduction

### Roles of the Operating Systems
- **Referee**
  - Resource allocation among users, applications
  - Isolation of different users, applications from each other
  - Communication between users, application
- **Illusionist**
  - Each application appear to have the entire machine to itself
  - Infinite number of processors, (near) infinite amount of memory, reliable storage, reliable network transport
- **Glue**
  - Libraries, User Interface, widgets, ...

### What is an Operating Systems ?
- A set of software that manage computer's resources for its users and their application
  - Maybe visible or invisible to its users
  - 2 major kinds
    - General purpose OS
    - Specific purpose OS

### Operating System Evaluation
- **Reliability and Availability**
- **Security** -> consider just inside the os eg. the priviledge user authentication
- **Portability**
  - AVM (Abstract Virtual Machine), API, HAL
- **Performance** : measure in the control environment
  - Overhead (lesser better), efficiency
  - Fairness, response time, throughput
  - Performance predictability
- **Adoption** : whether if the os is acceptable at the very high level company

### Design Tradeoffs
- Must balance between the 5s eg.
- Preserves legacy API -> Portability (up), Reliable (down), Security (down)
- Breaking an abstraction -> Performance (up), Portability (down), Reliability (down)

### Early Operation Systems
didn't have keyboard, mouse, display monitor at the time -> punched card and printers for I/O
> Computers are very Expensive
- **One application at a time**
  - Had complete control of hardware : **ONE APPLICATION**
  - OS was runtime library (or Systems Library eg. <stdio.h>) : **NO OS**
  - Users would stand in line to use the computer : **QUEUE**
- **Batch systems** : automatically load the new input (program) after the program terminal detected
  - Keep CPU busy by having queue of jobs
  - OS would load next job while current one runs
  - Users would submit jobs (analogy: in the "tray" of printer I/P), and wait ,and wait, and wait...

### Time-Sharing Operating Systems
started using keyboard, display monitor -> terminal to visualize input and output .. becoming more and more like OS nowadays
> Computers and People (Programmer) are Expensive in the 80s (?)
- **Multiple users at the same time** eg. remote desktop
  - ***Multipleprogramming*** : run multiple program at same time
  - ***Interactive performance*** : try to complete everyone's tasks quickly
  - As the computers become cheaper -> optimize for user time but not the computer time :(
- Early day of RAM
  - CODE : programs
  - DATA : global variables, const
  - HEAP : store array
  - . . .
  - STACK : LIFO call stack, only contains the address of the initial array

### Today's Operating Systems
> Computers are cheap *0*
- eg. Smartphones, Embedded systems, Laptops, Tablets, Virtual machine, Data center servers

### Tomorrow's Operating Systems
- Giant-scale data centers
- Increasing numbers of processors per computer
- Increasing numbers of computers per user
- Very large scale storage

### In-Class Activity
1. what is your opinion about operating systems functionality
  - ??????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
  - ?????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
  - ?????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
  - ??????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
  - ??????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
  - ???????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
  - ???????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
2. What is an Operating Systems?
  - ???????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????? ??????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????? ??????????????????????????????????????????????????????????????????????????????????????? ??????????????????????????????????????????????????????????????????????????????????????? ????????? OS ?????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????? ?????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????? User Interface ????????? ??????????????????????????? CLI (Command Line Interface) ?????????????????????
3. What are the Operating System Evaluation?
  - ????????????????????????/?????????????????? (Performance) ???????????????????????????????????????????????????????????? OS ??????????????????????????????????????????????????????????????????????????????????????? environment ???????????????????????????????????? ??????????????? task ???????????????????????? ?????????????????????????????????????????????????????????????????? ????????? OS ??????????????????????????????
  - ????????????????????????????????? (Security) ????????????????????????????????????????????????????????????????????? Vulnerlability accessment ?????????????????????????????????????????? ???????????????????????????????????????????????????????????????????????????????????????????????????????????????, ???????????????????????????????????????, ???????????????????????????????????????????????????????????????????????? ??????????????????????????????????????????????????????????????????????????? OS ?????????????????????????????? Opensoure ???????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????
  - ???????????????????????????????????????????????????????????? (Availability) ????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????? OS ???????????????
  - ????????????????????????????????????????????????????????????????????????????????? software ??????????????? (Integrability) ???????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????? OS ????????????????????????????????????????????????????????????
