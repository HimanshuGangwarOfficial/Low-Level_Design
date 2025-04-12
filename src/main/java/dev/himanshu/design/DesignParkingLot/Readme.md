# Parking Lot Design

## Requirements:
1. Big Parking lot : 10k-20k size
2. Multiple Entrances : 4 Entry and 4 Exit
3. Ticket & Spot allocated at entrance
4. Parking spot should be the nearest to entrance
5. Limit/ Capacity : 30K
6. Type of Parking lot: Handicap, Compact, Large, Two wheelers
7. Hourly rate
8. Payment type: Cash, Card
9. Monitoring System

## Objects:

1. Parking Lot System
2. Entry/ Exit terminals: Printers, Payment Processors
3. Parking Spot
4. Ticket
5. Database
6. Monitoring Systems

## Lets Design

ParkingSpot(I) : id, reserved

HandicapParkingSpot implements ParkingSpot
CompactVehicleParkingSpot implements ParkingSpot
LargeVehicleParkingSpot implements ParkingSpot
TwoWheelerParkingSpot implements ParkingSpot

Note: We should have added parking spot types in an enum, but that approach violates Open/Close Principle.



