# NetPilot

**AI for Networks.** Spin up any multi-vendor network in minutes — validate changes, run POCs, and evaluate new architectures using AI that builds real labs with real device CLIs.

Modern network teams lose weeks to lab setup: provisioning VMs, sourcing device images, wiring topologies, writing baseline configs, and maintaining lab infrastructure that drifts out of sync with production. For teams doing continuous change validation, pre-sales POCs, or serious network research, the setup tax is the bottleneck.

NetPilot collapses that work. Describe a network in plain English — or import your production configs — and NetPilot generates the topology, vendor-specific configurations, and deploys a fully working lab to isolated cloud infrastructure with real device CLIs. Minutes, not weeks.

### Built for enterprise teams

**POC Labs for network vendors and system integrators.** Spin up working demo environments in minutes instead of months. Sales engineers describe the customer environment — vendor mix, protocols, topology — and show prospects exactly how the product performs in their network. Tear it down after the call.

**Change management sandbox for NetOps teams.** Import production configs to create a digital twin. Test routing policy changes, firewall updates, firmware upgrades, and failover scenarios in an isolated environment before touching live infrastructure. 68% of infrastructure outages come from configuration errors — validate changes before they reach production.

**Research and evaluation environments for R&D teams.** Enterprise research groups, government labs, and financial infrastructure teams use NetPilot to evaluate new architectures, protocols, and vendor solutions without touching production. Ephemeral, auditable, multi-vendor — spin up a topology for a specific study, run the analysis, tear it down. Dedicated infrastructure available for sensitive workloads.

### Multi-vendor by default

Cisco IOL, Juniper cRPD, Arista cEOS, Nokia SR Linux, Palo Alto PAN-OS, Fortinet FortiGate, and FRR running side-by-side in a single topology. Real container images with full CLI access, not simulated abstractions.

### How it works

1. **Design.** Describe any topology in natural language — OSPF, MPLS L3VPN, BGP, leaf-spine — no diagrams or templates required
2. **Configure.** AI generates production-grade vendor-specific configurations, ready to deploy
3. **Deploy.** Real network OS instances run on isolated Containerlab infrastructure. SSH into any device, run show commands, debug protocols
4. **Validate.** Routing tables, protocol adjacencies, end-to-end reachability — checked and diagnosed autonomously
5. **Test.** Built-in iperf3 traffic generation validates throughput, latency, and failover behavior before anything touches production

### Isolation and security

Each lab runs in its own isolated Containerlab instance. No shared infrastructure between labs. Ephemeral by default — created on demand, destroyed when done. Data encrypted in transit and at rest. Enterprise customers can request dedicated infrastructure and SSO integration.

### Resources

- **Platform**: [netpilot.io](https://netpilot.io)
- **Use cases**: [Change validation](https://netpilot.io/network-digital-twin) · [Pre-sales POCs](https://netpilot.io/for-software-vendors) · [Training labs](https://netpilot.io/for-training-providers)
- **Documentation**: [netpilot.io/docs](https://netpilot.io/docs)
- **Engineering blog**: [netpilot.io/blog](https://netpilot.io/blog)
- **Enterprise inquiries**: contact@netpilot.io

This organization hosts public resources for network teams evaluating or deploying NetPilot — reference topologies, integration patterns, and operator-facing documentation.

---

*NetPilot LLC · 6 Liberty Square #2747 · Boston, MA 02109*
