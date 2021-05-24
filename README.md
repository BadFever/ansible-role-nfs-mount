# ansible-role-nfs-mount

An Ansible Role installs and configures NFS mounts on Linux systems.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see defaults/main.yml):

```yml
nfs_mount_points:
  - mount_point: "/nfs"
    nfs_export: "1.1.111.71:/var/nfs"
```

Set exported directories

## Dependencies

None.
