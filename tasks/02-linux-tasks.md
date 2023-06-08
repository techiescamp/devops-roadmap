## **Research Linux Distributions**

---

- [ ]  Compare and contrast features of RHEL and Ubuntu.
- [ ]  Discuss the pros and cons of using CentOS over RHEL.
- [ ]  Compare the package managers used by Debian and Fedora.
- [ ]  Discuss how system administration varies across different Linux distributions.
- [ ]  Investigate the security features inherent to CoreOS.

## **Setup Linux Environment**

---

**Task 1: Installing a Linux Distribution**

- [ ]  Download a popular Linux distribution (like Ubuntu, Fedora, or CentOS) and install it in a virtual machine or a spare computer.
- [ ]  Set up the root user and create a new non-root user for daily tasks.
- [ ]  Update the system packages to their latest versions using the package manager (like **`apt`**, **`dnf`**, or **`yum`**).

**Task 2: Configuring the Shell Environment**

- [ ]  Familiarize yourself with the command line interface.
- [ ]  Customize the shell prompt to your liking using PS1 environment variable.
- [ ]  Learn about environment variables and set some of your own.
- [ ]  Learn about shell aliases and create some useful ones.

**Task 3: Installing Additional Software**

- [ ]  Install software from the distribution's repositories using the package manager.
- [ ]  Add a third-party repository and install software from it.
- [ ]  Install software manually from a .deb or .rpm file.
- [ ]  Install software manually from source code.

**Task 4: Configuring Networking**

- [ ]  Configure the network settings using the command line (IP address, DNS servers, etc.).
- [ ]  Test the network connectivity with commands like **`ping`** and **`traceroute`**.
- [ ]  Set up SSH and connect to your machine remotely.

**Task 5: Setting Up a Development Environment**

- [ ]  Install a text editor or IDE, like Vim, Emacs, Visual Studio Code, or JetBrains IDEs.
- [ ]  Install build tools like **`gcc`** for C/C++, **`openjdk`** for Java, **`python`** for Python, etc.
- [ ]  Write a small program and compile/run it.
- [ ]  Install Git, clone a repository, and make some changes to it.

## **Understanding Linux Terminal**

---

**Task 1: Navigating the Filesystem**

- [ ]  Use **`cd`** to change directories.
- [ ]  Use **`ls`** to list directory contents.
- [ ]  Use **`pwd`** to print the current working directory.
- [ ]  Practice with absolute and relative paths.

**Task 2: Managing Files and Directories**

- [ ]  Use **`cp`** to copy files and directories.
- [ ]  Use **`mv`** to move or rename files and directories.
- [ ]  Use **`rm`** to remove files and directories.
- [ ]  Use **`touch`** to create new empty files.

**Task 3: Working with File Content**

- [ ]  Use **`cat`** to display the content of files.
- [ ]  Use **`less`** and **`more`** for paging through text files.
- [ ]  Use **`head`** and **`tail`** to display the beginning or end of files.

**Task 4: Redirection and Pipes**

- [ ]  Learn about standard input, standard output, and standard error.
- [ ]  Use **`>`** and **`>>`** to redirect output to a file.
- [ ]  Use **`<`** to redirect input from a file.
- [ ]  Use **`|`** to pipe output from one command to another.

**Task 5: Searching and Regular Expressions**

- [ ]  Use **`grep`** to search within text.
- [ ]  Use **`find`** to search for files in the file system.
- [ ]  Use **`|`** and **`grep`** together to filter command output.
- [ ]  Learn about basic regular expressions and use them with **`grep`**.

## **Linux Storage**

---

**Task 1: Exploring File Systems**

- [ ]  Use **`df`** to display file system disk space usage.
- [ ]  Use **`du`** to estimate file and directory space usage.
- [ ]  Understand the difference between hard and soft links (**`ln`** command).
- [ ]  Explore different file systems (ext4, XFS, Btrfs etc).

**Task 2: Disk Partitioning and Management**

- [ ]  Use **`fdisk`** to view and manage disk partitions.
- [ ]  Format a partition with a file system of your choice.
- [ ]  Mount and unmount file systems manually and by using **`/etc/fstab`**.

**Task 3: Logical Volume Management**

- [ ]  Install and set up Logical Volume Manager (LVM).
- [ ]  Create a logical volume, format it, and mount it.
- [ ]  Extend a logical volume and resize the file system.
- [ ]  Reduce a logical volume and resize the file system.

**Task 4: Network File System**

- [ ]  Set up a NFS server.
- [ ]  Configure a NFS client and mount a remote file system.
- [ ]  Understand NFS permissions and squash options.

