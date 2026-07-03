# Question 3 Explanation

- `echo` created the original test file, and `ln` created a hard link while `ln -s` created a symbolic link.
- `ls -li` and `stat` displayed inode numbers and metadata, showing that the hard link shared the same inode as the original file.
- `cat` confirmed that both links read the same content before the original file was removed.
- Removing the original file left the hard link working, but the symbolic link became broken because it points to a path that no longer exists.
- This experiment showed the functional difference between hard links and symbolic links in Linux.
