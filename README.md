# Linux APT

> 아파트! uh-huh uh-huh

APT (Advanced Package Tool) is a Debian-based package manager.
It's primarily used in `Debian` and its derivatives, such as
`Ubuntu`, `Linux Mint`, and `Pop!_OS`, to manage software packages.

## Package Search

```bash
apt search <keyword>
apt show <package-name>
# For offline result
apt-cache search <keyword>
```

## PPA Packages

PPA (Personal Package Archive) is a software repository specifically designed for
Ubuntu and other Debian-based systems that use the APT package management system.
It allows users and developers to distribute their software and updates more easily.

### Adding PPA

Adding The Mobile Robot Programming Toolkit (MRPT) PPA.

```bash
sudo add-apt-repository ppa:joseluisblancoc/mrpt-stable
```

### Removing PPA

```bash
sudo add-apt-repository --remove ppa:joseluisblancoc/mrpt-stable
```

ref: https://askubuntu.com/questions/307/how-can-ppas-be-removed
