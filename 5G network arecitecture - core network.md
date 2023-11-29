# Access and mobality management function(AMF)

<img width="1440" alt="Screenshot 2023-11-29 at 7 44 14 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/2e60261f-63d1-42a0-994c-d9cc1bcec365">

- 5G core network divided into many function as you see in this diagram
## 1st function

- AMF=It is very similar to MME in LTE (4G) or VLR in GSM(Global system for mobile communication)(2G)

- When a UE switch on then their first process to register with the network and this registration function is done by the AMF

- Before register in AMF you needs to authentication and this authentication is initiated by AMF weather this user is valid or not

- UE has always in two type of modes

   - Ideal mode:- in this mode UE register with network but UE not on call in that case the location of this UE is know to the network at the tracking area level

       - Tracking area:- the cell in the 5G network divided into the tracking area a group of cell has one tracking area and another group of cell has another tracking area

- So, when a UE in ideal mode and UE change there tracking area in this case UE needs to update their tracking area so this function is also handling by AMF

- When a  UE on call  in this case you will change their tracking area so you has also need to update there tracking area so this function is also handling by AMF