# Parsons D12 Machine Learning Guide
This repository is a guide to the Machine Learning computer on D12 (6E 16th St) at Parsons School of Design.


# Getting Started

## Do I need to use this computer?
- The computer is for Machine Learning (ML) applications only. Do not mine bitcoin.
- If you're learning about ML and doing tutorials, chances are you will not need the computer. If you really need it, use it.

## How can I use it?
To use the computer, you need an account. Please find me on D12 or email me (pschmitt at newschool) to get one. If you're in the Parsons Data Vis ML class, there is a class account prepared for you with all necessary software pre-installed.

To access the computer you will either need to ask a faculty member for access to the room or use SSH. Through SSH, you can access the computer from anywhere on campus.

### SSH Access
```bash

# STEP 1
# in the terminal connect via ssh:
ssh <user>@149.xx.xxx.xxx

# STEP 2
# navigate to your project directory
# open jupyter notebook on a vacant port:
jupyter notebook --ip=149.xx.xxx.xxx --port=80xx

# STEP3
# copy the jupyter url from the terminal into your browser. Done!

# OPTIONAL
# You can run Jupyter in the background by adding an & symbol to the start command
# This allows you to keep jupyter open while running other commands
jupyter notebook --ip=149.xx.xxx.xxx --port=80xx &

# If you use this, you need to manually stop the jupyter server after you're done working:
# replace the port number with what you selected when starting the server
jupyter notebook stop 80xx

# Check if there's still a server running:
jupyter notebook list

# if it won't stop for some reason, kill the jupyter process:
kill $(pgrep jupyter)

```

### Copy files from/to the computer via SSH

```

scp [-r] /local/path <user>@149.xx.xxx.xxx:/remote/path

```


# System Specs
- Intel Core i7-8700 3.2 GHz 6-Core LGA 1151 Processor
- ASUS Republic of Gamers Strix Z370-E Gaming LGA1151 ATX Motherboard
- Ballistix 32GB Ballistix Sport DDR4 2400 MHz UDIMM Memory Module Kit (2 x 16GB, White)
- NZXT S340 Mid-Tower Chassis
- EVGA SuperNOVA 850G2 850W Power Supply
- Samsung 500GB 960 EVO NVMe M.2 Internal SSD
- Seagate 4TB Barracuda SATA III 3.5" Internal HDD 
- Asus 1080 Ti 12GB GPU
