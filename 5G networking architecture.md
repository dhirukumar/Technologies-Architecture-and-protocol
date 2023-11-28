# next generation node B(gnB) function in 5G
## 5G architecture
<img width="1440" alt="Screenshot 2023-11-28 at 7 28 03 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/45c0cda2-811e-4690-b0eb-65a327023b7e">
- gNB is responsible for communication with UE on wireless Channel.

- Data sent by gnb is encrypted and UE decrypted the data.

- Data sent by gnb is compressed and decompressed by UE

- we know about two type of signaling.
    - Access stratum signaling:-The signaling transmit or received between UE and gnb
        - example during phone call
    - Non access stratum signaling:-The signaling done between UE and core network gnb does not process the non excess stratum signal
<img width="1440" alt="Screenshot 2023-11-28 at 7 28 13 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/ac02f32e-6d3b-4cdd-882d-573a2811d89f">

- - Radio Resource Management:- Same time a gNB is responsible to assign resource block and what data speed and quality of services and other resources to Many UE that control by radio Resource Management
-    - Power control:- at what power gNB transfer data to UE and same time at what power UE will transfer data to gNB to avoid interference between gnb and UE known as power control

  - gNB is connected to core Network and nearby base station because when you we enter in near base station so first gnb is responsible to handover UE to next gnb and this process called handover

- The connection between gnb and nearby gnb is known as Xn interface

## packet data unit (PDU) session
<img width="1440" alt="Screenshot 2023-11-28 at 8 25 18 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/fdf52479-a809-4c70-b313-f1b2c1ca83b3">

- In 5G all type of data like message, voice message and file transfer is held by the help of IP address.

- For providing all IP system gNB established PDU session.

- each PDU session consist one or more QOS flow.

- In case of one single UE use more than one QOS at a same time like:- you send message with the help of UE and same UE on video call so message takes one QOS flow and video call takes another QOS flow.

- QOS depands Upon data rate, latency and priority

- priority:- it refer when we use tow service at same time like video call and text message so video call is more prior with the comparison of text message

- each QOS has there on unique QOS ID

## what is meant by control plane and user plane sepration in 5G
<img width="1440" alt="Screenshot 2023-11-28 at 8 51 16 PM" src="https://github.com/dhirukumar/Technologies-Architecture-and-protocol/assets/146316525/72b05c62-f7d3-48ff-8e40-11506cd1dde6">

- All the entity above the dotted line is lie under control plane

- All the entity under the dotted line is lie under the user plane

- gNB,UPF,Data network they are directly involved in data traffic forwarding data does not flow above the dotted line but it is handle by the entity below the dotted line

- Other functionality are fall in the control plane like in the following:-
     - Authentication of UE weather it is valid user or not there is in the control plane
 
     - The connectivity management is held in control plane
 
     - How QOS quality and PDU flow all those function is in control plane
 
     - when UE Enter in next gNB so handover process also take place in control plane.
 
- What is  advantage of separating control plane and user plan the main advantage is scalability

- In case of a UE need more data rate in user plane we generate one more PDU session or we increase the capacity of existing PDU session or increase the capacity of gNB 













