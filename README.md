# Lab02 Embedded Systems Engineering

Name: Emmett
Student ID: R00222357

## Project Setup
This project must be run in linux environment. The project is setup to run in WSL2 Ubuntu 22.04.

### Machine Setup
```bash
sudo apt update
sudo apt install qemu-system-arm
sudo apt install build-essential
sudo apt-get install gcc-arm-none-eabi
sudo apt-get install libgtk-3-dev
sudo apt-get install dos2unix
```

[//]: # (### Run Project Windows)

[//]: # (```bash)

[//]: # (cd defender-lab/defender-lab)

[//]: # (dos2unix mk)

[//]: # (./mk)

[//]: # (```)

### Run Project Linux
```bash
cd defender-lab/defender-lab
chmod +x mk
./mk
```