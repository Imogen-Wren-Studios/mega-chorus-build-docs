# PGFX_MegaChorus V1.0
Build Documents for Pan Galactic FX Mega Chorus

Please find BOM at the bottom of this document.

![image](https://user-images.githubusercontent.com/53580358/205485727-40fc8b8e-c4ad-4a11-8edd-47d804779c71.png)


## Build Notes: 

**Please read the entire document before commencing build.**

_We Recommend starting with the smallest components first, the resistors and diodes, before moving onto
sockets for the ICs, caps and transistors. Check the polarity of diodes and Electrolytic caps!_

### NOTES REGARDING BBD CHIP SELECTION
_This PCB can be used with MN3007 BBDs which can work with up to a 15v supply, though we recommend
using 12v at the maximum, or it can be configured to work with MN3207/8 BBDs which can only work up
to an 8v supply, for which a space for a voltage regulator is provided._

#### To configure the board for MN3007:
- Connect BBDPwr to Vreg - Shown with Orange <br>
if following the MegaChorus Schematic: <br>
- Connect BBD VDD to Vb – Shown with Yellow 
Or, Alternatively the Boss CE 2 Schematic shows:
- BBD VDD to GND – Shown in Blue (Experimental) 

*For MN3007* - *R16A1* Should be installed, *R16B1* Should be omitted.

If using *MN3007*
– You Must use MN3101 Clock
If *MN3007* is used
- 8v Regulator does not
need to be installed, but RR1 is required instead

![image](https://user-images.githubusercontent.com/53580358/205697090-64366a96-3f7d-46fe-be82-11de7e7c8f5e.png)






## BOM


| No. | Ref       |  Value        | Type                  | Notes          |   
|---  | --------- | ------------- | --------------------- | -------------- | 
| 1 | R1        | 10k           | Resistor              |                |  
| 2 | R2        | 47k           | Resistor              |                | 
| 3 | R3        | 12k           | Resistor              |                |  
| 4 | R4        | 12k           | Resistor              |                |     
| 5 | R5        | 47k           | Resistor              |                |   
| 6 | R6        | 10k           | Resistor              |                |          
| 7 | R7        | 1k            | Resistor              |                |           
| 8 | R8        | 12k           | Resistor              |                |         
| 9 | R9        | 47k           | Resistor              |                |            
| 10 | R10       | 10k           | Resistor              |                |         
| 11 | R11       | 1M            | Resistor              |                |             
| 12 | R12       | 1M            | Resistor              |                |             
| 13 | R13       | 10k           | Resistor              |                |            
| 14 | R14       | 10k           | Resistor              |                |        
| 15 | R15       | 10k           | Resistor              |                |            
| 16 | R16       | 10k           | Resistor              |                |             
| 17 | R17       | 10k           | Resistor              |                |
| 18 | R18       | 100k          | Resistor              |                |         
| 19 | R19       | 10k           | Resistor              |                |        
| 20 | R16A1     | 56k           | Resistor              | Only   Install for     MN3007          |     
| 21 | R16B1     | 56k           | Resistor              | Only           Install    for       MN3207/8    |
| 22 | R20       | 10k           | Resistor              |              
| 23 | R21       | 12k           | Resistor              |               
| 24 | R22       | 10k           | Resistor              |              
| 25 | R23       | 390r          | Resistor              |                |
| 26 | R24       | 330k          | Resistor              |                |     
| 27 | R25       | 4k7           | Resistor              |                |         
| 28 | R26       | 10k           | Resistor              |                |            
| 29 | R27       | 100k          | Resistor              |                |              
| 30 | R28       | 10k           | Resistor              |                |              
| 31 | R29       | 330k          | Resistor              |                |            
| 32 | R30       | 10k           | Resistor              |                |          
| 33 | R31       | CLR           | Resistor              |                |           
| 34 | R32       | 470r          | Resistor              |                |            
| 35 | RR1       | 33r           | Resistor              | Install       this          if            using       MN3007      |       
| 36 | and       | NOT           | installing            | the            voltage      regulator                
|    |         |                |                         |All  The   ollowing  Resitors  are   part      of      the   Clock/LFO  Circuit   | 
| 37 | CR1       | 100k          | Resistor              |                |           
| 38 | CR2       | CLR           | Resistor              |                |            
| 39 | CR3       | CLR           | Resistor              |                |            
| 40 | CR4       | 2k7           | Resistor              |                |             
| 41 | CR5       | 33k           | Resistor              |                |            
| 42 | CR6       | CLR(2k2)      | Resistor               2k2            indicated    on           original    schematic   |          
| 43 | CR7       | 10k           | Resistor              |                |       
| 44 | CR8       | 10k           | Resistor              |                |          
| 45 | CR9       | 10k           | Resistor              |                |            
| 46 | CR10      | 10k           | Resistor              |                |          
| 47 | CR11      | 10k           | Resistor              |                |             
| 48 | CR12      | 33k           | Resistor              |                |            
| 49 |           |               |                       |                |             
| 50 | CR13      | 68k           | Resistor              | See            | NOTES        | regarding    | Sine        | Trim        | Trimpot   |        
| 51 | CR14      | 33k           | Resistor              |                |            
| 52 | CR15      | 47k           | Resistor              |                |          
| 53 | CR16      | 390r          | Resistor              |                |            
| 54 | CR17      | 470k          | Resistor              |                |           
| 55 | CR18      | 10k           | Resistor              |                |             
| 56 | CR19      | 10k           | Resistor              |                |           
| 57 | CR20      | 6k8           | Resistor              |                |            
| 58 | CR21      | 6k8           | Resistor              |                |           
| 59 | CR22      | 10k           | Resistor              |                |           
| 60 | CR23      | 4k7           | Resistor              |                |           
| 61 | CR24      | 1k            | Resistor              |                |            
| 62 | CR25      | 10k           | Resistor              |                |             
| 63 | CR26      | 4k7           | Resistor              |                |            
| 64 | CR27      | 4k7           | Resistor              |                |             
| 65 | CR28      | 10k           | Resistor              |                |            
| 66 | C1        | 6n8           | FilmCapacitor         |                |            
| 67 | C2        | 1n            | FilmCapacitor         |                |            
| 68 | C3        | 47n           | FilmCapacitor         |                |      
| 69 | C4        | 8n2           | FilmCapacitor         |                |     
| 71| C5        | 1u            | FilmCapacitor         |                |          
| 72 | C6        | 47n           | FilmCapacitor         |                |           
| 73 | C7        | 6n8           | FilmCapacitor         |                |          
| 74 | C8        | 3n3           | FilmCapacitor         |                |           
| 75 | C9        | 8n2           | FilmCapacitor         |                |             
| 76 | C10       | 470p          | FilmCapacitor         |                |          
| 77 | C11       | 47n           | FilmCapacitor         |                |        
| 78 | C12       | 1u            | FilmCapacitor         |                |          
| 79 | C13       | 47n           | FilmCapacitor         |                |          
| 80 | C14       | 8n2           | FilmCapacitor         |                |             
| 81 | C15       | 1n            | FilmCapacitor         |                |              
| 82 | C16       | 1u            | FilmCapacitor         |                |             
| 83 | EC1       | 10u           | ElectrolyticCapacitor |                |            
| 84 | EC2       | 220u          | ElectrolyticCapacitor |                |            
| 85 | EC3       | 100u          | ElectrolyticCapacitor |                |        
| 86 | EC4       | 10u           | ElectrolyticCapacitor |                |             
|    |            |               |                       | The following  aps  all      makup       part   of     the   clock/LFO  circuit |    
| 87 | CC1       | 47p           | FilmCapacitor         | Depth  Mod  can  be  increased.   150p     Highest  Tested   |       
| 88 | CC2       | 470n          | FilmCapacitor         |                |             
| 89 | CC3       | 10n           | FilmCapacitor         |                |              
| 90 | CEC1      | 10u(22u)      | ElectrolyticCapacitor | Experiment   with    different values  \-    1u  on    CE2       |
| 91 | CEC2      | 10u           | ElectrolyticCapacitor |                |     
| 92 | CEC3      | 10u           | ElectrolyticCapacitor | 100u   has     been  suggested on    forum       |
| 93 | D1        | 1n4005        | diodes                | Power      Protection  1N5187  | alternative |          |
| 94 | D2        | LEDA          | diodes                | Bypass         | LED               |
| 95 | D3        | LEDA          | diodes                | Triangle       | /        Sine       Selection LED               |
| 96 | D4        | LEDA          | diodes                | Triangle       | /         Sine       Selection    LED            |
|  |            |             |                         | The    Following  Diodes   are  part  of   the clock   circuit   | 
| 97 | CD1       | LEDB          | diodes                | Rate           | LED         
| 98 | CD2       | 1N4148        | diodes                |                |             
| 99 | CD3       | 1n4148        | diodes                |                |             
| 100 | CD4       | 1N4148        | diodes                |                |             
| 101 | CD5       | 1n4148        | diodes                |                |             
| 102 | Q1        | 2N3904        | transistors           | 2n5088/9       | Alternatives | for          | all         | transistors |         
| 103 | Q2        | 2N3904        | transistors           |                |            
| 104 | Q3        | 2N3904        | transistors           |                |           
|   |            |            |                         | The  Following   Transistors   form   part   of    the    clock   ircuit      
| 105 | CQ1       | 2N3904        | transistors           |                |          
| 106 | CQ2       | 2N3904        | transistors           |                |            
| 107 | CQ3       | 2N3904        | transistors           |                |          
| 108 | CQ4       | 2N3904        | transistors           |                |             
| 109 | CQ5       | 2N3904        | transistors           |                |         
| 110 | IC1       | TL072         | integrated circuits | Any   Typical Dual Opamp       |      
| 110 | IC2       | TL022         | integrated    circuits       | Use   Low  Power Op   Amp  for     best results |
| 111 | IC3       | MN3208\_BBD   | integrated    circuits       | MN3207/8   OR   MN3007       \-         SEE      NOTES!  
| 112 | IC4       | MN3101\_CLK   | integrated  circuits   | MN3102    OR      MN3101      –  SEE     NOTES   |   
| 113 | CIC5      | TL022         | integrated  circuits   | Use     Low     Power  Op   Amp  for best results |
| 114 | REG1      | LM78L08       | 8v    regulator      | Install     if        using     MN3207.    Install  Regulator    OR   RR1  if using MN3007      |          
| 115 | BiasVR1   | 25k           | potentiometers        | Pot  to  Tune   Bias  Voltage  for  BBD    
| 116 | TuneVR2   | 50k           | potentiometers        | LFO   Tuning      
| 117 | SineTrim3 | 47k           | potentiometers        | Sine  wave  shape   trimmer can   be    omitted  and     pins      2  &   3  shorted.  See  Notes     
| 118 | CLR1      | 47k           | \-100k                | potentiometers | LED          | Brightness   | Trimmer     
| 119 | Trim1     | 47k           | \-100k                | potentiometers | LED          | Brightness   | Trimmer   
| 120 | Rate1     | B100k         | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount  
| 121  | Shape2    | B100k         | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount   
| 122 | Depth3    | B100k         | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount   
| 123 | Delay4    | B500k         | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount    
| 124 | Tone5     | B50k          | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount   
| 125 | Blend6    | B10k          | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount   
| 1 | Also      | required      | 2                     | x              | 3PDT         | Footswitches |        
| 1 | Bypass    | Footswitch    |                       |                |           
|  | LFO       | F             |                       |               
|  | Footswitch | Sine/Triangle | LFO                   | Selection      | 

Clea
