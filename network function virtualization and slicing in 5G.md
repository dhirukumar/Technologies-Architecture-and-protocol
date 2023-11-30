# network function virtualization
<img width="1440" alt="Screenshot 2023-11-30 at 7 34 37 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/dc95c38f-2e54-4645-b673-234675945ef3">


 - Now we come to the network function virtualization now when you are taking example of the mobile networks for example for the 2G mobile network in the case of 2G mobile network you had the BTS that was controlled by the BSC and that was connected to the MSC all these network notes for actually built using special purpose hardware it was specialised hardware result it was expensive it was expensive to buy it was expensive to maintain and it was expensive to replace

 - network function provided implementation in software which is runing on COTS  (commercial of the shell) hardware such as service, storage and switches and this is easily available in the market what is specialised the software that is running on commercial of the shell(COTS)
<img width="1440" alt="Screenshot 2023-11-30 at 7 34 50 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/0648d4a3-7745-4725-97d5-7f57667156f2">

 - NFC Advantage in the following

    - the cost of both hardware and software reduce

    - easy for new vendor to enter in market because
  
    - far easier to upgrade the network by simply upgrading the software
  
  <img width="1440" alt="Screenshot 2023-11-30 at 7 34 59 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/2d4e95b0-98d7-45a2-920f-84dc558313bf">

  - On the top you have virtualize network function these are network function that are implemented on the software and they are the running on NFV architecture like computation , storage and network that are easier available in market and then there is a virtualized layer to virtualized all resources in virtual computation, and on top of virtualized resource and on top of  virtualized resources you have the software process running there are implemented the network functionality

  - If you talk about hardware resources , virtual resources and network function like (VNF1 VNF2 and VNF3) managed by network management and orchestion function(MANO)

  - In this diagram you seen user management in UDM is one VNF, mobility management function in AMF is one VNF, policy and charging in PCRF is one VNF and session management in SMF is One VNF that are running on NFV infrastructure which is best on COTS resources and this are managed by the (MANO)
<img width="1440" alt="Screenshot 2023-11-30 at 7 35 17 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/970deeca-8215-4945-a79a-86465057e154">

 - There are some advantage of NFV in 5G

     - 5G is a collection of network function that is virtualized on cloud infrastructure so it is easier accessible from every where

    - there is no custom hardware because it is running on COTS

    - it is easily deploy network function quickly because they are implemented on software

    - you can also scale up or a skill down resources as per requirement

        - for example if you want a scale up a AMF capacity in minute using MANO earlier it take very much time
     
  # network slicing
  <img width="1440" alt="Screenshot 2023-11-30 at 9 04 44 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/f3bc437a-0bd4-4182-8cf1-b8b6ae03e6da">

 - 5G network slicing is another key technology in 5G

 - With the help of slicing in 5G we built virtual end-to-end network on same physical network this end-to-end network called slice this Slice have different quality of services like mobile broadband in one of the Slice, similarly Messi machine type is another slice and mission control IOT is one other slice
<img width="1440" alt="Screenshot 2023-11-30 at 9 04 55 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/65e93328-f1cc-4800-b99e-8e99fa2ca147">

- This network slice is possible thanks to the NFV creation of multiple virtual network on same physical infrastructure

-   Why this slice is important in 5G network because different services have different quality of services(QOS) so different slice have different quality of services(QOS) for different services

-   One slice is used to optimise one use case

- slice is used to allocate of resource on demand as per requirement
