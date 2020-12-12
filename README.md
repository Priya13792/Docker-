# Docker-
What is Virtualization?

[Docker](https://stackify.com/docker-tutorial/) Virtualization refers to importing a guest operating system on our host operating system, allowing developers to run multiple OS on different VMs while all of them run on the same host, thereby eliminating the need to provide extra hardware resources.

These virtual machines are being used in the industry in many ways as follows:
•	Enabling multiple operating systems on the same machine
•	Cheaper than the previous methods due to less/compact infrastructure setup
•	Easy to recover and do maintenance if there’s any failure state
•	Faster provisioning of applications and resources required for tasks
•	Increase in IT productivity, efficiency, and responsiveness

Let’s check out the working of VMs with the architecture and also understand the issues faced by them. [Docker tutorial](https://stackify.com/docker-tutorial/).

What is a Virtualization Host?
From the above VM architecture, it is easy to figure out that the three guest operating systems acting as virtual machines are running on a host operating system. In virtualization, the process of manually reconfiguring hardware and firmware and installing a new OS can be entirely automated; all these steps get stored as data in any files of a disk.

Virtualization lets us run our applications on fewer physical servers. In virtualization, each application and operating system live in a separate software container called VM. Where VMs are completely isolated, all the computing resources like CPUs, storage, and networking are pooled together, and they are delivered dynamically to each VM by a software called a hypervisor.
However, running multiple VMs over the same host leads to degradation in performance. As guest operating systems have their own kernel, libraries, and many dependencies running on a single host OS, it takes up large occupation of resources such as the processor, hard disk and, especially, its RAM.
Also, when we use VMs in virtualization, the bootup process takes a long time that would affect efficiency in the case of real-time applications. In order to overcome such limitations, containerization was introduced. [Read more here](https://www.guru99.com/docker-tutorial.html).

How did containerization overcome these issues? Let’s discuss this further in this [Docker tutorial link](https://www.simplilearn.com/tutorials/docker-tutorial/what-is-docker-container).

[What is Docker and Docker Container?](https://www.simplilearn.com/tutorials/docker-tutorial).

Or, let’s understand what exactly containerization is in this [Docker for beginners tutorial](https://intellipaat.com/blog/tutorial/devops-tutorial/docker-tutorial/).
