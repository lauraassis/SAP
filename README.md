# SAP
# Switch Allocation Problem in Power Distribution Systems

###########################################################
# This repository provided information about 9 Power 
# Distribution Systems for Switch Allocation Problems 
# By:
# 1. Laura Assis - laura.assis@cefet-rj.br
# 2. José González - jfvg@feg.unesp.b
# 3. Gustavo Epifanio - gustavo.epifanio@eic.cefet-rj.br
###########################################################

Input Format:

Each instance provided represents an extensive power distribution network based on a real-life system. The information of a particular network is located in a specific directory as R1, R2, ..., Rn.

Each directory afford 3 files:

1. Ri_protections.txt - contains information about the protections devices present in the network.

  a) #ArcNumber - represents the number of the arc (in the network) where the protection is placed.

  b) Type - represents the type of the equipment placed in this arc.

2. Ri_switches.txt - contais information about the switches present in the network.

  a) #ArcNumber - represents the number of the arc (in the network) where the protection is placed.

  b) Capacity - represents the capacity supported by this specific switch.

  c) Type - represents the type of the switch placed in this arc.

3. Ri.dat
