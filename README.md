# PGFX_MegaChorus V1.0
Build Documents for Pan Galactic FX Mega Chorus

![image](https://user-images.githubusercontent.com/53580358/205485727-40fc8b8e-c4ad-4a11-8edd-47d804779c71.png)


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
|  |           |               |                       |                |           
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
| 35 | RR1       | 33r           | Resistor              | Install       this          if            using       |MN3007      |       
| 36 | and       | NOT           | installing            | the            voltage      regulator                
| 37 | All       | The            following             | Resitors        are           part          of           the          Clock/LFO  Circuit   | 
| 38 | CR1       | 100k          | Resistor              |                |           
| 39 | CR2       | CLR           | Resistor              |                |            
| 40 | CR3       | CLR           | Resistor              |                |            
| 41 | CR4       | 2k7           | Resistor              |                |             
| 42 | CR5       | 33k           | Resistor              |                |            
| 43 | CR6       | CLR(2k2)      | Resistor              | 2k2            | indicated    | on           | original    | schematic   |          
| 44 | CR7       | 10k           | Resistor              |                |       
| 45 | CR8       | 10k           | Resistor              |                |          
| 46 | CR9       | 10k           | Resistor              |                |            
| 47 | CR10      | 10k           | Resistor              |                |          
| 48 | CR11      | 10k           | Resistor              |                |             
| 49 | CR12      | 33k           | Resistor              |                |            
| 50 |           |               |                       |                |             
|  | CR13      | 68k           | Resistor              | See            | NOTES        | regarding    | Sine        | Trim        | Trimpot   |        
|  | CR14      | 33k           | Resistor              |                |            
|  | CR15      | 47k           | Resistor              |                |          
|  | CR16      | 390r          | Resistor              |                |            
|  | CR17      | 470k          | Resistor              |                |           
|  | CR18      | 10k           | Resistor              |                |             
|  | CR19      | 10k           | Resistor              |                |           
|  | CR20      | 6k8           | Resistor              |                |            
|  | CR21      | 6k8           | Resistor              |                |           
|  | CR22      | 10k           | Resistor              |                |           
|  | CR23      | 4k7           | Resistor              |                |           
|  | CR24      | 1k            | Resistor              |                |            
|  | CR25      | 10k           | Resistor              |                |             
|  | CR26      | 4k7           | Resistor              |                |            
|  | CR27      | 4k7           | Resistor              |                |             
|  | CR28      | 10k           | Resistor              |                |            
|  | C1        | 6n8           | FilmCapacitor         |                |            
|  | C2        | 1n            | FilmCapacitor         |                |            
|  | C3        | 47n           | FilmCapacitor         |                |      
|  | C4        | 8n2           | FilmCapacitor         |                |     
|  | C5        | 1u            | FilmCapacitor         |                |          
|  | C6        | 47n           | FilmCapacitor         |                |           
|  | C7        | 6n8           | FilmCapacitor         |                |          
|  | C8        | 3n3           | FilmCapacitor         |                |           
|  | C9        | 8n2           | FilmCapacitor         |                |             
|  | C10       | 470p          | FilmCapacitor         |                |          
|  | C11       | 47n           | FilmCapacitor         |                |        
|  | C12       | 1u            | FilmCapacitor         |                |          
|  | C13       | 47n           | FilmCapacitor         |                |          
|  | C14       | 8n2           | FilmCapacitor         |                |             
|  | C15       | 1n            | FilmCapacitor         |                |              
|  | C16       | 1u            | FilmCapacitor         |                |             
|  | EC1       | 10u           | ElectrolyticCapacitor |                |            
|  | EC2       | 220u          | ElectrolyticCapacitor |                |            
|  | EC3       | 100u          | ElectrolyticCapacitor |                |        
|  | EC4       | 10u           | ElectrolyticCapacitor |                |          
|  |           |               |                       |                |        
|  | The       | following     | Caps                  | all            | make         | up           | part        | of          | the       | clock/LFO | circuit |         |
|  | CC1       | 47p           | FilmCapacitor         | Depth          | Mod          | can          | be          | increased.  | 150p      | Highest   | Tested  |         |
|  |           |               |                       |                |             
|  | CC2       | 470n          | FilmCapacitor         |                |             
|  | CC3       | 10n           | FilmCapacitor         |                |              
|  | CEC1      | 10u(22u)      | ElectrolyticCapacitor | Experiment     | with         | different    | values      | \-          | 1u        | on        | CE2     |         |
|  | CEC2      | 10u           | ElectrolyticCapacitor |                |     
|  | CEC3      | 10u           | ElectrolyticCapacitor | 100u           | has          | been         | suggested   | on          | forum     |           |         |         |
|  | D1        | 1n4005        | diodes                | Power          | Protection   | 1N5187       | alternative |             |           |           |         |
|  | D2        | LEDA          | diodes                | Bypass         | LED               |
|  | D3        | LEDA          | diodes                | Triangle       | /            | Sine         | Selection   | LED         |           |           |         |         |
|  | D4        | LEDA          | diodes                | Triangle       | /            | Sine         | Selection   | LED         |           |           |         |         |
|  | The       | Following     | Diodes                | are            | part         | of           | the         | clock       | circuit   |           |         |         |
|  | CD1       | LEDB          | diodes                | Rate           | LED         
|  | CD2       | 1N4148        | diodes                |                |             
|  | CD3       | 1n4148        | diodes                |                |             
|  | CD4       | 1N4148        | diodes                |                |             
|  | CD5       | 1n4148        | diodes                |                |             
|  | Q1        | 2N3904        | transistors           | 2n5088/9       | Alternatives | for          | all         | transistors |           |           |         |
|  | Q2        | 2N3904        | transistors           |                |            
|  | Q3        | 2N3904        | transistors           |                |           
|  | The       | Following     | Transistors           | form           | part         | of           | the         | clock       | circuit   |           |         |         |
|  | CQ1       | 2N3904        | transistors           |                |          
|  | CQ2       | 2N3904        | transistors           |                |            
|  | CQ3       | 2N3904        | transistors           |                |          
|  | CQ4       | 2N3904        | transistors           |                |             
|  | CQ5       | 2N3904        | transistors           |                |         
|  | IC1       | TL072         | integrated            | circuits       | Any          | Typical      | Dual        | Opamp       |           |           |         |         |
|  | IC2       | TL022         | integrated            | circuits       | Use          | Low          | Power       | Op          | Amp       | for       | best    | results |
|  | IC3       | MN3208\_BBD   | integrated            | circuits       | MN3207/8     | OR           | MN3007      | \-          | SEE       | NOTES!    |         |         |
|  | IC4       | MN3101\_CLK   | integrated            | circuits       | MN           | 3102         | OR          | MN3101      | –         | SEE       | NOTES   |         |
|  | CIC5      | TL022         | integrated            | circuits       | Use          | Low          | Power       | Op          | Amp       | for       | best    | results |
|  | Chorus    | V1.0          | Build                 | Docs           | 5          
|  | (Based    | on            | the                   | BYOC           | MegaChorus) 
|  | REG1      | LM78L08       | 8v                    | regulator      | Install      | if           | using       | MN3207.    
|  | Install   | Regulator     | OR                    | RR1            | if           | using        | MN3007      |             
|  | BiasVR1   | 25k           | potentiometers        | Pot            | to           | Tune         | Bias        | Voltage     | for       | BBD    
|  | TuneVR2   | 50k           | potentiometers        | LFO            | Tuning      
|  | SineTrim3 | 47k           | potentiometers        | Sine           | wave         | shape        | trimmer     | can         | be        | omitted  
|  | and       | pins          | 2                     | &              | 3            | shorted.     | See         | Notes     
|  | CLR1      | 47k           | \-100k                | potentiometers | LED          | Brightness   | Trimmer     
|  | Trim1     | 47k           | \-100k                | potentiometers | LED          | Brightness   | Trimmer   
|  | Rate1     | B100k         | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount  
|  | Shape2    | B100k         | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount   
|  | Depth3    | B100k         | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount   
|  | Delay4    | B500k         | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount    
|  | Tone5     | B50k          | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount   
|  | Blend6    | B10k          | potentiometers        | Alpha          | 9mm          | Right        | Angle       | PCB         | Mount    
|  | Also      | required      | 2                     | x              | 3PDT         | Footswitches |        
|  | Bypass    | Footswitch    |                       |                |           
|  | LFO       | F             |                       |               
|  | Footswitch | Sine/Triangle | LFO                   | Selection      | 

Clea
