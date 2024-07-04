# Packages and package managers
Both _software updates and software installation files_ for Linux OS are distributed in files known as **packages**.

**Packages:**
* Archive files
* For installing new software or updating existing software

**Package managers:**
* Manage the download and installation of packages
* Available for different Linux distros
* Can be GUI-based or command-line tools

# Deb and RPM packages
**Deb and RPM packages** are used by _package managers in Linux OS_. They are _distinct file types_ containing software or updates for differnt Linux OS.
* **deb files:**
  * For **Debian-based** distributions such as Debian, Ubuntu, and Mint
  * deb stands for _Debian_
* **rpm files:**
  * For **Red Hat-based** distributions such as CentOS/RHEL, Fedora, and openSUSE
  * RPM stands for _Red Hat Package Manager_

deb and RPM _formats are equicalent_. If a package is only avaiable in one format, you can use **alien** to convert it:
* RPM to deb:
  ```
  alien <package-name>.rpm
  ```
* deb to RPM:
  ```
  alien -r <package-name>.deb
  ```
# Updating deb-based Linux
## Command line: apt
**apt** is a command-line tool for updating deb-based Linux systems.

We use the `sudo apt update` command to find avaiable packages for your distro.

To upgrade all installed packages on a system, use the `sudo apt upgrade` command.