**Task 5: Backup and Restore**

- [ ]  Use **`tar`** and **`gzip`** to create a backup of your files.
- [ ]  Use **`rsync`** to sync files between different directories or systems.
- [ ]  Restore your files from the **`tar`** backup.
- [ ]  Explore other backup solutions like **`dd`**, **`dump`**, **`cpio`**, etc.

## Linux File Permissions

---

**Task 1: Basic File Permissions**

- [ ]  Create a file and use the **`ls -l`** command to list the permissions.
- [ ]  Change the permissions of the file using **`chmod`** command with symbolic (e.g., **`chmod u+x filename`**) and numerical (e.g., **`chmod 644 filename`**) modes.
- [ ]  Explain the different permissions (read, write, execute) for user, group, and others.

**Task 2: Understanding Directory Permissions**

- [ ]  Create a directory and list its permissions.
- [ ]  Change the permissions of the directory and explain the impact on the files within.
- [ ]  Explain the significance of execute permission on a directory.

**Task 3: User and Group Management**

- [ ]  Create a new user and group using **`useradd`** and **`groupadd`** commands.
- [ ]  Add the user to the group with **`usermod`** or **`gpasswd`**.
- [ ]  Change the ownership of a file/directory with **`chown`** and **`chgrp`**.

**Task 4: Setuid, Setgid, and Sticky Bit**

- [ ]  Create a file and set the Setuid and Setgid permissions.
- [ ]  Run the file as a different user and observe the result.
- [ ]  Create a directory and set the Sticky Bit. Explain its purpose.

**Task 5: Access Control Lists (ACLs)**

- [ ]  Use the **`getfacl`** and **`setfacl`** commands to view and modify ACLs on a file/directory.
- [ ]  Discuss when and why you would want to use ACLs instead of traditional permissions.

## **Linux Security**

---

**Task 1: Configuring Firewalls**

- [ ]  Install and enable a firewall tool like UFW or Firewalld.
- [ ]  Create and apply rules to allow and deny certain types of traffic.
- [ ]  Test the firewall's efficacy using tools like **`nmap`** or **`telnet`**.

**Task 2: Understanding SELinux**

- [ ]  Learn about SELinux modes (Enforcing, Permissive, Disabled) and contexts.
- [ ]  Use commands such as **`sestatus`**, **`getenforce`**, and **`setenforce`**.
- [ ]  Practice changing the SELinux context for a file or process.

**Task 3: User Rights Management**

- [ ]  Learn about sudo and the **`/etc/sudoers`** file.
- [ ]  Add and remove users from the sudo group.
- [ ]  Test the effect of these changes.

T**ask 4: Understanding SSH Key-Based Authentication**

- [ ]  Generate a pair of SSH keys and copy your public key to another machine.
- [ ]  Attempt to SSH into the machine using key-based authentication.
- [ ]  Disable password-based SSH authentication and attempt to SSH into the machine.

**Task 5: System Hardening**

- [ ]  Explore system hardening guides and select measures applicable to your environment.
- [ ]  Implement chosen hardening measures.
- [ ]  Use a tool like Lynis or OpenSCAP to audit the security of your system.

## Linux Networking

---

**Task 1: Hostname and Network Configuration**

- [ ]  Use commands such as **`ifconfig`**, **`ip`**, **`netstat`**, **`hostname`** and **`nslookup`** to view network configuration and system hostname.
- [ ]  Change the IP address and hostname of your machine.
- [ ]  Test the changes using **`ping`**, **`nslookup`** or **`hostname -f`**.

**Task 2: Understanding Network Services**

- [ ]  Install and configure a network service, such as a web server or FTP server.
- [ ]  Connect to the service from another machine.
- [ ]  Troubleshoot any connection issues that arise.

**Task 3: Using `iptables`**

- [ ]  Learn about the structure of **`iptables`** rules.
- [ ]  Create **`iptables`** rules to allow, deny, or redirect traffic.
- [ ]  Use **`iptables -L`** to list your current rules.

**Task 4: Using `netcat`**

- [ ]  Use **`netcat`** to create a simple server and client on different machines.
- [ ]  Send a message from the client to the server.
- [ ]  Reverse the roles and send a message from the server to the client.

**Task 5: Understanding DNS**

- [ ]  Use **`nslookup`** or **`dig`** to query the DNS records for a domain.
- [ ]  Change your machine's DNS servers and test the effect.
- [ ]  If possible, set up a local DNS server and configure another machine to use it.

