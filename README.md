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
Lets consider 2 parallel plates connected with a battery of "V" volts.After sometimes of battery connection let the plate connected with the cathode of battery has total charge +Q on its surface and 
the plate connected with the anode of battery has total charge -Q on its surface .\
Gradually as the charge increases on the plate potential also increases.Let the potential on the plates are V1 and V2 respectively .\
Relation between total charge on either plate and potential difference between two parallel plates (V= V1-V2) can be mathematically expressed as:

$$ Q \propto V $$
 
Here the proportionality constant is the capacitance of the parallel plates : 

$$ Q = CV .......................(1)$$  
 
We will apply Gauss's theorem to calculate the capacitance of the parallel plates .\
Gauss Theorem can mathemticallly expressed as

$$\Phi_E = \oint\limits_S\overrightarrow{E} . \overrightarrow{dS} = \frac{Q _{in}}{\epsilon_o} .........................................(2)$$

We imagine a closed gaussian surface around a plate and total electric flux coming out of that closed gaussian surface can be expressed as

$$\Phi_E = EA=  \frac{Q}{\epsilon_o} $$

Q can be expressed as :

$$ Q=\overrightarrow{E}.A.\epsilon_o ...................(3) $$

Assuming a large area and small separation "d" between plates , Electric feild between plates can be expressed mathematically 

$$ \overrightarrow{E} = \frac{V}{d}...........................(4)$$

From the equation 1 Capacitance C can be expressed as  : 

$$C= \frac{Q}{V} $$

Therefore putting the values of Q and V from equation 3 and 4 the capacitance of the parallel plates can be expressed as:

 $$ C=\frac{\epsilon_0 \cdot AE}{Ed} = \frac{\epsilon_0 \cdot A}{d} ............................(5)$$

* Calculate  C1  and C2 of the image
 <p align="center">
   <img src="https://github.com/user-attachments/assets/1eb4bfff-6368-469d-bfcd-5d40f87470b8" alt="Description" width="600" height="400"/>
</p>
To calculate c1=

$$ C_1= \frac {\epsilon_o.A.K}{d} $$

$$=\frac{ 8.85 \times 10^{-12}  \times  100 \times 10^{-6} \times 1 \times10^{-6} \times 3.9}{1 \times 10^{-6}} =3.4515  \times 10^{-15}$$                            

$$C_2=\frac {\epsilon_o.A.K}{d} $$

$$=\frac{ 8.85 \times 10^{-12}  \times 100 \times 10^{-6} \times 1 \times10^{-6} \times 3.9}{0.1\times 10^{-6}}=34.515 \times 10^{-15} $$

| Dielctrics| A=5000 mm<sup>2</sup> D= 0.5mm| A=5000 mm<sup>2</sup>D= 1.5mm|  A=5000 mm<sup>2</sup> D= 2.5mm |  A=5000 mm<sup>2</sup> D= 3.5mm |  A=5000 mm<sup>2</sup> D= 4.5mm |  A=5000 mm<sup>2</sup> D= 5mm|
|----------|----------|----------|----------|----------|----------|----------|
| Air  | C=89 K=1.005     | C=30 K=1.016   | C=18 K=1.016   | C=13 K=1.028   | C=10 K=1.016  | C=9 K=1.016    |
| Mica  | C=456 K=5.15  | C=148 K=5.016| C=89 K=5.028   | C=64  K=5.062  | C=48 K=4.88    | C=45 K=5.08   |
| Paper    | C=307 K=3.46  | C=104 K=3.52    | C=63 K=3.55    | C=45 K=3.55  | C=34  K=3.45  | C=32 K=3.615   |
| Paraffin    | C=210 K=2.37   | C=67  K=2.27    | C=42  K=2.37    | C=28 K=2.21    | C=23 K=2.33   |C=21 K=2.37   |
| Porcelain    | C=546   K=6.16 | C=188 K=6.37   |C=108   K=6.10    | C=80 K=6.32    | C=63  K=6.40    |C=54  K=6.10    |
| Glass   | C=601  K=6.79  | C=204 K=6.91    |C=121 K=6.83   | C=89   K=7.03    | C=68  K=6.91 | C=63 K=7.11   |






| Dielectrics |A=5000 mm<sup>2</sup> D= 0.5mm | A=10000 mm<sup>2</sup> D= 0.5mm| A=15000 mm<sup>2</sup> D= 0.5mm | A=20000 mm<sup>2</sup> D= 0.5mm | A=25000 mm<sup>2</sup> D= 0.5mm | 
|----------|----------|----------|----------|----------|----------|
| Air    |C= 89 K=1.005|C=177 K=1|C=266 K=1.001|C=354 K=1    | C=443  K=1.001|
| Mica    | C=456   K=5.15|C=858 K=4.84 |C=1314 K=4.94 |   | C=1 | 
| Paper    | C=307   k=3.46| C=620 K=3.50|C=911 K=3.43| C=1202 K=3.39 | C= 1533 K=3.46|
| Paraffin    |C=210 K=2.37 | C=407 K=2.29     |C=617 K=2.32    | C=806 K=2.27  | C=1028 K=2.32 |
| Procelain  |C=546 K=6.16| C=1104 K=6.23     | C= 1689 K=6.36     | C=1 K=0.0028| C=1 K=0.0022| 
| Glass    |C=601 K=6.79|C=1264 K=7.141     | C=1877 K=7.069     | C=1 K=0.0028     |C=1 K=0.0022  |
- Capacitance of two charging plates
- ![image](https://github.com/user-attachments/assets/08131eaf-4c4a-4d76-b19b-7e27a5bdc407)

  *ps-2*: [secondday capacitance.pdf](https://www.dropbox.com/scl/fi/hjrkndgx4u982u7d9e87i/day2-ps.pdf?rlkey=pe8y32gs2lkz8uo831cdsf12l&st=cempfqmy&dl=0)

 
 
