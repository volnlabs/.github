<div align="center">

# Voln Labs

**Building the runtime for autonomous machines.**

</div>

---

Today's robots need a firmware reflash to change behavior. Stop the robot, rebuild, redeploy, reboot, hope nothing broke.

We're building an operating system where new behavior loads at runtime—verified, sandboxed, and hot-swappable. No downtime. No reflashing.

## What we're building

- **AxiomOS** — a bare-metal Rust kernel with runtime-loadable eBPF programs
- **Verification tooling** — proving program safety before execution
- **Robotics SDK** — libraries for autonomous systems built on top

## The bet

eBPF proved runtime extension works in Linux. Rust proved kernels can be safe. Nobody has built this for robotics yet.

We are.

---

<div align="center">

Rust · eBPF · bare-metal · ARM64 / x86_64 / RISC-V

Independent systems research.

</div>
