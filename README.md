
# (Tool 1) : IH – Installation History Tracker for Linux

### Description : 
IH (Installation History) is a lightweight .deb package that provides detailed insights into the software installation and uninstallation history on Linux systems. It allows users, sysadmins, and developers to track the lifecycle of packages with precision and ease.

### Installation : 
```bash
sudo dpkg -i ih.deb
```

Note: To view the manual and all available commands, run:

```bash
ih --help
# or
ih -h
```

---

### Key Features

- **Track Installations & Uninstallations**
	- View which packages were installed or removed on a specific day (today, yesterday, or any custom date).
	- Monitor activity over a date range.
	  <br>

- **Duration Analysis**
	- Automatically calculate the time a package remained installed before it was removed.
	- Identify short-lived installations or frequently reinstalled packages.
	  <br>
- **Detailed Reports**
	- Generate concise and easy-to-read reports of installation history.
	- Supports filtering by package name, date, or time range.
	  <br>
- **Lightweight & Easy to Use**
	- Minimal system overhead, no complex dependencies.
	- Installable via a .deb package for quick setup.
	<br>
- **Use Cases**
	- System auditing and monitoring
	- Debugging package conflicts
	- Personal or organizational software management



------------------------------------------------------------------------------------------------------------------------------------------


