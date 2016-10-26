class: center, middle

# Intro to Docker InfraKit

---

class: center, middle

# What is Docker InfraKit?

https://github.com/docker/infrakit

> A toolkit for creating and managing declarative,
> self-healing infrastructure.

<img src="https://github.com/docker/infrakit/raw/master/images/arch.png"
     alt="InfraKit Architecture" style="width: 60%;"/>


---

# InfraKit Origins

https://blog.docker.com/2016/10/introducing-infrakit-an-open-source-toolkit-for-declarative-infrastructure/

> While working on Docker for AWS and Azure, ...
> We started InfraKit to solves these problems and to 
> provide the ability to create a self healing infrastructure
> for distributed systems.

---

# InfraKit Origins (cont.)

March 2016: Docker Inc. acquires Conductant, Inc.
Bill Farner, David Chung, and John Sirois
Bill Farner: Apache Aurora project (Aurora is a Mesos framework)

> "The Quest for an Open Borg"

> "Aurora is responsible for management and scaling of microservices
> at Twitter and is used daily by over a thousand engineers across the company"

> "In building Aurora, we focused on technical as well as organizational scalability. 
> ...
> At Twitter, we needed Aurora to excel at both. 
> Today, Aurora manages clusters with **tens of thousands** of machines
> used by **hundreds of engineers** to develop and deploy hundreds of services.
> It accomplishes this feat with an **operations team of just three engineers**"

[1]: https://blog.docker.com/2016/03/democratizing-scale-google-borg-twitter-aurora-docker/

---
# Getting Started

## Build from source (golang)

```bash
mkdir -p ~/go/src/github.com/docker
cd !$
git clone git@github.com:docker/infrakit.git
cd infrakit
make binaries
```

---

# Demo 1: A Quick Tutorial


---

# Future

From Docker blog 2016/10:
>  In a future release, InfraKit will also become 
> part of the Docker Engine.

---

# Q & A

---

# Thank you!

