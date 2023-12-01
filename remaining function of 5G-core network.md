# Network repositery function(NRF)
<img width="1440" alt="Screenshot 2023-12-01 at 10 45 24 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/d88a6fd4-2919-46a4-b4c7-306a1b6059a9">

- NRF maintain list of profile of network function available in the 5G core network

     - for example:- NSSF wants to know where the function of AMF is located it will send the discovery request to the NRF and NRF response by returning the IP address and domain name of server of the server that network function is located
 
- All the network function register themselves with the NRF so that NRF functionality there Discovery by the other network function

# network slice selection function (NSSF)
<img width="1440" alt="Screenshot 2023-12-01 at 11 00 46 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/238e8ecd-e2d8-4e85-ab05-008f4e332325">

- In case UE register with AMF but this UE want to use services that is not in AMF like network slicing function so this AMF invoke the NSSF and NSSF basically inform this UE about network slicing and what AMF provide services so that this mobile avail the services like slicing by connecting to that other AMF

- This in NSSF is new to 5G because of the admint of network slicing is not in the previous mobile network
