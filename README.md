# Assignment1
Done — I created a single code document named Ahmed Char Device Dynamic Circular Queue that contains:

Kernel module ahmed_queue.c (creates /dev/ahmed, supports SET_SIZE_OF_QUEUE, PUSH_DATA, POP_DATA; blocking behavior with wait queues)

include/ahmed_ioctl.h (shared IOCTL definitions + struct)

Makefile to build the module

Userspace examples: userspace/configurator.c, userspace/filler.c, userspace/reader.c

README.md with build & usage instructions

You can view and copy the full code and instructions from the canvas document titled Ahmed Char Device Dynamic Circular Queue. If you want, I can:

Extract individual files to a zip you can download, or

Walk you through building, loading, and testing the module step-by-step, or

Adjust any behavior (e.g., non-blocking mode, signal handling, resizing policy, different device name).
