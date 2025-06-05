![image](https://github.com/user-attachments/assets/baa43cf0-a40d-49a7-9e80-e84ad0cd7695)
![image](https://github.com/user-attachments/assets/cebee175-c0f4-4a6e-9fde-3e9c0c99a886)

This Slapdown Intake was essentially my first full attempt at designing a slapdown-style intake - a system meant to rapidly deploy and collect game pieces from the floor.
In FRC there tend to be two different types of intakes that get used: Slapdown Intakes and Four-Bar Intakes. It has always been hotly contested which one is preferable, but with the storeability, the simplicity and the sheer reliability, Slapdown Intakes came out on top.

Intakes in FRC use rollers (Polycarbonate) when the game piece is squishy (compliant), and compliant/star wheels when the game piece is hard (noncompliant). Essentially this is just saying that squish = roller and non-squish = wheel

![image](https://github.com/user-attachments/assets/1076e9cb-b1d8-4755-abf6-c8b36525db5e)
I also wanted to highlight the master sketching (Layout Sketch) in this mechanism mostly because its a good representation of how I use master sketches to design my parts. I believe it's good practice to be able to make designing as easy as possible and as parametric (well-changeable and connected) as possible in order to make it easier to change variables.
This is one of those ways. The part studio is specifically designed that despite all the different plates and complexity, if you change one thing, it will change everything linked ot it, in order to fit the dimension just inputted. It's pretty cool!

However, there are a few design issues, for one the main chain drive is driven by pulley, which isn't great for power transmission or good intake design.
A more direct drive, perhaps with gears is preferred, so that would be mechanically more simple and also reliable.

The plates themselves were also not ideal, the packaging was very spread out, also a fault of the master sketch being a bit overestimating of how much footprint the intake would need to take up. Too much vertical space was occupied, which would make it less aesthetically pleasing and more difficult to integrate with the rest of the robot structurally.

Despite the flaws, I did still gain the experience in laying out a multistage (if you will) mechanism with intaking and also pivot structure, and then also how power transmission decisions do affect perforamnce and maintenance. This was also mentioned in my elevator.md where the 2025 NOMAD robot originally ran belt-elevator, but that skipped. a lot of the power transmission is made better by chain in these applications, however, chains are heavy which is the main drawback.
