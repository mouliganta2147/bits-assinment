# Question 5 Explanation

- `lsblk` showed the available storage devices and their partition layout.
- `mount` and `df -h` displayed the mounted file systems and the current disk usage across the environment.
- `df -i` reported inode usage, which helps reveal whether the system may run out of file entries rather than raw disk space.
- The findings suggest monitoring disk growth, removing old logs, and archiving unused data to improve storage efficiency.
