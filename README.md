# Hi, I’m Rahul Dev 👋

I’m a **Rust & Solana engineer** working on **RPC, validator internals, and async Rust**.


---

## Current Focus

- Studying **Agave (Solana validator) internals**
- Building an **RPC sidecar MVP** to reduce validator contention
- Exploring:
  - mmap & shared-memory IPC
  - lock-free / wait-free data paths
  - async Rust (Tokio)
  - jsonrpsee-based RPC servers
  - safety boundaries in `unsafe` Rust

---

## Projects

### 🔹 Solana RPC Sidecar (WIP)
**Goal:** Decouple read-heavy RPC traffic from the validator replay loop

**Tech:** Rust · mmap · shared memory · lock-free queues · jsonrpsee

**Highlights**
- Validator publishes **read-only state observations**
- Sidecar serves RPC without blocking consensus or replay
- Explicit safety invariants around shared memory
- Benchmarks comparing in-process vs sidecar RPC

📂 Repo: `https://github.com/rahuldev7583/blazeRPC`

---

### 🔹 Solana Client Apps & Anchor Programs
- Built multiple Solana client-side applications
- Experience with Anchor programs and account models
- understanding of Solana runtime from a dApp perspective

---

## ✍️ Writing

I write technical deep dives on Solana & Rust infrastructure:

- RPC request flow inside Agave

📘 Medium: https://medium.com/@rahuldev7583

---

---

## 📬 Contact

- Twitter: https://twitter.com/iamrahul_dev
- GitHub: https://github.com/rahuldev7583
- Gmail: **rahuldev2714@gmail.com**

Open to **Rust / Solana infra roles** and **contract work**.
