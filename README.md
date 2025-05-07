<h1 align="center">
  <img src="https://r2.e-z.host/049cab41-5ed3-4a5c-a42f-5b83b721f333/re5pq23l.png" alt="Header Image" style="width:30%; max-width:600px;"/>
</h1>

# Banana 🍌

**A free and better alternative to MCPTool**

---

## 📦 Installation

### Requirements

* Python 3.10+
* Winget package manager (Windows only)

### Setup

```bash
git clone https://github.com/Renovsk/Banana.git && cd Banana
pip install -r requirements.txt
python main.py
```

> On first launch, install command line developer tools if prompted.

---

## ⚙️ Features

### Commands

| Command    | Arguments                               | Description                                                                  |
| ---------- | --------------------------------------- | ---------------------------------------------------------------------------- |
| `server`   | `<address>`                             | Shows information about the server                                           |
| `uuid`     | `<ign>`                                 | Shows player's UUID                                                          |
| `ipinfo`   | `<ip>`                                  | Shows information about the given IP                                         |
| `monitor`  | `<ip>`                                  | Monitors who leaves and joins on a specified server (if queries are enabled) |
| `dns`      | `<domain>`                              | Shows all DNS records of the domain                                          |
| `target`   | `<domain>`                              | Shows all subdomains with their resolved IPs                                 |
| `proxy`    | `<ip> <mode>`                           | Starts a local Velocity proxy server that redirects to the specified server  |
| `check`    | `<file>`                                | Checks the status of Minecraft servers listed in a specified text file       |
| `scan`     | `<ip> <range> <threads>`                | Scans for online Minecraft servers in a given IP range                       |
| `clear`    | N/A                                     | Clears the screen                                                            |
| `ogmur`    | `<users_file> <server> <commands_file>` | Sends a bot that will execute a list of commands from a file                 |
| `update`   | N/A                                     | Re-initializes Banana                                                        |
| `kick`     | `<username> <server>`                   | Kicks a player from the server (if cracked)                                  |
| `shell`    | `<port>`                                | Uses netcat to listen to a port                                              |
| `connect`  | `<username> <server>`                   | Joins with a bot and allows you to send messages                             |
| `rcon`     | `<server> <password>`                   | Connects to a server's RCON                                                  |
| `brutrcon` | `<server> <file>`                       | Attempts to brute-force RCON using a password file                           |
| `fuzz`     | `<website> <file> <threads>`            | URL fuzzing: e.g., `example.com/FUZZ` or `FUZZ.example.com`                  |
| `sendcmd`  | `<username> <server> <file>`            | Sends a bot that executes commands from a file                               |
| `exit`     | N/A                                     | Exits Banana                                                                 |

> More commands coming soon!

---

## 👉 Credits

* Made by `@x5ten` on Discord
