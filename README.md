# Intelligentvehicleparking
Design a Intelligent parking lot using Python 

## Description

It creates parking lot with given number of slots. The cars follow Greedy approach while being parked in the slots.

ParkingLot.py
 
# functions -

1. `create_parking_lot n` = Given n number of slots, create a parking lot
2. `park car_regno car_color` = Parks a vehicle with given registration number and color in the nearest empty slot possible. 
                                If there are no more empty slots available, it shows a message "Sorry, parking lot is full".
3. `status` =  Prints the slot number, registration number and color of the parked vehicles.
4. `leave x` =  Removes vehicle from slot number x
5. 'slot_numbers_for_cars_with_color' = slot number from colour of car.
5. 'slot_number_for_registration_number' = slot number from registration number of car.
6. 'registration_numbers_for_cars_with_colour' = get registration numbers of cars with particular color.

ParkingLot.py can be run through shell or through file containing test cases. An example file `run_test_case.txt` has been provided in repo.

I have followed TDD approach while designing this. `test_parking_lot.py` uses `unittest` module of python. Here 6 test cases are written in order to test each functionality mentioned in ParkingLot.py

Vehicle.py is a separate class where we can define the type of vehicles that can be parked. As of now, it only contains class `Car`

## Setup

To create your own ParkingLot - 


1. Run `python ParkingLot.py` to run without input test case file. This opens a shell where you can write your commands 

  
  
1. To run with a file execute `python ParkingLot.py -f run_test_case.txt. 
   Run test cases.
  
  
3. You can also run the test cases separately as `python test_parking_lot.py`. 
   This runs the 6 test cases written in file. This is very useful when you want to create your own function and test it simultaneously.


