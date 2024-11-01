# tutorial-simple-example

## 0. Setting up environment
### a. codespace
![image](https://github.com/user-attachments/assets/48188311-9447-4861-8aed-27f606beb8e8)

### b. devcontainer (require docker to be installed on your laptop/pc)
- https://code.visualstudio.com/docs/devcontainers/tutorial

### c. Virtual Machine (if you're on macOS or Windows)
Some eBPF program may not work inside the container, therefore you may want to setup a virtual machine:

## 1. Running the eBPF program

```bash
make run <The name of your app>
```

e.g. If we're running the `minimal` eBPF program, the command would be:
```bash
make run minimal
```

## 2. Utility shortcut

```bash
make trace
```

This shortcut is equivalent to the following command:
```bash
bpftool prog trace log
```
