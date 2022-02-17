# Remote Forensics
A remote forensic tools for Linux distributions.

## Todo  
- Create a program(client/agent) which will run on the target machine to collect forensic data
- Create a program(server) which allow communication between the agent

### Agent  
- Runs on the target system with sudo / root privileges
- Collects preliminary information regarding the target (about the device info[name, ip, mac, time, disks, ram, etc.])
- Collects artifacts with forensic value
- Monitor specific process & files
- Executes a command given by server on target and returns the output of the command back to the server


### Server
- Manages communication between agents
- Stores data collected from agents centrally 
- Mange Agents & collected data
