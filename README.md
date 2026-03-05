# bootit
A lightweight next boot selector

## What is Bootit?
Bootit is basically a CLI tool that makes your PC reboot to specific OS for one time.
```bash
sudo bootit scan # list IDs of bootable entries

sudo bootit alias add windows 1
sudo bootit alias add archlinux 2
```
Then, reboot to it with
```bash
sudo it windows
```
or
```bash
sudo it 2
```
or whatever. It does not change boot order.

## Installation
### Cargo
```bash
cargo install bootit
```

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests on the GitHub repository
