Name:

EID:

Team Number:

## Questions

1. Why does your program need a setup and a loop?

    Set up to initialize the ports
    Loop to run the main program in a loop

2. What is the downside to putting all your code in a loop?
   Having to reinitialize everything everytime it loops.
   
    

3. Why does your code need to be compiled?

    To be converted into machine code

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    It starts blinking at a lower rate. Decreasing duty slowly would be a better idea.

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    Every connected device needs to have a common ground. Voltage is relative.

6. What is the difference between synchronous and asynchronous communication?

    Synchronous has clock; Asynchronous doesn't.

7. Profile of UART: Sent X bytes in Y time 

   6 bytes 0.512 ms
8. Profile of SPI: Sent X bytes in Y time

    6 bytes 0.175 ms

9. Why is SPI so much faster than UART?

    It has clock and collect data in that clock.

10. list one pro and one con of UART

    pro: cheap because doesn't have clock
    con: slow because doesn't have clock

11. list one pro and one con of SPI
    pro: fast
    con: more expensive

12. list one pro and one con of I2C

  we haven't done i2c

13. Why does I2C need external resistors to work?

    havent done i2c yet

## Screenshots

Procedure A, step 1:
![C:\Users\bprim\arduino-lab-1-bprimal22\img](img/ProcedureA_1.png)

Procedure A, step 4:
![C:\Users\bprim\arduino-lab-1-bprimal22\img](img/Dim_lab1.png)

Procedure B, UART:
![C:\Users\bprim\arduino-lab-1-bprimal22\img](img/hello.png)

Procedure B, SPI:
![C:\Users\bprim\arduino-lab-1-bprimal22\img](img/spi1.png)