**Task 6: Managing Hostname**

- [ ]  Understand the role and importance of the system hostname.
- [ ]  Learn the difference between static and transient hostnames.
- [ ]  Change the system hostname using the **`hostnamectl`** command.
- [ ]  Verify the changes by displaying the system hostname.
- [ ]  Understand how changing the hostname can impact the applications and services running on the system.

## **Web Servers and Databases**

---

**Task 1: Install and Configure a Web Server**

- [ ]  Install Apache or Nginx using package management tools like **`apt`** or **`yum`**.
- [ ]  Understand and modify the main configuration files.
- [ ]  Create a virtual host/domain.

**Task 2: Host a Website**

- [ ]  Create a simple HTML webpage.
- [ ]  Serve the webpage through the web server.
- [ ]  Access the webpage from a different machine.

**Task 3: Secure the Web Server**

- [ ]  Configure firewall rules to allow/deny traffic to the web server.
- [ ]  Enable HTTPS using Let's Encrypt.

**Task 4: Analyzing Server Logs**

- [ ]  Understand the structure and contents of server logs.
- [ ]  Use **`grep`**, **`awk`**, and **`cut`** to analyze logs and find specific entries.

**Database Tasks**

**Task 5: Install and Configure a Database**

- [ ]  Install MySQL or PostgreSQL using package management tools.
- [ ]  Understand and modify the main configuration files.
- [ ]  Secure the database installation.

**Task 6: Create and Manage a Database**

- [ ]  Create a database and a table.
- [ ]  Insert, update, and delete data.
- [ ]  Perform basic SQL queries to retrieve data.

**Task 7: Backup and Restore a Database**

- [ ]  Create a backup of the database using **`mysqldump`** or **`pg_dump`**.
- [ ]  Restore the database from a backup.

**Task 8: Monitor Database Performance**

- [ ]  Understand the basic performance metrics for databases.
- [ ]  Use tools like **`top`**, **`iostat`**, and **`vmstat`** to monitor system resources utilized by the database.
- [ ]  Use database-specific tools (like **`EXPLAIN`** in SQL) to analyze query performance.

## **Load Balancers and Reverse Proxy**

---

**Task 1: Understand Load Balancing Concepts**

- [ ]  Learn about the purpose and benefits of load balancing.
- [ ]  Understand different load balancing algorithms (Round Robin, Least Connections, etc.).

**Task 2: Set Up a Load Balancer**

- [ ]  Install and configure HAProxy or Nginx as a load balancer.
- [ ]  Create a couple of web servers and configure the load balancer to distribute traffic between them.

**Task 3: Monitor and Troubleshoot the Load Balancer**

- [ ]  Learn to interpret the stats page in HAProxy or the **`nginx -s`** command output in Nginx.
- [ ]  Troubleshoot common issues (e.g., backend server down, high latency).

**Task 4: Understand Reverse Proxy Concepts**

- [ ]  Understand the purpose of a reverse proxy and how it differs from a forward proxy.

**Task 5: Set Up a Reverse Proxy**

- [ ]  Configure Nginx or Apache as a reverse proxy server for a web application.
- [ ]  Test access to the web application through the reverse proxy.

**Task 6: Secure the Reverse Proxy**

- [ ]  Enable HTTPS on the reverse proxy.
- [ ]  Understand and configure basic access controls (e.g., IP whitelisting).

**Task 7: Troubleshoot the Reverse Proxy**

- [ ]  Understand common issues (e.g., 502 Bad Gateway errors) and how to resolve them.
- [ ]  Learn to read and interpret the reverse proxy logs.

## **Systemd Management**

---

**Task 1: Understanding Systemd**

- [ ]  Understand the role of **`systemd`** in the Linux system.
- [ ]  Explore the basic concepts related to **`systemd`** (units, targets, services, etc.).

**Task 2: Working with Services**

- [ ]  Use **`systemctl`** to start, stop, restart, and check the status of services.
- [ ]  Identify failed services and understand the reasons using **`systemctl`** and **`journalctl`**.

**Task 3: Managing Systemd Units**

- [ ]  Understand the structure of a **`systemd`** unit file.
- [ ]  Create a simple **`systemd`** service unit from scratch.
- [ ]  Enable and disable **`systemd`** services to start at boot.

**Task 4: Systemd Logs and Troubleshooting**

- [ ]  Use **`journalctl`** to read and filter **`systemd`** logs.
- [ ]  Analyze log messages to troubleshoot **`systemd`** service issues.

**Task 5: Advanced Systemd Management**

