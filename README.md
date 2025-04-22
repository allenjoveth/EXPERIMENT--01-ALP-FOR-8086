# EXPERIMENT 01 ALP FOR 8086
Name : ALLEN JOVETH P

Roll no : 212223240007

## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
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

mov ax,0abcdh
mov bx,2347h
add ax,bx

ret
```






## Output 
![1 add](https://github.com/user-attachments/assets/a0e635f3-b202-46fc-8404-1396e7d742ba)
 
## Subtraction   of 8 bit numbers  ALP 

```
org 100h

mov ax,[1000h]
mov bx,[2000h]
sub ax,bx

ret
```




 
## Output  
![2 sub](https://github.com/user-attachments/assets/76ef41a3-115a-43b0-bcc7-7edbdd62db35)

## Multiplication alp 
 
```
org 100h  

mov cx,7000h
mov bx,5000h
mov ax,bx 
mov dx,cx 

mul dx   

ret

```

 ## Output  
![3 multi](https://github.com/user-attachments/assets/df148b66-dc04-4aad-941c-2d2d250f7d93)

## Division alp 
```
org 100h  

mov bx,1001h
mov ax,[bx]
mov cx,05h
div cx 

ret
```
## Output  
![4 div](https://github.com/user-attachments/assets/21fecf92-cff7-41de-a9d9-e9d77851518f)

 
## Programs for logical  operations: 

## AND:
```
org 100h

mov ax,1234h 
mov bx,3456h
AND ax,bx

ret
```
## Output 
![5 and](https://github.com/user-attachments/assets/5d61dda1-21ce-4cc5-9739-d02db80f0094)

## OR :
```
org 100h

mov ax,1234h 
mov bx,3456h
or ax,bx

ret
```
## Output 
![6 or](https://github.com/user-attachments/assets/c2ec5acb-6b9f-4c80-95c0-92ed2d997d7e)

## NOT :
```
org 100h

mov ax,1234h 
NOT ax,bx

ret
```
## Output
![7 not](https://github.com/user-attachments/assets/fa45a325-2567-4aaf-871a-3f72bd1069e7)

## XOR :
```
org 100h

mov ax,1234h 
mov bx,3456h
XOR ax,bx

ret
```
## Output 
![8 xor](https://github.com/user-attachments/assets/3579428e-9219-4769-b1f4-adda417df364)


## Result :
The ALP on fundamental arithmetic and logical operations is executed successfully.
