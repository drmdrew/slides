class: center, middle

# Intro to Docker InfraKit

Drew MacInnis (github.com/drmdrew)
- https://github.com/drmdrew/infrakit-demo

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

https://blog.docker.com/2016/03/democratizing-scale-google-borg-twitter-aurora-docker/

* March 2016: Docker Inc. acquires Conductant, Inc.
  - Bill Farner, David Chung, and John Sirois
  - Bill Farner: Apache Aurora project (Aurora is a Mesos framework)
  - http://aurora.apache.org/

> "The Quest for an Open Borg"
<br/><br/>
> "Aurora is responsible for management and scaling of microservices
> at Twitter and is used daily by over a thousand engineers across the company"
<br/><br/>
> "In building Aurora, we focused on technical as well as organizational scalability. 
> ...
> At Twitter, we needed Aurora to excel at both. 
> Today, Aurora manages clusters with **tens of thousands** of machines
> used by **hundreds of engineers** to develop and deploy hundreds of services.
> It accomplishes this feat with an **operations team of just three engineers**"

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

## Use a docker infrakit image (I had problems!)

```bash
Attaching to infrakitdemo_group_1
group_1  | panic: user: Current not implemented on linux/amd64
group_1  |
group_1  | goroutine 1 [running]:
group_1  | panic(0x73a720, 0xc42000b120)
group_1  |  /usr/local/go/src/runtime/panic.go:500 +0x1a1
group_1  | github.com/docker/infrakit/discovery.Dir(0x720720, 0xc420033b3f)
```
---

# Demo 1: A Quick Tutorial

https://github.com/docker/infrakit/blob/master/docs/tutorial.md

---

# Future

From Docker blog 2016/10:
>  In a future release, InfraKit will also become 
> part of the Docker Engine.

## Docker for AWS/Azure

https://beta.docker.com/docs/aws/

---

# Questions?

---

# Thank you!

