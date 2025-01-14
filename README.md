# PS-2025-S8-Abhishek
## This github repository about the foundation on mixed-signal vlsi design.
## PASSIVE IC DEVICES
### Here we cover basic prionciplkes behind passive IC devices: Resistors,Cpacitors and Inductors.
### Resistance

- Finding current and resistivity in material
- <p align="center">
  <img src="https://github.com/user-attachments/assets/8e6408a0-07bd-4d3a-b83d-36e1f8f5cb6d" alt="Diagram" width="600" height="400">
  </p>
Consider a block of metal or semiconductor material with dimensions L,W, and H .\
Let N= Free charges per unit volume. 
A battery of "V" volts connected across the block .To calculate the current I<sub>R</sub> for an applied voltage 
 across the length of the material, we will consider an incremental cross section of the material with length 
. The current can be written as the total charge in the incremental volume in time 

$$I_R = \frac{\Delta Q}{\Delta T}= \Delta Qs\frac{\Delta X}{\Delta T}=Q_SV_D ...............................(i)$$

or,

$$I_R=SheetCharge* AverageVelocity$$

Here Q_S is the Sheet charge or the Free charges per unit length

$$Q_S= nWH = A.............................................(ii)$$

v<sub>d</sub>  is the average velocity of free charges:

$$ V_D= \frac{\Delta X}{\Delta T}  =\mu E ....................................................(iii) $$

$$E= \frac{\Delta V}{\Delta X}....................................................(iv)$$ 

Therefore from equation (i),(iii) and (iv)

$$I_R =Q_SV_D= Q_S\mu E= \mu Q_S \frac{\Delta V}{\Delta X}.....................................(v) $$

The incremental resistance can be expressed as :

$$\Delta R = \frac{\Delta V}{ I_R}$$

$$ =\frac{\Delta V}{\mu Q_S \frac{\Delta V}{\Delta X}}=\frac{\Delta V \Delta X}{Q_S \mu\Delta V}=\frac{\Delta X}{Q_S \mu}=\frac{\Delta X}{N A \mu}=\frac{\rho \Delta X}{A}$$

Total resistance of the material can be expressed as:

$$R = \sum \Delta R=\sum \frac{\rho\Delta X}{A}=\frac{\rho}{A} \sum \Delta X=\frac{\rho L}{A}.................................................(vi)$$

Here L and A are the length and cross-sectional area (WH) of the block respectively .

$$ R =\left( \frac{\rho}{H} \right) \left(\frac{L}{W} \right)....................................................(vii) $$

$\frac{\rho}{H}$ is called sheet-rho( $\rho_{sheet}$)


Calculate the resistance of an aluminum wire with the following dimension:
L= 100\mu, W=1Um, h=0.5 Um $$ \mu m $$
| Material | Resistivity in μm | Resistance | Sheet-row | Melting point | Cost/10 gram | Temprature coefficient of resistance |
|----------|----------|----------|----------|----------|----------|----------|
| Aluminium    | 2.65     | 26.5     | Data     | Data     | Data     | 0.00429     |
| Copper   | 1.68 | 16.8    | Data     | Data     | Data     | 0.00393   |
| Gold | 2.44| 24.4  | Data     | Data     | Data     | Data     | 0.0034  |





*ps-1*: [firstday resistance.pdf](https://www.dropbox.com/scl/fi/d346jb7r3z6xbblazyoxk/WhatsApp-Image-2025-01-09-at-11.28.12_a9e2c784.pdf?rlkey=li5fka6ik4l8pv1ra3ynxgc9c&st=opyjfgl1&dl=0)
## Second Day
- Capacitance of two charging plates
- ![image](https://github.com/user-attachments/assets/08131eaf-4c4a-4d76-b19b-7e27a5bdc407)

  *ps-2*: [secondday capacitance.pdf](https://www.dropbox.com/scl/fi/hjrkndgx4u982u7d9e87i/day2-ps.pdf?rlkey=pe8y32gs2lkz8uo831cdsf12l&st=cempfqmy&dl 
