# labyrinth
An extremely simple random-maze-generated game made using C++ with SDL2.0 library.

## Game details
  ### Gameplay
    You find yourself trapped in a maze, there is only one way out through a secret door.
    You'll encounter through your journey to freedom dangerous viruses that will worsen your health.
      The Weak Virus:
        Once encountered, this virus will reduce your hp by one.
      Covid-19 Virus:
        Once encountered, this virus will reduce your hp by 3.
        A 60 seconds timer will be set-up. You should find a disinfectant gel ASAP!
    Fortunatly, there are hepfull stuff on the way. Potions can restore your health. If you encounter one,
    your hp will be boosted by 1.
    Disinfectant gels can save you against Covid-19 viruses. Though these will not increase your hp!
    
    
  ### Features
   - user can provide the size of the maze
   - each round the maze is randomly generated
   - you can access any case in the maze as long as it is not a wall
   - user chooses the initial position and direction of the player
   - user chooses the initial position of the viruses and the health potions
   - user chooses the position of the exit point
    
## What this game lacks
  - sounds
  - proper menu
  - interesting gameplay
  - character choice
  - flexible animations
  - dynamic environment
  - proper crossplatform support

## How to install
    - install SDL2.0 (see official webpage for the how-to)
    - run these commands in root directory:
        make
        ./game
        
## License
  You are free to do whatever you like with the source files!
