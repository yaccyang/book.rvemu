# Writing a RISC-V Emulator in Rust

## Introduction

NOTE: This project is actively ongoing. Pages are not perfect and they can change soon.

This is the book for writing a 64-bit RISC-V emulator from scratch in Rust. It shows us how to implement an emulator in 10 steps. You can run [xv6](https://github.com/mit-pdos/xv6-riscv), a simple Unix-like OS, in your emulator in the final step.

You'll learn the following basic computer architecture from making an emulator in Rust:

* Basic RISC-V architecture
* Instruction sets
* Privileged architecture
* Exceptions
* Interrupts
* Peripheral devices
  * UART
  * PLIC
  * CLINT
  * Virtio
* Virtual memory system

The source code is available at [d0iasm/rvemu-for-book](https://github.com/d0iasm/rvemu-for-book).

| Step | Content |
| :--- | :--- |
| Step 1 | [CPU with Two Instructions](hardware-components/cpu-with-two-instructions.md) |
| Step 2 | [Memory and System Bus](hardware-components/memory-and-system-bus.md) |
| Step 3 | [Control and Status Registers](hardware-components/control-and-status-registers.md) |
| Step 4 | [Privileged Architecture](hardware-components/privileged-architecture.md) |
| Step 5 | [Exceptions](hardware-components/exceptions.md) |
| Step 6 | [PLIC \(a platform-level interrupt controller\) and CLINT \(a core-local interrupter\)](hardware-components/plic-a-platform-level-interrupt-controller-and-clint-a-core-local-interrupter.md) |
| Step 7 | [UART \(a universal asynchronous receiver-transmitter\)](hardware-components/uart-a-universal-asynchronous-receiver-transmitter.md) |
| Step 8 | [Interrupts](hardware-components/interrupts.md) |
| Step 9 | Virtio |
| Step 10 | Virtual Memory System |

Congratulations🎉 Now you can run xv6 in your emulator!

![](.gitbook/assets/2020-08-16-rvemu-for-book-xv6.png)

The author is [@d0iasm](https://twitter.com/d0iasm) and please feel free to ask and request anything to me via [Twitter](https://twitter.com/d0iasm) or [GitHub issues](https://github.com/d0iasm/rvemu-for-book/issues)!

