# Lucas Nishimura

**Solution Architect | Hands-on builder of distributed systems, network platforms, and AI-assisted engineering workflows**

I design systems, but I like staying close to the code.

My work usually lives where architecture, infrastructure, and implementation meet: distributed Java services, Go-based infrastructure tools, telecom platforms, network simulation, observability, and automation. I enjoy taking an idea from architecture diagrams and trade-off discussions all the way to working software, tests, packaging, deployment, and operational documentation.

I am based in Curitiba, Brazil, and I build mostly around JVM, Go, Linux, networking, and systems that need to keep behaving well under real-world constraints.

Most of my current public engineering work is organized under [nishisan-dev](https://github.com/nishisan-dev/).

## Projects I care about

### [n-backup](https://github.com/nishisan-dev/n-backup)

High-performance client-server backup system written in Go. It focuses on direct streaming from source to destination over TCP with mandatory mTLS, parallel streams, resumability, integrity checks, object storage integration, WebUI observability, Prometheus metrics, and operational packaging for Linux.

### [ishin-gateway](https://github.com/nishisan-dev/ishin-gateway)

Programmable API gateway and reverse proxy built in Java, with Groovy-based dynamic routing rules, OAuth2/JWT support, Zipkin/Prometheus observability, circuit breaker, rate limiting, cluster mode, rule deployment, and high-throughput streaming paths.

### [nishi-network-simulator](https://github.com/nishisan/nishi-network-simulator)

Deterministic Java network simulator with a discrete-event engine, Cisco-like CLI, MCP integration for AI agents, and realistic protocol modeling across L2/L3, BGP, OSPF, IS-IS, MPLS, EVPN/VXLAN, SRv6, multicast, redundancy, services, and observability.

### [nishi-utils](https://github.com/nishisan-dev/nishi-utils)

Java utility library and distributed systems playground. It includes persistent maps and queues, plus NGrid: a TCP-based distributed infrastructure for queues, maps, replication, leader election, quorum, catch-up, logical consumers, type-safe serialization, and outbound backpressure.

### TEMS

Telecom fault-management platform experience: event collection, alarm processing, correlation, persistence, probes, gateways, and integrations across SNMP, Syslog, JMS/Kafka, SQL, REST, CORBA/TMF814, databases, and downstream systems. Public notes stay high-level because this kind of work can involve sensitive operational context.

### [n-netman](https://github.com/nishisan-dev/n-netman)

Lightweight Go agent for declarative L2/L3 VXLAN overlays across Linux/KVM/libvirt hosts. It handles bridge/VXLAN management, peer state, route exchange over gRPC, mTLS, policy-based routing, health checks, metrics, and VM attachment workflows.

## Other engineering threads

- [n-brain](https://github.com/nishisan/n-brain): experimental Java framework for artificial cognitive dynamics, simulated time, homeostasis, topology-aware coupling, and long-running developmental simulations.
- [grafo-db](https://github.com/nishisan/grafo-db): graph/data-structure experiments around Java graph libraries, storage, algorithms, and property graph modeling.

## How I work

- I start with architecture, constraints, failure modes, and integration boundaries, then move into implementation details until the system is actually usable.
- I care about deterministic tests, practical documentation, observability, packaging, CI, and the boring operational pieces that make software survive outside a demo.
- I use AI agents such as Codex, Claude, and Gemini as part of my engineering loop: repository analysis, design exploration, implementation support, code review, test generation, documentation, and debugging across large codebases.
- I like tools that make complex systems easier to reason about: CLIs, simulators, traces, metrics, diagrams, reproducible labs, and automation.

## Skills

**Architecture and systems**

Solution architecture, distributed systems, integration design, service boundaries, reliability trade-offs, event-driven systems, telecom platforms, observability, automation, and technical documentation.

**Backend and infrastructure**

Java 21/25, Maven, Go, Linux, Docker, systemd, shell tooling, CI/CD, TCP services, mTLS, OAuth2/JWT, Prometheus, Zipkin, tracing, health checks, packaging, and release workflows.

**Networking**

L2/L3 networking, VLANs, VXLAN, BGP, OSPF, IS-IS, MPLS, EVPN, SRv6, multicast, BFD, VRF, ACLs, NAT, DHCP, Linux bridges, KVM/libvirt, and network simulation.

**AI-assisted engineering**

Codex, Claude, Gemini, agent-driven repository exploration, implementation planning, test-driven iteration, PR review support, documentation drafting, and architecture brainstorming with concrete code context.

## Contact

- Website: [nishisan.dev](https://nishisan.dev)
- GitHub: [@nishisan](https://github.com/nishisan)
- Organization: [nishisan-dev](https://github.com/nishisan-dev/)
- Location: Curitiba, PR, Brazil
