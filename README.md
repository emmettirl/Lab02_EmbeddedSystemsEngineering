# Lab02 Embedded Systems Engineering

Name: Emmett
Student ID: R00222357

## Project Description
All changes were added to the t.c file. 

Firstly in part A, I added code to main function, in the switch case to handle user input.
This also ensures the user sprite does not move out of bounds.

In part B, I modified the Draw_all function, to change the sprite displayed based on the direction of the user input.

In part C, I added the projectile, with a check for out of bounds, and a check for collision with the enemy sprite. I also modified the enemey movement, so it resets to 0 when going out of bounds, which ensures the coordinates match the visual position. 
Upon collsion, both sprites are removed. 

### Machine Setup
```bash
sudo apt update
sudo apt install qemu-system-arm
sudo apt install build-essential
sudo apt-get install gcc-arm-none-eabi
sudo apt-get install libgtk-3-dev
```

### Run Project
```bash
cd defender-lab/defender-lab
chmod +x mk
./mk
```