# Enoch Agyemang Twumasi
**Software Engineer & Systems Architect**  
[LinkedIn](https://linkedin.com/in/enoch-twumasi) | [Portfolio](https://firstlastdev.com/#founder) | [Email](mailto:eatblessing@gmail.com)

I engineer solutions across the computing stack—from bare-metal firmware and microcontroller systems to high-performance, deterministic enterprise software. My approach to digital infrastructure is heavily informed by a background in physical systems and clinical healthcare, where state isolation, strict failure boundaries, and high reliability are non-negotiable. I apply that exact scientific rigor to software engineering, operating with a strict understanding of underlying invariants, memory management, and execution models.

## Technical Architecture & Competencies

| Domain | Technologies & Concepts |
| :--- | :--- |
| **Embedded Systems & Bare-Metal** | C, Embedded C, ARM Cortex-M / STM32 Architecture, Register-Level Programming, Memory-Mapped I/O, Firmware Startup & Linker Configuration |
| **Runtime & Language Systems** | JavaScript, Strict TypeScript, V8 Internals (Execution Models, Memory/GC), Node.js Architecture, libuv, Event Loop Mechanics |
| **Networking & Protocol Engineering** | TCP/UDP Networking, Raw Socket Programming, Application-Layer Protocol Design, Binary Encoding, Bitwise Serialization |
| **Modern Enterprise Architecture** | Next.js 16+ (App Router), React 19, React Server Components (RSC), Server-Side Architectures, Tailwind CSS |
| **Data, Security & AI Systems** | Relational Database Design, Supabase, Upstash Redis, RBAC Security Boundaries, Grounded AI (RAG), Deterministic SEO |

## Featured Engineering Repositories

### Embedded Systems & Bare-Metal Engineering
*My current engineering trajectory, focusing on direct hardware-level programming, memory-mapped I/O, and bare-metal C.*

*   **[nucleo-h755zi-q-baremetal-bringup](https://github.com/enoch-twumasi/nucleo-h755zi-q-baremetal-bringup)**  
    *Bare-metal firmware for the STM32 Nucleo H755ZI-Q (ARM Cortex-M7).*  
    Engineered entirely without the STM32 Hardware Abstraction Layer (HAL). This project demonstrates direct silicon interaction through register-level RCC and GPIO configuration. It includes a custom-authored C runtime startup sequence with an X-Macro interrupt vector table, and a dedicated linker script establishing firmware memory layout, explicit boundaries, and LMA/VMA placement.

### Networking & Protocol Engineering
*Earlier systems-level explorations bridging application logic, data representation, and network transport prior to transitioning into bare-metal C.*

*   **[OneByte-Protocol](https://github.com/enoch-twumasi/OneByte-Protocol)**  
    *Custom binary application-layer protocol and UDP server architecture.*  
    Implemented in JavaScript/Node.js, this project explores binary protocol design beneath the standard HTTP stack. It demonstrates packing multiple command fields (integer IDs, state flags, commands) into a single-byte payload using logical bitwise masking and shifting, transmitted via connectionless UDP sockets (`dgram`).

## Enterprise Architecture & Deployments

As the Founder & Lead Engineer of **First and Last**, I architect and deploy production enterprise platforms that demand the same deterministic reliability as lower-level systems.

*   **High-Performance Architecture:** Engineered production platforms utilizing Next.js 16+, React 19, and React Server Components (RSC), applying strict server-first rendering to achieve near-instant TTFB and perfect Core Web Vitals.
*   **Security & Infrastructure:** Designed immutable architectures implementing strict RBAC security boundaries, multi-tenant data isolation, and centralized server-level credential vaulting.
*   **Deterministic AI Integration:** Architected grounded Retrieval-Augmented Generation (RAG) systems with strict execution boundaries to integrate LLMs into live business environments without data leaks or hallucinations.

## Operational Philosophy

Code is a mechanism to solve real-world problems. Whether configuring an ARM Cortex-M peripheral register, allocating raw UDP buffers for network transport, or architecting a multi-tenant database boundary, the objective remains the same: highly reliable, scientifically rigorous, and mathematically sound execution.
