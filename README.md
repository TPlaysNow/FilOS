# FilOS🍇 Version 0.01

The Friendly Python OS.

Discord: https://discord.gg/pWtDgDTDMa

## Installation

Download all of the files for the 'src' directory from this repo or clone the repo directly to your own system (it should automatically create the FilOS/root/src directories for you):

```bash
git clone https://github.com/tassopsaltakis/FilOS.git
```

## Usage
Create this file structure for the FilOS folder. Your folder should replicate this structure.
```File Structure
FilOS/                       #FilOS Folder
│                      
└── root/
    ├── home/                # User home directories
    │   └── [user1]/         # Your user directory will automatically be created upon user creation
    │
    ├── tmp/                 # Temporary files
    │
    ├── src/                 # Source code for the OS
    │   ├── shell.py
    │   ├── commands.py
    │   ├── user_management.py
    │   ├── login.py
    │   └── ...              # Other Python files and utilities
    │
    ├── logs/                # Logs generated by the OS
    │
    └── misc/                # Miscellaneous application data and system hashes
        └── hashes/          # Directory for user data hashes

```
Once this is complete, open your terminal and type:
```bash
 cd FilOS/root/src/
 python3 shell.py
```
You will be prompted with the login for FilOS! Enjoy!
## Contributing

Pull requests are welcome. Join the discord (I would really appreciate any advice): https://discord.gg/pWtDgDTDMa

Please make sure to update tests as appropriate.
