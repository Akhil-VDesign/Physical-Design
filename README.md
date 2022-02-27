![Logo](https://user-images.githubusercontent.com/100471745/155844116-3cd2be63-bd70-424a-8bf1-34b06214d796.png)
# Physical-Design
5 Day Advanced Physical Design Workshop Using Openlane and Sky130
## Intro to open-source EDA, OpenLANE and Sky130 PDK
On the first day of the workshop
### OpenLANE ASIC FLow
![OpenLANE flow](https://user-images.githubusercontent.com/100471745/155844006-fe2d350a-6a33-4822-a4a8-17a2281993c5.png)

### Working on OpenLANE
![first time entering openlane](https://user-images.githubusercontent.com/100471745/155844418-5191b653-38de-4655-a424-a22d548fa3a2.png)


## PicoRV32 Layout and Floorplan
### Opening PicoRV32 Layout with Magic
![Opening Magic with layout](https://user-images.githubusercontent.com/100471745/155844643-763a01aa-89f0-4ebe-be76-f183ff34a3e3.png)

Zoomed Layout
![zoomed magic](https://user-images.githubusercontent.com/100471745/155844721-ea3fea82-2655-4c7d-950e-70b05904aeb9.png)
Layout After standered Cell Placement
![Standered cells are placed in placement run, also power rails can be seen placed](https://user-images.githubusercontent.com/100471745/155844800-cee75976-c703-40ff-b8db-f61683a91264.png)

### Inverter Layout
![Inverter Layout cloned from github](https://user-images.githubusercontent.com/100471745/155844879-f1c081ae-ccf5-4d78-bf18-927e3fdbc174.png)
Note: For an error as shown below, change the NMOS and PMOS instance name from X0 and X1 to M0 and M1
![error](https://user-images.githubusercontent.com/100471745/155844933-7224e01a-624d-43b9-86da-39354faca56b.png)
## NGSPICE run
![ng spice run 14](https://user-images.githubusercontent.com/100471745/155881248-c66c8ba4-a4ed-4be2-b7ee-4aa9dae175d3.png)
### inverter transient plot
![inverter out vs time transient plot](https://user-images.githubusercontent.com/100471745/155881305-fd1beac0-f69a-41b7-bc22-424c36b0a970.png)
### importing all files to picorv32a 
![importing all the necessary files to src foler of picorv](https://user-images.githubusercontent.com/100471745/155881320-91656c77-9233-448f-b496-eb960f808155.png)
### preparation with standered cell inv
![preparation with standered cell inv](https://user-images.githubusercontent.com/100471745/155881349-b19b676c-cc1b-4e42-9a24-74dc58b4ef61.png)
### synthesis succesful with standered cell inv
![synthesis succesful with standered cell inv](https://user-images.githubusercontent.com/100471745/155881372-1a41148f-5055-41db-8137-bbd59f91480c.png)

