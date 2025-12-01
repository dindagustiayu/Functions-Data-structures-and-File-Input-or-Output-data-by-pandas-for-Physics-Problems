# Function, Data Structures, and File Input or Output
This work aims to applying the concept of _Functions, Data Structures, and File Input/Output_ for solving physics problems by Python 3 and Jupyter Notebook. There are some solutions for tasks in this Python code.

# Key Equation
- The Solar mass
  -  $M_{Sun}=\frac{4\pi^{2}(1 AU)^{3}}{G (1 yr)^{2}}$
- The velocity of an atom
  - $v(x)=\sqrt{v_{0}^{2}+\frac{2F_{0}}{m}(cos\frac{x}{n}-1}$

## 1. Function
## P4.1 - The solar mass
Calculate the solar mass. The solar mass can be calculated by using the relation:
            $M_{Sun}=\frac{4\pi^{2}(1 AU)^{3}}{G (1 yr)^{2}}$

In this task, we will use approximate values for AU and G. The unit AU is an astronomical unit of length. Its value is defined to be the average distance between the Sun and Earth:

1 AU = 1.496 x $10^{11}$ m
            
where 1 lightyear = 9.5 x $10^{12}$ km. The constant G is called the gravitational constant and has the following value:

G = 6.674 X $10^{-11}m^{3}kg^{-1}s^{-1}$

## P4.2 - The velocity of an atom
The atoms within a material are structured such that they create a lattice. We will look at an atom which moves along the surface of a material. Since the atoms are aligned as a lattice, we could use a periodic model to find the velocity of the atom moving across the surface:

$v(x)=\sqrt{v_{0}^{2}+\frac{2F_{0}}{m}(cos\frac{x}{n}-1)}$

where m is the mass of the atom, x is the position, v0 is its initial velocity, and n is a scaled distance between the atoms within the material. We set the force F0 = 1N. Find the velocity of the atom when x = 1, v0 = 2, n = 4 and m = 3.

- Repeat the calculation for Zn, Cu, and Ni for F0 = 1 x $10^{-25}$ N

## 2. Data Structures

## P4.3 - The crystall lattice structures
The crystal lattice structures of the first row transition metal elements are given below. Some elements have different crystal structures under different conditions of temperatures and pressure. Use python sets to group them and determine which metal,
- (a) only exist face-centered cubic (fcc), body-centered cubic (bcc), hexagonal-centered cubic (hcp)
- (b) exist  in two of these structures
- (c) do not form an hcp structure.

| Lattice |      Elements           |
|:--------|------------------------:|
|FCC      | Cu, Co, Fe, Mn, Ni, Sc  |
|BCC      | Cr, Fe, Mn, Ti, V       |
|HCP      | Co, Ni, Sc, Ti, Zn      |


## P4.4 - Magnetic classification
The magnetic properties are related to metals. Some elements have different properties under different conditions of temperatures and pressure. Use python sets to group them and determine which category, 
- (a) only exist as diamagnetic, paramagnetic, and non-magnetic.
- (b) exist  in two of these magnetic.
- (c) exist  in three of these magnetic.

| category    |      Elements         |
|:------------|----------------------:|
|Diamagnetic  | Zn, Cu, Sc, Ti        |
|Paramagnetic | Cr, Mn, V, Fe, Cu, Ti |
|Non-magnetic | Al, Zn, Sc            |

## P4.4 - Magnetic classification
The magnetic properties are related to metals. Some elements have different properties under different conditions of temperatures and pressure. Use python sets to group them and determine which category, 
- (a) only exist as diamagnetic, paramagnetic, and non-magnetic.
- (b) exist  in two of these magnetic.
- (c) exist  in three of these magnetic.

| category    |      Elements         |
|:------------|----------------------:|
|Diamagnetic  | Zn, Cu, Sc, Ti        |
|Paramagnetic | Cr, Mn, V, Fe, Cu, Ti |
|Non-magnetic | Al, Zn, Sc            |


## P4.5 - The computational density
The text file [atomic-data.txt](https://github.com/dindagustiayu/Functions-Data-structures-and-File-Input-or-Output-data-by-pandas-for-Physics-Problems/blob/main/atomic-data.txt), which can be downloaded directly, contains data for the elements, molar cell, and volume cell for Al, Cu, and Pb. Read in data and calculate computational density for each subtances.
