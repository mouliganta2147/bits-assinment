# Question 2 Explanation

- `mkdir` created the secure workspace structure for documentation, source, and log files.
- `touch` created sample project files so the permission changes could be observed on real files.
- `chmod` changed directory and file permissions to `750` and `640`, limiting access to the owner and group.
- `stat` and `ls -l` showed the resulting ownership and permission details after the changes.
- `umask` confirmed the default permission mask, and the permissions help protect project data from unauthorized access.
