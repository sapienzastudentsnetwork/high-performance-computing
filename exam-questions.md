# Oral Exam
The oral exam starts with the presentation of the two (optional) assigments, if you didn't make them expect more in depth questions.

## Part 1: **Pontarelli**
_Likes to go in detail_

### Optimizations
- Struct of Array vs Array of Structs effects on cache
- How does tiling work?
- What does -ffast-math actually do?

### Profiling
- Different types of profiling (instrumentation vs sampling)
- How to start profiling a program (roofline, top down)
- How does the PMU work?
- How do Performance Counters work?
- Which are the first level TMA metrics?
- What does a very high retiring percentage mean in TMA?
- What is a branch misprediction and how does the hardware recover?
- Make a practical example of a situation in which you have high frontend/backend TMA percentage? 

### End-Host Networking
- Talk about end-host networking: life of a packet (from NIC to User Space, in detail)
- What mechanism does the NIC use write a packet to kernel space?
- How does RDMA work (read, write)

## Part 2: **De Sensi**
_Lets you talk about the 2nd assignment, some question mainly regarding the communication strategy_

- Why did you use NCCL/NVSHMEM/MPI in the assignment

### NCCL
- How does NCCL work?
- Which are the benefits with respect to CUDA-Aware MPI?
- Why are the first couple of NCCL operations issued in a program usually very slow?

### NVHSMEM
- How does NVSHMEM work?
- How would you implement an AllToAllv using NVSHMEM?
