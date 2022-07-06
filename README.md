# MICROCONTROLLER-TRAINER-MODEL-LGS-51
User manual of microcontroller trainer model LGS-51
## Introduction
the LGS51 series Trainer is designed to be both useful and instructive in illustrating certain concepts commonly encountered in 8051/52-based development. Although many kits already exist, this kit is designed specifically to form the basis of thorough technical discussions and tutorials consistent with Experts in the field of Microcontroller development & Experience Faculties in Microcontroller Subject.
The Kit is was developed with the 8031/51 in mind but can be used with any 40-pin 8052 pin-compatible derivative including the traditional true-blue 8052, 8051, 8032, 8031, 89C55WD, 89VRD2 etc.
It has
* 16X2 LCD Display
* 32K BB RAM,8+16K additional RAM, 32 k Monitoe EEPROM.Memory expandable up to 128 K.
* 48I/O lINES from 8255 X 2 nos. of serial ports from 8051 and 8251, on board 8253. 14 I/O lines from 8051 CPU which is very useful for students to interface other devices directly to microcontroller like DAC, stepper motor, DC motor etc.
*  built in Line assembler & disassembler.
*  with the use of PS2 Type keyboard user can directly write/enter the program in assembly language.
*  Can checked the entered code in mnemonics using disassembler facility.
*  To develop the skills in applications using 8051 we have wide range of interfacing modules to select like ADC, DAC, stepper motor etc.

## hardware Details
1)0000H To 1FFFH-8K			Monitor EPROM (Program Memory)
 
2)2000H To 3FFFH-8K			Scratch Pad RAM Available to user,
                                               			after 27FFH. (Data Memory)

3)8000H To FFFFH-32K                   	User RAM Battery backup.
                                                               	(Data Memory)

4)  0003H Data memory                         CW for 8255
     0000H                                                      Port A
     0001H                                                      Port B
     0002H                                                      Port C

5)  0203H Data                                    	CW for 8253
     0200H                                                   Channel 0
     0201H                                                   Channel 1
     0202H                                                   Channel 2

6)  0400H LCD                                      		Display

7)  Interrupt vector table for LGS 51 kit
    		Interrupt                                     RAM Location
      		INTO                                              FF03
      		TFO                                                FFOB
      		INT1                                               FF13
      		TF1                                                 FF1B
      	     RI and TI                                             FF23

8) Internal Memory Mappings,
  ;00h - 0fh bank 0/1 user access
  ;10h - 27h monitor scratch / monitor bank 2 (r0 - r7)
  ;28h - 3fh user scratch
  ;40h - 5fh monitor data
  ;60h - 7fh monitor stack
  (For 8052/89C52 user can use additional Internal RAM from 80H to FFH.
        






### Monitor Command
### Serial Link Command

