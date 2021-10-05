# IskiOS

IskiOS is a system developed at University of Rochester, and it is designed to provide efficient intra-kernel isolation for security defenses against
control-flow hijacking attacks. IskiOS retrofits **Intel Protection Keys for Userspace (PKU)** to enable its protections for kernel memory.
Having enabled what we call ***Protection Keys for Kernelspace (PKK)***, IskiOS equips the Linux kernel with **eXecute-Only Memory (XOM)** for its code segment, as well as
**write-protected race-free shadow stacks**.


IskiOS was published in the 24th International Symposium on Research in Attacks, Intrusions and Defenses (RAID'21). For more information, check our paper: [Fast Intra-Kernel Isolation and Security with IskiOS](https://arxiv.org/pdf/1903.04654.pdf).