- [ ]  Learn about and use **`systemd`** timers as cron replacements.
- [ ]  Understand and apply **`systemd`** resource controls and sandboxing features.
- [ ]  Create a complex **`systemd`** service unit that manages a real-world application (like a web server or database).

## Linux **Troubleshooting**

---

**Task 1: Investigating High Load**

- [ ]  Identify a high load on a system using tools like **`top`**, **`htop`**, or **`uptime`**.
- [ ]  Determine which processes are causing the high load.
- [ ]  Analyze the system logs (**`/var/log/syslog`**, **`/var/log/messages`**) to look for any error messages related to the problematic processes.

**Task 2: Resolving Disk Space Issues**

- [ ]  Determine which directories are consuming the most disk space using the **`du`** command.
- [ ]  Identify large, unnecessary files for deletion.
- [ ]  Monitor disk usage over time to understand usage patterns.

**Task 3: Troubleshooting Network Issues**

- [ ]  Use **`ping`** and **`traceroute`** to identify network connectivity issues.
- [ ]  Use **`netstat`** or **`ss`** to identify which services are listening on which ports.
- [ ]  Use **`tcpdump`** to capture and analyze network traffic.
- [ ]  Troubleshoot DNS issues using tools like **`dig`** or **`nslookup`**.

**Task 4: Investigating Memory Usage**

- [ ]  Identify high memory usage processes with **`top`** or **`htop`**.
- [ ]  Understand the difference between virtual, shared, and resident memory.
- [ ]  Monitor memory usage over time to spot leaks or excessive usage.

**Task 5: Resolving Permission Issues**

- [ ]  Identify files with incorrect permissions using the **`find`** command.
- [ ]  Correctly set file permissions and ownership with **`chmod`** and **`chown`**.
- [ ]  Understand and apply the principle of least privilege.

**Task 6: Analyzing System Performance**

- [ ]  Use **`sar`** to monitor system performance over time.
- [ ]  Identify and analyze CPU, memory, and I/O bottlenecks.
- [ ]  Troubleshoot slow boot time issues using **`systemd-analyze`**.

**Task 7: Dealing with Failed Services**

- [ ]  Use **`systemctl`** to check the status of a failed service.
- [ ]  Analyze logs of the failed service using **`journalctl`**.
- [ ]  Identify and resolve common service failure issues (e.g., configuration errors, missing dependencies).

## Control Groups & Namespaces Tasks

---

**Task 1: Exploring Control Groups (cgroups)**

- [ ]  Install **`cgroup`** utilities.
- [ ]  Create a new **`cgroup`** and assign a process to it.
- [ ]  Limit the CPU and memory usage of your **`cgroup`**.
- [ ]  Monitor the resource usage of your **`cgroup`**.

**Task 2: Playing with Namespaces**

- [ ]  Use **`unshare`** to create new namespaces and run processes inside them.
- [ ]  Explore different types of namespaces (PID, NET, UTS, IPC, USER, MNT).
- [ ]  Use **`nsenter`** to enter an existing namespace.

**Task 3: Combining `cgroups` and `namespaces`**

- [ ]  Create a new **`cgroup`** and a new namespace.
- [ ]  Run a process inside the new namespace and **`cgroup`**.
- [ ]  Limit and monitor the resource usage of the process.

**Task 4: Troubleshooting with cgroups and namespaces**

- [ ]  Diagnose a system performance issue using cgroup statistics.
- [ ]  Use namespaces to isolate a problematic process and diagnose it.
- [ ]  Understand how to use cgroups and namespaces for resource management and isolation.

## eBPF Tasks

---

**Task 1: Learning Basics of eBPF**

- [ ]  Read up on the basics and understand the concept of eBPF.
- [ ]  Explore the purpose and uses of eBPF.

**Task 2: Setting Up eBPF**

- [ ]  Set up an environment that supports eBPF.
- [ ]  Install BCC (BPF Compiler Collection).

**Task 3: Exploring eBPF Tools**

- [ ]  Use different tools provided by BCC for system analysis.
- [ ]  Understand how each tool works and what information it provides.

**Task 4: Writing eBPF Programs**

- [ ]  Write a basic eBPF program that performs a simple task.
- [ ]  Compile and load your eBPF program using BCC.
- [ ]  Analyze the effect of your eBPF program on the system.

**Task 5: Advanced eBPF**

- [ ]  Use eBPF to monitor network traffic.
- [ ]  Use eBPF to trace system calls and kernel functions.
- [ ]  Implement a complex use case using eBPF. For example, implementing a basic firewall.
