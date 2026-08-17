# Laboratory 03 – Multi-Cloud Explorer

## Mission 3: Become a Multi-Cloud Explorer

This laboratory activity explores Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

## Mission Objectives

- Explore the major public cloud platforms.
- Identify the core services offered by AWS, Microsoft Azure, and Google Cloud Platform.
- Compare cloud services across different providers.
- Analyze business requirements and recommend appropriate cloud solutions.
- Create professional technical documentation using Markdown.
- Continue developing a well-organized GitHub Cloud Computing Portfolio.

## Checkpoint 7 – Linux Investigation

### Linux Server Information

The Linux server was investigated using the KillerCoda Playground. The following information was collected using Linux system commands.

| System Information | Result                                        |
| ------------------ | --------------------------------------------- |
| Operating System   | Ubuntu 24.04.4 LTS                            |
| Architecture       | x86_64                                        |
| CPU                | Intel Xeon E312xx (Sandy Bridge, IBRS update) |
| CPU(s)             | 1                                             |
| Memory             | 1.9 GiB                                       |
| Memory Used        | 413 MiB                                       |
| Memory Available   | 1.5 GiB                                       |
| Disk Size          | 19 GiB                                        |
| Disk Used          | 5.4 GiB                                       |
| Disk Available     | 13 GiB                                        |
| Disk Usage         | 30%                                           |

### Linux Commands Used

The following commands were used to identify the Linux server information:

```bash
cat /etc/os-release
lscpu
free -h
df -h
```

### Cloud Services That Could Host the Linux Server

If this Linux server were migrated to the cloud, it could be hosted using virtual machine services from all three major cloud providers.

| Cloud Provider              | Service                | Purpose                                                 |
| --------------------------- | ---------------------- | ------------------------------------------------------- |
| Amazon Web Services (AWS)   | Amazon EC2             | Hosts Linux-based virtual machines and server workloads |
| Microsoft Azure             | Azure Virtual Machines | Hosts Linux virtual machines and applications           |
| Google Cloud Platform (GCP) | Compute Engine         | Hosts Linux virtual machines and scalable workloads     |

### Recommendation

The Ubuntu Linux server can be migrated to AWS, Azure, or GCP because all three providers support Linux-based virtual machines. Amazon EC2, Azure Virtual Machines, and Google Compute Engine can provide the required compute environment for running the server and its applications. The final provider should be selected based on factors such as cost, performance, scalability, existing infrastructure, and business requirements.

### Screenshot Evidence

The following screenshots should be included as evidence of the Linux investigation:

1. **Operating System:** KillerCoda terminal showing the output of `cat /etc/os-release`.
2. **CPU Information:** KillerCoda terminal showing the output of `lscpu`.
3. **Memory:** KillerCoda terminal showing the output of `free -h`.
4. **Disk Space:** KillerCoda terminal showing the output of `df -h`.



