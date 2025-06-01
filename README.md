# EXPERIMENT 01 ALP FOR 8086
### Name : THRIKESWAR p
### Roll no : 212222230162 
### Date of experiment : 4-03-2025





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h

MOV AX,5123H
MOV BX,1142H
ADD AX,BX

ret
```


## Output  
![Screenshot 2025-03-04 102937](https://github.com/user-attachments/assets/3a0b1e14-dca0-489f-82c1-5a7477ecb59c)

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h
MOV BX,1200h
MOV AX,BX
MOV CX,120h
MUL CX
ret
```

## Output
![Screenshot 2025-03-04 104241](https://github.com/user-attachments/assets/68292950-f2a3-4577-a4c3-ad3a8f00bb71)

## Multiplication alp 
```
 org 100h
MOV BX,1200h
MOV AX,BX
MOV CX,120h
MUL CX
ret
```
 ## Output  
![Screenshot 2025-03-04 105745](https://github.com/user-attachments/assets/c1ce32a2-1465-4d82-bb34-3c0e078cadcc)


## Division alp 
```
org 100h
MOV AX, 0009H   
MOV BL, 02H     
DIV BL    
ret
```
## Output  
![Screenshot 2025-03-04 112027](https://github.com/user-attachments/assets/e963e84e-6b57-43d0-8dcf-18680535cbf4)

## And of 8 bit numbers ALP
```assembly
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## Output
![ANDEX](https://github.com/JananiSoundararajan/EXPERIMENT--01-ALP-FOR-8086/assets/119477549/137f8c67-17d9-4cc2-8437-349d50e0a404)

## OR of 8 bit numbers ALP
```assembly
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## Output
![OR EX](https://github.com/JananiSoundararajan/EXPERIMENT--01-ALP-FOR-8086/assets/119477549/d9fce991-bce0-4c58-a77c-2de3216f302d)

## NOT of 8 bit number ALP
```assembly
MOV AL,65H
NOT AL
HLT
```
## Output
![NOT EX](https://github.com/JananiSoundararajan/EXPERIMENT--01-ALP-FOR-8086/assets/119477549/a7efe90e-2100-4df5-8298-3516af3b7f65)

## XOR of 8 bit number ALP
```assembly
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output
![XOREX](https://github.com/JananiSoundararajan/EXPERIMENT--01-ALP-FOR-8086/assets/119477549/838fcf0e-3db2-4d6c-a9b6-0607b839726d)


## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








