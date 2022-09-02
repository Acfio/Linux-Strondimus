# Linux-Strondimus
This is a **modified kernel linux** created for my **OS Debian-Based Strondimus**. The actual kernel release is the [_**linux-5.15.64**_](https://www.kernel.org/) and the name of the version is **Vodka**.

## Characteristics

The **virtualitation** have been **desactivated for decrease the up time of the computer.**

Old Intel **(Pentium, Celleron...)** and AMD **(Athlon, FX...)** processor haven´t got support, **the kernel automaticly will run x86 generic drivers.**

The **AMD** and **Intel** generations from **10 years ago to now** are **specially optimized** to get the most out of their **performance** doing:
  ```
  -Enabling their specific drivers.
    
  -Unlocking the maximum frequency.
    
  -Changing the performance type from economy to performance (that's how it works in distributions Debian, such as Debian itself or Ubuntu)
  ```

Also this **kernel** have been **specially optimized** for **Strondimus-OS** and have been activated all the **security options**, eliminating the most of **kernel-vulerabilityes.**

## Installation

**If you want to install it** what you have to do is download the [_linux-Vodka-*.tar.gz_](https://github.com/Acfio/Linux-Vodka/releases) and **untar it** doing:
    
    tar -xzvf linux-5.15.64-Vodka-Beta.tar.gz
(Is only a example of the version)

After it you have to **enter** to the new directory and **install the firmware** and the **kernel** doing:

    sudo make modules_install
    sudo make install

And we **reboot** with the new **kernel** redy.

    reboot
