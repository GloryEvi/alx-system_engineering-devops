
# ALX System Engineering & DevOps

## 0x0B-ssh

This directory is related to SSH (Secure Shell) connections and server management.


#### 0. Use a private key
**File:** `0-use_a_private_key`

A Bash script that uses SSH to connect to a server using a private key for authentication.

**Requirements:**
- Uses SSH with single-character flags only
- Connects using private key `~/.ssh/school`
- Connects as user `ubuntu`
- Does not use the `-l` flag

**Usage:**
```bash
./0-use_a_private_key





# 0x0C Web Server

This directory contains Bash scripts for web server configuration and file transfer.

## Scripts

### 0-transfer_file
Transfers a file from client to server using scp.

**Usage:** `./0-transfer_file PATH_TO_FILE IP USERNAME PATH_TO_SSH_KEY`

**Requirements:**
- Accepts 4 parameters: file path, server IP, username, SSH private key path
- Transfers file to user home directory (~/)
- Disables strict host key checking
- Shows usage message if less than 4 parameters provided