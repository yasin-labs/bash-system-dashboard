# System Dashboard

A lightweight command-line dashboard written in Bash for displaying essential Linux system information.

---

## Features

- System information
- Kernel version
- Hostname
- Disk usage
- Memory usage
- CPU load
- Uptime
- Logged-in users
- Interactive menu

---

## Requirements

- Bash 3+
- Linux (or WSL)

---

## Usage

Run the script:

```bash
chmod +x system-dashboard.sh
./system-dashboard.sh
```

---

## Example

```text
=============================
      System Dashboard
=============================

1) System Information
2) Disk Usage
3) Memory Usage
4) CPU Usage
5) Uptime
6) Logged-in Users
7) Exit

Choose an option:
```

---

## Project Structure

```text
system-dashboard/
├── system-dashboard.sh
├── README.md
└── LICENSE
```

---

## Commands Used

- `uname`
- `hostname`
- `df`
- `free`
- `uptime`
- `who`
- `ip`
- `lscpu`

---

## Future Improvements

- Display CPU temperature
- Colored terminal output
- Refresh mode (live monitoring)
- Export report to a text file
- Show network interfaces
- Display top memory-consuming processes

---

## License

This project is licensed under the MIT License.
See the LICENSE file for details.
