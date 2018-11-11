# CudaMon

## Partitioning of CUDA SMs among tasks to improve Real-Time schedulability

The latest GPU architecture, NVIDIA Volta, allows the partitioning of SMs among various tasks using NVIDIA Multi Process Service. MPS allows us to partition and set a maximum limit on the number of SMs that a process can use. This partitioning has been leveraged to improve schedulability when multiple real time processes are running simultaneously. A controller to launch and manage all the tasks in the system has been designed and implemented. The core contention avoidance algorithm was based on TCP AIMD. The controller has been tested with synthetic as well as Deep learning based tasks to show its usefulness in real world workloads.

[Report](https://github.com/albd/cudaMon/raw/master/15_618_Project_Final_Report.pdf)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Hy1om7pi5DE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
