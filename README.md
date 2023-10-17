# Radio-Extension-Board
KiCad PCB design files 

<img width="219" alt="image" src="https://github.com/alexrcherry/Radio-Extension-Board/assets/112339626/42429340-3357-403f-ba91-c02e0f62e17d">

## Purpose
The purpose of this board is to transmit data to the ground station and also to determine altitude. Recovery on liquid rockets does not have a good track record so it is good to get max altitude data back to the ground without requiring the recovery to work. The radio chip used for this board also has the ability to do ranging. With multiple ground stations spaced apart, a primitive form of GPS can be used to determine the position and altitude of the rocket. This may be the primary form of altitude determination for the spaceshot since GPS cuts out at 80km. Accelerometer integration may be used in conjunction with or instead of the radio ranging. 

## Key ICs
STM32G4A1KEU6  
SX1280  
MCP2557FD  
