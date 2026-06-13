# Docking Station!

  <img height="300" alt="image" src="https://github.com/user-attachments/assets/cbf13a72-4174-458b-b8e1-4b8602277858" />

  [View in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/cec4245d48316d051146b3ca?renderMode=0&uiState=6a2cddf3cc68f1e0ff63f0b2)


A very cool laptop docking station with 9 USB-A 2.0 ports!

<div id="contents">

1. [Why?](#why)
2. [What can it do?](#what-can-it-do)
3. [Fallout Zine](#fallout-zine)

</div>

## Why?
My laptop only has 2 USB-A ports, which is honestly not enough especially when both of them are used up for a keyboard and mouse.

I made this docking station to change that.

Another reason I made this is that I kinda like taking my laptop with me and keep it on my lap while using it on the sofa sometimes, so a docking station kinda makes that easier so you only have to plug it in and then everything works!

<div align="center"><a href="#contents">Jump to contents</a></div>

## What can it do?
It has 9 USB ports, which you can connect whatever you want to. The USB ports are controlled using an Fe1.1s controller.

It also has an ESP32 and 2 controllable PWM case fans (with two mosfet so you can turn them completely off), to keep your laptop cool and prevent it from overheating.

I also added external power from a barrel jack, because the laptop wont be able to power so many USB ports, especially when things are connected to them.

There is also a programmable e-ink display, you can display the time, your notifications, the current speed of the fans, or even show specifically which USB ports are currently in use!

I also added a mini detachable macropad with three switches and a rotary encoder.

You can program the macropad's buttons to do whatever you want! The rotary encoder also works as a switch, so technically there are four switches. You can make the rotary encoder change the volume, fan speeds, etc!

The macropad is connected to the ESP32!

Oh and btw the ESP32 also supports WiFi incase you want it to show weather or something even when the laptop is turned off.

The ESP32 also knows exactly which ports are connected to devices at a time, so you can also make it show how many ports are in use, and how many are free, etc!

<div align="center"><a href="#contents">Jump to contents</a></div>


## Fallout Zine
<a href="https://github.com/KavyanshKhaitan2/docking-station/blob/main/zine/Zine%20Print.pdf"><img height="500" src="https://github.com/KavyanshKhaitan2/docking-station/blob/main/zine/Zine%20Preview.png?raw=true"></a>

[ [Download PDF](https://github.com/KavyanshKhaitan2/docking-station/raw/main/zine/Zine%20Print.pdf) ]

<div align="center"><a href="#contents">Jump to contents</a></div>

## PCB
<div align="center"><a href="https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FKavyanshKhaitan2%2Fdocking-station%2Ftree%2Fmain%2Fpcb%2F">View in KiCanvas</a></div>

### Mainboard
<img width="762" height="787" alt="image" src="https://github.com/user-attachments/assets/f07582ee-52d5-4ef0-9801-ea6f6c95a236" />

### Left Daugtherboard
<img height="400" alt="image" src="https://github.com/user-attachments/assets/7a56be86-c604-4629-9c5e-8820b2adc620" />

The rest of the PCBs are very similar to the left daughterboard one, so I wont add them. If you still want to take a look at them, feel free to open the KiCanvas link!

<div align="center"><a href="#contents">Jump to contents</a></div>

## Schematic
<div align="center"><a href="https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FKavyanshKhaitan2%2Fdocking-station%2Ftree%2Fmain%2Fpcb%2F">View in KiCanvas</a></div>

### Mainboard
<img height="400" alt="image" src="https://github.com/user-attachments/assets/430dcd0d-4fb0-42ba-a5ec-e117e004c771" />

### Left daugtherboard
<img height="300" alt="image" src="https://github.com/user-attachments/assets/c19b2ab1-731a-4c2c-9836-41a188325883" />

### Right daugtherboard
<img height="300" alt="image" src="https://github.com/user-attachments/assets/160a206d-7688-405a-ba28-a7a5161ac404" />

### Front daughterboard
<img height="300" alt="image" src="https://github.com/user-attachments/assets/72d35e1b-8e6b-48dd-a893-aefcf4842dba" />

<div align="center"><a href="#contents">Jump to contents</a></div>


## 3D
- [ [Download assembly as a STEP file](https://github.com/KavyanshKhaitan2/docking-station/blob/main/Final%20assembly.step) ]
- [ [Open Assembly in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/cec4245d48316d051146b3ca) ]

### Main case
<img width="1336" height="740" alt="image" src="https://github.com/user-attachments/assets/a5048764-f74d-4f68-86fc-c7977ebf36d1" />

- [View in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/84ca16973cb290fcea814d7e)
  - Part 1 (bottom) ([View STL in GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/Main%20Case/Main%20Case%20Thingy%20-%20Part%201.stl))
    - Print in black
    - Please print this part with supports!
  - Part 2 (top) ([View STL in GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/Main%20Case/Main%20Case%20Thingy%20-%20Part%202.stl))
    - Print in black

<div align="center"><a href="#contents">Jump to contents</a></div>

### Macropad assembly
<img width="1040" height="661" alt="image" src="https://github.com/user-attachments/assets/77b5c6ec-4090-4af2-8821-82f604d22291" />

- [View in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/eab1af3c6609ed024df62d84)

### Macropad case
<img width="971" height="728" alt="image" src="https://github.com/user-attachments/assets/fb638b0e-17b0-492f-9352-1b71dc49ee58" />

- [View in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/cd5c69b8e6d2878261d109a7)
  - Part 1 (bottom) ([View STL in GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/Switches%20Case/Switches%20Case%20-%20Part%201.stl))
    - Print in black
  - Part 2 (top) ([View STL in GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/Switches%20Case/Switches%20Case%20-%20Part%202.stl))
    - Print in black
  - Screw ([View STL in GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/Switches%20Case/Switches%20Case%20-%20Screw%20(print%20x4).stl))
    - Print in black
    - Print x4
  - Accent (for top) ([View STL in GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/Switches%20Case/Switches%20Case%20-%20Accent.stl))
    - Print in filament closest to #8B2B2B.
      - <img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/2fcce77c-ef1c-480e-b163-ec6a6f97f5ec" />

<div align="center"><a href="#contents">Jump to contents</a></div>

### ePaper assembly
<img width="616" height="736" alt="image" src="https://github.com/user-attachments/assets/bf810040-92ed-4f03-b8e8-0668b8f902ca" />

- [View in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/d050ad97f0686956ed070595)

### ePaper case
<img width="520" height="652" alt="image" src="https://github.com/user-attachments/assets/7697053f-58d2-4825-840d-7024720bf91a" />

- Main part
  - [View in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/4e8279b7c40fa71bd8f46031)
  - Lid part (Lid) ([View STL in GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/ePaper%20Case/ePaper%20case%20-%20case-lid.stl))
  - Main part (Main) ([View STL in GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/ePaper%20Case/ePaper%20case%20-%20case-main.stl))
- Display angle-r
  - [View in OnShape](https://cad.onshape.com/documents/6c290d74c1d15daba79eec04/w/3858ccf09c2f651529fab3b7/e/b7b2b35c02b07108b093d455)
  - [View STL on GitHub](https://github.com/KavyanshKhaitan2/docking-station/blob/main/production/3dp/ePaper%20Case/Display%20angle-r%20-%20Part%201.stl)
    - Print in black
   
<div align="center"><a href="#contents">Jump to contents</a></div>
