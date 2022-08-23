# Amazon Elastic Compute Cloud

- Amazon EC2 provides secure, resizable compute capacity in the cloud as Amazon EC2 instances.
- It runs on top of big physical host machine AWS machines using virtualization technologyThis phenomenan is called multitenancy and hypervysor is responsible for coordinating multitenancy.
- EC2 instances are highly scalableand we can also scale it horizontally using Amazon EC2 autoscaling groups.
- You don’t pay for stopped or terminated instances because there is no computation power used by them but EBS volumes attached to instances continue to retain information and accrue charges.

## Types of EC2 Instances

### General Purpose Instances

- General purpose instances provide a balance of compute, memory, and networking resources.
- If you need an application in which the resource needs for compute, memory, and networking are roughly equivalent and does not require optimization in any single resource area.

### Compute Optimized Instances

- Compute optimized instances are ideal for compute-bound applications that benefit from high-performance processors
- ideal for high-performance web servers, compute-intensive applications servers, and dedicated gaming server
- You can also use compute optimized instances for batch processing workloads that require processing many transactions in a single group.

### Memory Optimized instances

- Memory optimized instances are designed to deliver fast performance for workloads that process large datasets in memory.
- ideal for high-performance database or a workload that involves performing real-time processing of a large amount of unstructured data.

### Accelarated Computing Instances

- Accelerated computing instancesuse hardware accelerators, or coprocessors, to perform some functions more efficiently than is possible in software running on CPUs
- In computing, a hardware accelerator is a component that can expedite data processing.
- Accelerated computing instances are ideal for workloads such as graphics applications, game streaming, and application streaming.

### Storage Optimized Instance

- Storage optimized instances are designed for workloads that require high, sequential read and write access to large datasets on local storage.
- Storage optimized instances are designed to deliver tens of thousands of low-latency, random IOPS to applications.
- Input/Output operations per second (IOPS) is a metric that measures the performance of a storage device. It indicates how many different input or output operations a device can perform in one second.
- Ideal for distributed file systems, data warehousing applications, and high-frequency online transaction processing (OLTP) systems
