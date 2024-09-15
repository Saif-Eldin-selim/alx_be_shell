root@11c4d61afea1:/# mkdir -p shell_permissions
root@11c4d61afea1:/# chown betty:betty shell_permissions
root@11c4d61afea1:/# su betty
$ cd shell_permissions
$ echo "su betty" > 0-iam_betty
$ chmod +x 0-iam_betty
