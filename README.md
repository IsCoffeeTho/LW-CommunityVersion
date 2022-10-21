# Logic World - Community Version (Mod)
## DISCLAIMER
**DO NOT USE MODS ON SERVER AS IT IS UNSUPPORTED CURRENTLY**

## Installation

[Using `git`](https://github.com/IsCoffeeTho/LWCommunityVersion/blob/master/INSTALLATION-withgit.md)

[Without `git`](https://github.com/IsCoffeeTho/LWCommunityVersion/blob/master/INSTALLATION-withoutgit.md)

## Components
### XOR Gate\* (Mini)
![XOR Gate*](https://user-images.githubusercontent.com/33318553/138606324-e99653d4-cb85-471e-9c64-b09a4aeb7c51.png)

Exactly like the big XOR gate except in a smaller package

### SR Latch
![image](https://user-images.githubusercontent.com/33318553/138606402-cbf3faa4-5c50-4f21-b382-a1c59d379025.png)

Its a Stock Standard SR Latch (Set, Reset Latch)

### Register
![image](https://user-images.githubusercontent.com/33318553/138606457-daeea039-c525-4a9f-a187-836e148a3399.png)

Very Similar to a D-Latch, Except it saves the bit on the falling edge of the Clock

### Multiplexer
![image](https://user-images.githubusercontent.com/16965564/138995049-e1094ad3-2efe-4ccd-951d-1b85a22e208f.png)

The multiplexer selects between two inputs (D0 and D1) based on the select input (S).

**Multiplexer Truth Table**

D0 | D1 | S | Output
:-:|:-:|:-:|:-:
0|any|0|0
1|any|0|1
any|0|1|0
any|1|1|1

### Demultiplexer
![image](https://user-images.githubusercontent.com/16965564/138996039-20f2c8fd-02fb-4dac-8efa-0243f22bbf20.png)

The demultiplexer routes the input (D) to one of two different outputs (Out 0 and Out 1) based on the select input (S).

**Demultiplexer Truth Table**

S | D | Out 0 | Out 1
:-:|:-:|:-:|:-:
0|0|0|0
0|1|1|0
1|0|0|0
1|1|0|1

### Circuit Via
![image](https://user-images.githubusercontent.com/33318553/138668446-4c98eee3-94e4-446f-9cfb-1dbddfeab37b.png)

Allows you to make "Circuit Traces" and it passes through the circuit board, similar to a through peg but small.

> ## Chips (currently broken [#2](https://github.com/pipe01/LogicScript/pull/2))
> ### 4 Bit RAM
> ![image](https://user-images.githubusercontent.com/33318553/138606702-04c57727-32e7-4a52-b854-3fcb43611fcf.png)
>
> `[4 ADDR (TOP ROW), 4 DATA (BOTTOM ROW), READ WRITE LINES, RESET CHIP ON FAR SIDE, 4 OUTPUTS (HIDDEN)]`
>
> `[DOT SIGNIFIES SIDE OF LSB]`
>
> A small RAM component perfect for any 4-bit system!
>
> ### Addressable SR Latch
> ![image](https://user-images.githubusercontent.com/33318553/138606839-85e66aff-775a-47f3-bada-a19199197f7b.png)
>
> `[8 ADDR, SET AND RESET LINES, RESET CHIP ON FAR SIDE, CHIP SELECT ON TOP, 1 OUTPUT (OPPOSITE ADDRs)]`
>
> `[DOT SIGNIFIES SIDE OF LSB]`
>
> Really shrinks down the giant RAM systems.
