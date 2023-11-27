# Key features of NG-RAN
<img width="1440" alt="Screenshot 2023-11-08 at 5 25 50 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/264bfcb0-daab-47cf-8a8d-5423fb6af03c">

### dual connectivity

-  dual connectivity :- dual connectivity is reffer to when your UE connect with two cell one is primary cell and another is sec cell 

  - primary cell is inportant for data rate and what type of service UE get
  - sec cell is inportant for

<img width="1440" alt="Screenshot 2023-11-08 at 5 28 00 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/6519c035-b9bf-4168-8e8b-91874b787dcb">

- We can have master node as 4G eNB that is connected to 4G core(EPC-Evolved packet core)

- Split bearer is the function that allows the split of data going to gNB from the core side into two paths
<img width="1440" alt="Screenshot 2023-11-08 at 5 29 23 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/3d9d747d-497f-446e-9f29-93f50a5f2a5f">

### Small cells in 5G networks

- Using dual connectivity it can connect to two cells which increases data rates.
  
-small cell coverage area 10 miter to 2k/m

- small cell is connected to macro cell

<img width="1440" alt="Screenshot 2023-11-08 at 5 31 47 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/0860dbd0-6d67-4aef-98e3-f23f1c619b57">

###  Increased wireless spectrum of 5G and its property
<img width="1440" alt="Screenshot 2023-11-08 at 5 43 22 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/cbac4c42-a5fa-49d7-9495-42f4499af89d">

- Lower frequencies have less attenuation with excellent building penetration but have limited availibility
  
- Range of 6-100Ghz is what called mmWave but attenuation is much higgher as compared to other frequencies
OFDMA

- when we increse the frequency the coverage are less and the spectrum avlibality is higher

### OFDMA

- Orthogonal frequency division multiple access

- In OFDMA the frequency band in is divided into sub carriers

- the connection between UE and GnodB is called air interface

<img width="1440" alt="Screenshot 2023-11-08 at 5 43 22 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/8d21f7cb-7417-44f4-8282-5c15b8311ad0">

<img width="1440" alt="Screenshot 2023-11-08 at 5 55 30 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/cda64030-4762-4f05-a0ff-c40c1e1b378e">

-  the space between two carrer subspacing is called def f

- flexible numerology is also know asscalable carrer spacing

- Flexible numerology is reffered by μ

<img width="1440" alt="Screenshot 2023-11-08 at 5 56 28 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/6ea4eba9-8fc3-4359-a2ce-c0bda0191af6">

- In case of 5G NR time is divided into FRAM which is space of 10 micro/sec

- IN case of 1 FRAM = 10 subfram with 1 micro/sec

- cyclic prefix= the time gap between one OFDM and another OFDM is know as cyclic prefix

- there are two type of cyclic prefix
    - normal
    - extended

- 1 slot=14 OFDM
<img width="1440" alt="Screenshot 2023-11-08 at 5 58 25 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/26133441-5284-41d6-ba6c-2847fb89fc8e">

### Resource Block and Resource elemment

- In 5G NR resource block is only defined in frequency domain and not in time domain having 12 consecutive block vertically
  
- In case of LTE resource block was defined in both frequency and time domains.

- As the spacing of sub carriers increased the duration of time slot is increased.

<img width="1440" alt="Screenshot 2023-11-08 at 6 26 08 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/c57ea899-016e-4b88-8298-6a3581f2f8c1">

####  Resource elemment

- It is defined in both time and frequency domain

![Screenshot 2023-11-27 at 4 44 57 PM](https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/e23b383b-5b86-47a5-8f77-481f033773bf)

### Modulation in 5G
- QAM- Quadrature amplitude modulation
  
- When the distance between UE and tower increases and if there are obstacles between them, we need to downgrade the modulation scheme.
  
- For example
    - 16 QAM= 4 bits per symbol
    - 256 QAM= 8 bits per symbol, i.e it is defined in the power of 2
<img width="1440" alt="Screenshot 2023-11-08 at 6 30 16 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/1fe9e7e2-803e-4fa0-b1ae-d56768f011d7">

#### Cloud RAN
<img width="1440" alt="Screenshot 2023-11-08 at 6 33 46 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/87594c4e-50e3-479f-add1-55b54fadbe58">

- latancy:- time taken to send a packet to recive packet is know as latency

- in cloud RAN DU is only is responsible for reciving/transmit the signal but all the process is held in CU
<img width="1440" alt="Screenshot 2023-11-08 at 6 34 20 AM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/7110ee4b-d10e-4174-b207-5db6a724555a">





