# GRBL-CNC-Shield-Nema23-Stepper-Motor-TB6600

![image](https://user-images.githubusercontent.com/19898602/185733018-77ae5aa4-1d6d-46ad-ba2c-e7096647ec2c.png)

Hello friends in this post I have made a custom PCB for the GRBL CNC Shield + Nema 23 Stepper Motor + TB6600.

So you’ll tell what is new in that right ? 

so the new thing is that this CNC GRBL shield used to control NEMA23 stepper motor.![MVI_0001_9_1_1](https://user-images.githubusercontent.com/19898602/185733389-2337b1f0-a99f-4d7e-8605-f2c0dad0b3ac.gif)


In current situation we have GRBL CNC SHIELD V3 which can only control NEMA 17 stepper motor with A4988 stepper driver.

![image](https://user-images.githubusercontent.com/19898602/185733031-adce2c58-0212-48bf-91b8-d2c8731a8098.png)


What if we need to install NEMA23 Stepper motor in CNC machine for more power.

you cannot do this task with traditional GRBL CNC Shield. 

either you have to shift for MACH controller board which runs on proprietary software MACH3/4.

In this case you have to invest a lot in hardware and software, and for the sake of hobby CNC MACH way to complicated.

![image](https://user-images.githubusercontent.com/19898602/185733041-329d8516-846b-40e3-a2a0-2732b89fbfee.png)


But after using my CNC Shield you can easily connect 4 bigger stepper motor and TB6600 Stepper driver very easily and enjoy your CNC work on GRBL version without any issue and this CNC shield works on Arduino Nano so your control box even get compact.

Grbl is a no-compromise, high performance, low cost alternative to parallel-port-based motion control for CNC milling. It will run on a vanilla Arduino (Duemillanove/Uno) as long as it sports an Atmega 328.

The controller is written in highly optimized C utilizing every clever feature of the AVR-chips to achieve precise timing and asynchronous operation. It is able to maintain up to 30kHz of stable, jitter free control pulses.

It accepts standards-compliant g-code and has been tested with the output of several CAM tools with no problems. Arcs, circles and helical motion are fully supported, as well as, all other primary g-code commands. Macro functions, variables, and most canned cycles are not supported, but we think GUIs can do a much better job at translating them into straight g-code anyhow.

Grbl includes full acceleration management with look ahead. That means the controller will look up to 18 motions into the future and plan its velocities ahead to deliver smooth acceleration and jerk-free cornering.

# PIN OUT OF GRBL CNC SHIELD

![image](https://user-images.githubusercontent.com/19898602/185733053-a90c3646-8feb-4873-93d3-88efe64aac9c.png)


You can all components which latest version of GRBL supports like

1. Coolant
2. Resume
3. Hold
4. Abort
5. Spindle direction
6. Spindle Enable
7. E-stop
8. X-Limit switch
9. Y-limit Switch
10. Z-limit Switch
11. Enable
12. X_Step
13. X_Dir
14. Y_Step
15. Y_DIR
16. Z_Step
17. Z_Dir
18. A_Step
19. A_Dir

A-step and A-direction is for to mirror any other 4 Axis.

In order to enable this 4rth Axis you need to add jumper at shown location.

![image](https://user-images.githubusercontent.com/19898602/185733078-60cfe74c-aabd-4f78-80a5-2fcaa1343ba7.png)


In fact you can connect any bigger stepper and most of any Stepper driver will work with this shield.

It is compatible with stepper driver like

1. TB6600
2. DM556
3. DM542
4. TB6560

# PCB FILE OF GRBL CNC SHIELD

[You can download or edit PCB & Schematic of this shield](https://oshwlab.com/sharmaz747/nema23-grbl-cnc-shield)

![image](https://user-images.githubusercontent.com/19898602/185733221-2f469b03-4aa5-45f1-bdd8-295ba5bf272b.png)


![image](https://user-images.githubusercontent.com/19898602/185733187-0a66c6e9-4695-4799-9131-274914687379.png)

![image](https://user-images.githubusercontent.com/19898602/185733190-ec66fe73-5b8a-45b1-9e8d-a5c0c1c3f169.png)

# ODERING PCB
![image](https://user-images.githubusercontent.com/19898602/185733487-12458378-a4ed-4996-a844-b92d4f49bde5.png)

![image](https://user-images.githubusercontent.com/19898602/185733492-a5920bae-0027-4a75-ad28-1c2a69f8b4c2.png)


After designing PCB in my favorite PCB editor tools. Now it’s time to order PCB

I trust on [JLCPCB](https://jlcpcb.com/IAT ) for ordering PCB they have very fast shipping service and low rates for quality PCB.

You will also get welcome coupons from [JLCPCB](https://jlcpcb.com/IAT ) so hurry up & visit [JLCPCB](https://jlcpcb.com/IAT )



# CONNECTION DIAGRAM

![image](https://user-images.githubusercontent.com/19898602/185733236-6e9a0e51-edda-4739-b664-f62c0a731b37.png)



![MVI_0001_9_1_1](https://user-images.githubusercontent.com/19898602/185733408-dfc774c2-bc56-4d62-b855-5886294c59c3.gif)


