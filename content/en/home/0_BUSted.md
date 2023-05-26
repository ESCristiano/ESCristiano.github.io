---
title: "About BUSted"
image: "contention.png"
weight: 0
---

**BUSted** is a novel class of **microarchitectural side-channel attacks** that exploit timing differences in the arbitration logic of MCUs' bus interconnect. It can **bypass** all security protections, including **memory protection units** (MPUs) and **TrustZone**, and steal secrets in real-time. Unlike other side-channel attacks, BUSted does not rely on complex microarchitectural components such as caches or branch predictors. It is effective even in very restrictive setups -- single-core MCUs with interrupts disabled, and running applications operating over ephemeral secrets. The spy logic of BUSted is implemented through **hardware gadgets** -- groups of interconnect peripherals that operate autonomously, obviating CPU intervention. By targeting a ubiquitous microarchitectural component found in all MCUs, BUSted poses a substantial security hazard to the entire range of MCUs, including Armv6-M, Armv7-M, Armv8-M, RISC-V, PIC, and AVR
