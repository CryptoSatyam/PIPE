# Dependencies for & LINUX & VPS
```
sudo apt update
sudo apt upgrade -y
```

# install screen 
```
sudo apt install screen -y
```
# Create Screen And Run Next All Commands in New Screen 
```
screen -S pipe
```

# Install
```
curl -L -o pop "https://dl.pipecdn.app/v0.2.8/pop"

```

#
```
chmod +x pop
```
# Make Directory

```
mkdir download_cache
```

# Sign-up With Command

```
./pop --signup-by-referral-route ebad1db832e2a0e
```

# Start The Node

```
sudo ./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <KEY>
```
🚩 Note: Put your `ram` , `disk` & `pubkey` with your actual Information.Retrieve the public key from your Solana wallet (e.g., Phantom, Backpack) & Replace in `<KEY>` by Solana Address

🚩**& Also Don't forget to Remove < >**



# Install Nano For Running Next Command 

```
sudo apt update && sudo apt install nano -y
```



# Save the file (Very Important)  (Open a different WSL window or Ubuntu for this) First install nano then run below command 

```
nano ~/node_info.json
```
**Ctrl+x to Exit**

# Node Status

```
./pop --status
```

# Check points

```
./pop --points
```

# Generate referral

```
./pop --gen-referral-route
```

# Quick Start

```
./pop
```

Docs- https://docs.pipe.network/devnet-2

Check Points & Status From Dashboard -: https://dashboard.pipenetwork.com/node-lookup

## Need to Free Your 8003 Port

### Identify the Process Using Port 8003
```
sudo ss -tulpn | grep 8003
```

### Terminate the Process by PID
```
sudo kill -9 1234
```

### Kill All Processes Using Port 8003
```
sudo fuser -k 8003/tcp
```

# Thank you for Visiting

