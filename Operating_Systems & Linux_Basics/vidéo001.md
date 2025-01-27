## Title of video : Introduction to Operating Systems

Goals :
What's an OS ?
How it's constructed ?
How OS differ from each other ?

<hr>

### What's an OS ?
An operating system (OS) is the intermediary between computer hardware and software applications. A computer consists of hardware components like the CPU, memory, storage, and input/output devices (e.g., screen, mouse, keyboard). Applications running on the computer need to interact with these hardware resources, but they don’t directly know how to do so.

For instance, if you use a browser like Google Chrome, it needs access to the CPU and memory, and it must process input from the mouse and keyboard while displaying information on the screen. However, Chrome itself doesn't include the code to interact with each hardware component directly, as that would be inefficient. Every application would need to replicate this complex task if no intermediary existed.

The operating system handles this complexity. It serves as a "middleman" that allows applications to request hardware resources and ensures proper interaction with the hardware. For example, when Chrome requests memory, the OS manages the allocation. If you click the mouse to start Chrome, the OS interprets this action, starts the application, and allocates CPU and memory as needed.

Additionally, the OS ensures fair resource management between applications. If Chrome is using too many resources but hasn’t been active, and you open another application like Safari, the OS reallocates resources to ensure smooth functioning. It also isolates applications to prevent interference between them, maintaining stability and security.

In short, the operating system:

1. Manages hardware resources and allocates them to applications.
2. Provides a consistent interface for applications to interact with hardware.
3. Balances resource usage and ensures efficient operation across multiple programs.

