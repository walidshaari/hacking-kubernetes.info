Running cloud native workloads on Kubernetes can be challenging: keeping them secure is even more so. Kubernetes' complexity offers malicious in-house users and external attackers alike a large assortment of attack vectors. In this book, 
[Andrew Martin](https://twitter.com/sublimino) and [Michael Hausenblas](https://twitter.com/mhausenblas) review Kubernetes defaults and threat models and shows how to protect against attacks.

The book is available via [O'Reilly online in Early Release](https://learning.oreilly.com/library/view/hacking-kubernetes/9781492081722/) and by late 2021 it will be available in full.

![book cover](hk.png)

## Coverage

* Chapter 1: we set the scene, introducing our main antagonist and also what threat modelling is.
* Chapter 2: where we focuses on pods, from configurations to attacks to defenses.
* Chapter 3: we switch gears and dive deep into sandboxing and isolation techniques (KVM, gVisor, Firecracker, Kata).
* Chapter 4: covers supply chain attacks and what you can do to detect and mitigate them.
* Chapter 5: where we review networking defaults and how to secure your cluster and workload traffic.
* Chapter 6: we shift our focus on the persistency aspects, looking at file‐ systems, volumes, and sensitive information at rest.
* Chapter 7: covers the topic of running workloads for multi tenants in a cluster and what can go wrong with this.
* Chapter 8: we focus on review different kinds of policies in use, discuss access control—specifically RBAC—and generic policy solutions such as OPA.
* Chapter 9: we cover the question what you can do if, despite controls put in place, someone manages to break in (IDS).
* Chapter 10: a somewhat special one, in that it doesn’t focus on tool‐ ing but on the human side of things, in the context of cloud as well as on-prem installations.

## About the authors

Based on our combined 10+ years of hands-on experience designing, running, attacking, and defending Kubernetes-based workloads and clusters, we want to equip you, the cloud native security practitioner, with what you need to be successful in your job.

We both have served in different companies and roles, gave training sessions, and published material from tooling to blog posts as well as have shared lessons learned on the topic in various public speaking engagements. Much of what motivates us here and the examples we use are rooted in experiences we made in our day-to-day jobs and/or saw at customers.
