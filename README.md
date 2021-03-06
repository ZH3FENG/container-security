# container-security
Resources for container security research, such as Docker, Kubernetes, etc.

## Kernel and architecture

Namespaces in operation by Michael Kerrisk - [whitepaper](https://lwn.net/Articles/531114/)

Control groups series by Neil Brown - [whitepaper](https://lwn.net/Articles/604609/)


2018, KubeCon, CloudNativeCon:"Container Isolation at Scale (Introducing gVisor) by Dawn Chen and Zhengyu He" - [slide](https://schd.ws/hosted_files/kccnceu18/47/Container%20Isolation%20at%20Scale.pdf) - [video](https://www.youtube.com/watch?v=pWyJahTWa4I)

2018:"A history of low-level Linux container runtimes" by Daniel J. Walsh - [article](https://opensource.com/article/18/1/history-low-level-container-runtimes)

2015:"The History of Containers" by by thildred - [article](https://rhelblog.redhat.com/2015/08/28/the-history-of-containers/)

2015, LinuxCon:"Anatomy of a Container: Namespaces, cgroups & Some Filesystem Magic" by Jérôme Petazzoni - [slide](https://www.slideshare.net/jpetazzo/anatomy-of-a-container-namespaces-cgroups-some-filesystem-magic-linuxcon)

2013:"Resource management: Linux kernel Namespaces and cgroups" by Rami Rosen - [slide](http://www.haifux.org/lectures/299/netLec7.pdf)

## Escaping

2018:"CVE-2017-1002101:kubernetes: Volume security can be sidestepped with innocent emptyDir and subpath" - [article](https://www.twistlock.com/2018/03/21/deep-dive-severe-kubernetes-vulnerability-date-cve-2017-1002101/) - [exp](https://github.com/bgeesaman/subpath-exploit)

2017:"Escaping Docker container using waitid() – CVE-2017-5123" by Daniel Shapira - [article](https://www.twistlock.com/2017/12/27/escaping-docker-container-using-waitid-cve-2017-5123/)

2016:"Abusing Privileged and Unprivileged Linux Containers" by NCC Group - [whitepaper](https://www.nccgroup.trust/globalassets/our-research/us/whitepapers/2016/june/container_whitepaper.pdf)

2015: "Chw00t: How to break out from various chroot solutions" by Balázs Bucsay - [slide](https://deepsec.net/docs/Slides/2015/Chw00t_How_To_Break%20Out_from_Various_Chroot_Solutions_-_Bucsay_Balazs.pdf)

2014:"Container escape through open_by_handle_at (shocker exploit)" - [vuln](https://lists.linuxcontainers.org/pipermail/lxc-devel/2014-June/009547.html) - [exp](https://github.com/gabrtv/shocker)


## Docker

2016:"Docker & Security" by Florian Barth and Matthias Luft - [slide](https://www.ernw.de/download/ERNW_Stocard_Docker-Devops-Security_fbarth-mluft.pdf)

2016, BSides:"Docker: Security Myths, Security Legends" by Rory McCune - [video](https://www.youtube.com/watch?v=uQigvjSXMLw)

2015, BlackHat:"Vulnerability Exploitation In Docker Container Environments" by Anthony Bettini - [video](https://www.youtube.com/watch?v=77-jaeUKH7c) - [slide](https://www.blackhat.com/docs/eu-15/materials/eu-15-Bettini-Vulnerability-Exploitation-In-Docker-Container-Environments.pdf) - [whitepaper](https://www.blackhat.com/docs/eu-15/materials/eu-15-Bettini-Vulnerability-Exploitation-In-Docker-Container-Environments-wp.pdf)


## Kubernetes

2018:"Hard Multi-Tenancy in Kubernetes by Jessie Frazelle" - [article](https://blog.jessfraz.com/post/hard-multi-tenancy-in-kubernetes/)

#### Exploring Container Security Articles by Google

Exploring container security: An overview - [article](https://cloudplatform.googleblog.com/2018/03/exploring-container-security-an-overview.html)

Exploring container security: Node and container operating systems - [article](https://cloudplatform.googleblog.com/2018/04/exploring-container-security-Node-and-container-operating-systems.html)

Exploring container security: Digging into Grafeas container image metadata - [article](https://cloudplatform.googleblog.com/2018/04/exploring-container-security-digging-into-Grafeas-container-image-metadata.html)

Exploring container security: Protecting and defending your Kubernetes Engine network - [article](https://cloudplatform.googleblog.com/2018/04/exploring-container-security-protecting-and-Defending-your-Kubernetes-Engine-network.html)

Exploring container security: Running a tight ship with Kubernetes Engine 1.10 - [article](https://cloudplatform.googleblog.com/2018/04/Exploring-container-security-Running-a-tight-ship-with-Kubernetes-Engine-1-10.html)

Exploring container security: Using Cloud Security Command Center (and five partner tools) to detect and manage an attack - [article](https://cloudplatform.googleblog.com/2018/05/Exploring-container-security-Using-Cloud-Security-Comma.html)

Exploring container security: Isolation at different layers of the Kubernetes stack - [article](https://cloudplatform.googleblog.com/2018/05/Exploring-container-security-Isolation-at-different-layers-of-the-Kubernetes-stack.html)


## Hardening

2016:"Understanding and Hardening Linux Containers" by NCC Group - [whitepaper](https://www.nccgroup.trust/globalassets/our-research/us/whitepapers/2016/april/ncc_group_understanding_hardening_linux_containers-1-1.pdf)

## Miscs

2018:"How modern containerization trend is exploited by attackers" - [article](https://kromtech.com/blog/security-center/cryptojacking-invades-cloud-how-modern-containerization-trend-is-exploited-by-attackers)

2018:"How one of our Kubernetes clusters got pwned Shopify" - [article](https://hackerone.com/reports/341876)

2015, Defcon 23:"Linux Containers: Future or Fantasy?" by Aaron Grattafiori - [video](https://www.youtube.com/watch?v=iN6QbszB1R8) - [slide](https://media.defcon.org/DEF%20CON%2023/DEF%20CON%2023%20presentations/DEFCON-23-Aaron-Grattafiori-Linux-Containers-Future-or-Fantasy-UPDATED.pdf)

## Best Practices

The Docker Bench for Security is a script that checks for dozens of common best-practices around deploying Docker containers in production.
https://github.com/docker/docker-bench-security

The Kubernetes Bench for Security is a Go application that checks whether Kubernetes is deployed according to security best practices.
https://github.com/aquasecurity/kube-bench
