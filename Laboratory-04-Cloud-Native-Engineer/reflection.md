# Mission Reflection

The exposure gained here has enabled me to realize the application of containerization in cloud computing and its difference from regular Virtual Machines. Prior to this hands-on training, cloud computing was a term I connected mostly to VMs, however it was a revelation to me that containers can be a much more efficient and lightweight solution for running applications.

**1. How does the boot time and setup process of a Docker container compare to installing an operating system on a Virtual Machine?**

A Docker container typically boot and runs a lot faster than other methods, not because it actually installs the underlying OS but rather the fact that it uses existing and lightweight image that contains only the application and the minimum of its dependencies already. By contrast, launching a VM needs a guest OS installation which takes even more memory and hardware resources as well as time.


**2. Why is port mapping (-p 8080:80) necessary when running a web server inside a container?**

As you know, port mapping is important in that it binds a port on the host computer to the same or different port in the container. Here, port 8080 of the host was mapped to port 80 of the Nginx container. Thus, I could reach the web server via `http://localhost:8080`.

**3. What happens to the data inside a container when you use the docker rm command?**

The `docker rm` command removes a stopped container. Any data stored only inside the container's writable layer can be lost when the container is removed. This taught me that important data should be stored using volumes or another persistent storage method.

**4. How do you think containerization changes the way software developers and IT operations teams work together (DevOps)?**

Containerization supports collaboration among developer and IT operations teams since applications can be wrapped in their dependencies and run consistently across various environments. This not only helps in addressing development and production systems inconsistencies but can also allow for faster deployment, testing, and updates.

**5. How is your GitHub portfolio evolving?**

With every laboratory activity that I post, my GitHub portfolio gets more structured. This lab consists of a report, Docker commands, pictures, my thoughts, and a research. It records the progress I have made by studying cloud computing technologies and provides a detailed description of my practice skills.
From this activity, I learned about Docker and its role in a containerization which is an important aspect of modern cloud computing.


