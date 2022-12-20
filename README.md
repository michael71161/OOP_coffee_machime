# OOP Coffee Machine  Programm 
*******************************************************
Done with  Python using the object oriented programming paradigm 
*******************************************************
Coffee Machine that able to prepere different type of drinks which 
requires different resources. Machine accepts coins and return coins 
Maintanance mode available, Report (profit resoueces available)

### Features :
- Can make 3 different types of drinks, each drink 
   requires different resources 
- Resources: Machine have 3 types of resources:
   water , milk, coffee - each drink will reduce resources
- Machine accepting Shekel coins and returns change 
- Machine have maintanance mode: while on menu type "off"
   to make machine unavailable 
- Report Sheet: You can type "report" while on menu,
   it will generate a list with resources left and profit done by machine 

### Files Structure:
- coffee_maker.py : containes CoffeeMaker class.
 has init function with the resources of the machine and with the following functiones: 
 report - Prints a report of all resources
 is_resource_sufficient- Returns True when order can be made, False if ingredients are insufficient
 make_coffee- Deducts the required ingredients from the resources
 - menu.py : classes- 
   class MenuItem- Models each Menu Item
   class Menu- Models the Menu with drinks
   functiones- 
   get_items- Returns all the names of the available menu items
   find_drink- Searches the menu for a particular drink by name. Returns that item if it exists, otherwise returns None
- MoneyMachine.py: containes all money related        operationes 
  clasees : 
  class MoneyMachine- havs as a initials currency and coin values which are our constant variables 
  on the init function we will have the changebale varaibles : profit , money_recieved 
  functiones: 
  report- Prints the current profit
  process_coins- Returns the total calculated from coins inserted
  make_payment- Returns True when payment is accepted, or False if insufficient
- main.py :
  our main file which contain the programm that we are going to run , we will import all our classes from all other files to this main file 

  

          
