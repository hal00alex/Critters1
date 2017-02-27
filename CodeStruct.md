## King/Main/Viewing/Outputing Class 
  - quit
  - show
  - step
  - add algae
  - make
  - stats
  
## Critter Abstract Class 
  - fight which calls walk and/or run 
  - walk 
  - run 
  
## Algae extends Critter
  - plant_food
  - seed
  - appear (added every TimeStep)
  
## TestCritter extends Critter 
  - babies
  
## Model/Given Code
  - start_energy 
  - walk_energy_cost 
  - run_energy_cost 
  - rest_energy_cost
  - min_reproduce_energy  
  - plant_food 
  - refresh
  
## Stage 1 
  - makeCritter acts as constructor with random starting position for all types of critters
  - worldTimeStep acts a trigger for doTimeStep 
  - doTimeStep is included in all critters and they walk, run, or fight
  - view via displayWorld which creats ASCII art
  - create quit, show, and step 
  
## Stage 2 
  - doTimeStep advances to include babies and death/deletion
  - doTimeStep now adds a cost/toll to actions from Stage 1 
  - each critter gets to respond to a battle cry with A.fight(B.toString())
  - fighting needs to update energy and roll a dice 
  - dice is a getRandomInt function
  - having babies takes energy and needs an instruction 
  - add seed
  
## Stage 3
  - made a toll for each additional movement 
  - fight calls run and/or walk
  - make fight able to handle 3+ critters
  - add make and stats 
  
## Errors 
  - last item to add 
  - Invalid Critter for inputs 

  
