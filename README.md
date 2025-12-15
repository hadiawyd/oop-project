This project is for our Object-Oriented-Programming class.
It is an Automated Parking Management System in C++ and uses concepts like inheritance,
polymorphism, and dynamic memory allocation.

## What This Program Can Do
- Park different types of vehicles
- Manage separate parking zones:
  - Normal
  - EV (Electric Vehicles)
  - Truck
- Automatically reduce available slots when a vehicle is parked
- Increase slots again when a vehicle exits
- Show a warning when the garage is full
- Calculate parking bills based on vehicle type and hours parked
- Billing is effected by charging consumed for EV's
- Display the current garage status
- Validate plate numbers and arrival time input
- 
## Vehicle Types Supported
- Car  
- Electric Car  
- Truck  
- Rickshaw  
- Motorbike  
  - Normal Bike  
  - Heavy Bike  
Each vehicle has its own parking fee and slot requirement.

## Input Sequne is given below

-First enter the number of slots available for each zone(Normal,EV,Truck)
-Input Plate Number: Plate number must be in the format:
   ABC-123
   If the format is incorrect, the program will ask again.
-Arrival Time: Arrival time must be entered in the format:
   HH:MM AM/PM

-As soon as all this input is given the vehicle gets parked.

## How Parking Works

- The user first enters how many slots are available in each zone.
- When a vehicle is parked:
  - Available slots decrease automatically.
  - The vehicle is stored in the system.
- If no slots are available:
  - The vehicle is added to a waiting queue.
  - A warning message is displayed.
    
## Billing System

- Car: Rs. 200 per hour  
- Electric Car: Rs. 200 per hour (+ charging cost)  
- Truck: Rs. 350 per hour  
- Rickshaw: Rs. 170 per hour  
- Normal Bike: Rs. 100 per hour  
- Heavy Bike: Rs. 150 per hour  

## How Exit Works

- The user enters the vehicle plate number and hours parked.
- The program calculates the bill.
- The parking slot is freed.
- If a vehicle is waiting, it is parked automatically.

## Project Done By

-Hadia Sajid (31687)
-Ayesha Alam (30846)
