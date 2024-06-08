
**How can you clone a Git repository via Jenkins?**  
First, we must enter the e-mail and user name for your Jenkins system, then switch into your job directory and execute the `git config` command.

**What are the Advantages of Ansible?**  
- Agentless, it doesn’t require any extra package/daemons to be installed
- Very low overhead
- Good performance
- Idempotent
- Very Easy to learn
- Declarative not procedural

**What’s the use of Ansible?**  
Ansible is mainly used in IT infrastructure to manage or deploy applications to remote nodes. For instance, if we want to deploy one application on hundreds of nodes by just executing one command, Ansible is the tool to use, provided you have some knowledge of Ansible scripts to understand or execute the task.

**What’s the difference between Ansible Playbook and Roles?**  
- **Roles:** Reusable subsets of a play. A set of tasks for accomplishing certain roles (e.g., common, webservers).
- **Playbooks:** Contain plays. Map among hosts and roles (e.g., site.yml, fooservers.yml, webservers.yml).

**How do I see a list of all the ansible_ variables?**  
Ansible by default gathers “facts” about the machines, and these facts can be accessed in Playbooks and in templates. To see a list of all the facts that are available about a machine, you can run the `setup` module as an ad-hoc action:
`Ansible -m setup hostname`
This will print out a dictionary of all the facts that are available for that particular host.

**What is Docker?**  
Docker is a containerization technology that packages your application and all its dependencies together in the form of containers to ensure that your application works seamlessly in any environment.

**What is a Docker image?**  
A Docker image is the source of a Docker container. In other words, Docker images are used to create containers.

**What is a Docker container?**  
A Docker container is the running instance of a Docker image.

**Can we consider DevOps as Agile methodology?**  
Of course, we can! The only difference between Agile methodology and DevOps is that Agile methodology is implemented only for the development section, whereas DevOps implements agility on both development and operations sections.

**What are the advantages of using Git?**  
- Data redundancy and replication
- High availability
- Only one `.git` directory per repository
- Superior disk utilization and network performance
- Collaboration-friendly
- Git can be used for any sort of projects.

**What is a kernel?**  
A kernel is the lowest level of easily replaceable software that interfaces with the hardware in your computer.

**How can you define particular space to the file?**  
This feature is generally used to give the swap space to the server. For instance, to create a swap space of 1GB, you can use the command:
```dd if=/dev/zero of=/swapfile1 bs=1G count=1```

**What is the concept of sudo in Linux?**  
Sudo (superuser do) is a utility for UNIX- and Linux-based systems that provides an efficient way to give specific users permission to use specific system commands at the root (most powerful) level of the system.

**What is a Jenkins Pipeline?**  
Jenkins Pipeline (or simply “Pipeline”) is a suite of plugins that supports implementing and integrating continuous delivery pipelines into Jenkins.

**How to stop and restart the Docker container?**  
To stop the container: `docker stop containerID`  
To restart the Docker container: `docker restart containerID`

**What platforms does Docker run on?**  
Docker runs on Linux and Cloud platforms:
- **Linux:**
  - Ubuntu 12.04 LTS+
  - Fedora 20+
  - RHEL 6.5+
  - CentOS 6+
  - Gentoo
  - ArchLinux
  - openSUSE 12.3+
  - CRUX 3.0+
- **Cloud:**
  - Amazon EC2
  - Google Compute Engine
  - Microsoft Azure
  - Rackspace

Note that Docker does not run on Windows or Mac for production as there is no support. However, it can be used for testing purposes on Windows.
