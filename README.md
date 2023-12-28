# Computer-Networking
This project is intended to apply the concepts of computer networking to set up an enterprise network. In this project, I have established five different departments in a single building that include Admin, HR, and Finance, IT-Office, and CEO-office network. The distribution of devices among different departments is given by.

![Table1](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/2db0c03a-f2e4-4ae1-8aad-5281fec77e47)

Network Topology
The network is established on a hybrid topology. The network comprises three intermediate routers that serve to manage and route the traffic among the different departments. Each department has a switch that is connected to one of the intermediate routers. The visualization of the network hierarchy is given below:
 
![LabProject Topology](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/3ee93c7b-688e-4858-b510-9d67d489f165)

IP configuration
Each device in the network is statically assigned an IP address and enabled to connect with other devices within the network. The devices within a department will communicate with each other through the network switches. To transfer data among departments, the network has been configured to use PT-ROUTERS. These routers use Dynamic Routing, RIP to enable connections among multiple networks connected to them. The static IP configuration of each of the department is given below along with their default gateway.
Admin
![Table2](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/4d1c7ed8-dc05-4e60-a3be-f647ab4653b5)
 
HR
![Table3](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/2d74686c-0613-4fa4-af14-28831e5f8de2)

Finance
![Table4](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/338d9855-bef2-42cc-b561-512b77b02d76)

CEO-Office
![Table5](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/068b9d82-88a0-4ea2-a565-2dafe3fb174a)

IT-Office
![Table6](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/8a9a820b-da14-4aad-987d-a26bcf91f40e)

Router Configuration
The routers R1, R2, and R3 have been configured to allow traffic across department networks. The router R1 is connected to the Admin department Switch along with R2 and R3. The R2 serves to route the traffic from the Finance and HR department with the other departments through its connection with the routers R1 and R2. Similarly, R3 serves to route the traffic through the network directly connected to R3 and R1 along with the CEO Office and IT-Office. The router port configuration and network connectivity is given below.
Router-1
IP Conf.
![Table7](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/c73ce11a-d9aa-4c60-82f1-bafce3ecc3ff)

RIP Conf.
![Table8](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/79c2743c-43f3-4a02-b4fd-8b50ef3f0540)

![Router 1 Conf](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/5b7995eb-3696-4932-a379-359ec7871163)

Router-2
IP Conf.
![Table9](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/a129cce9-df06-4269-af6b-21805dd55376)

RIP Conf.
![Table10](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/52db479e-7631-4bfb-bc0e-ca401f558b4e)

![Router 2 Conf](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/d0f113cc-3e4c-432a-99b5-6ea718594560)

Router-3
IP Conf.
![Table11](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/0cd2f87e-4a40-4184-8c44-741e5e8a70cc)

RIP Conf.
![Table12](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/753d7060-8da4-4789-bb70-950694f46969)
 
![Router 3 Conf](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/6dd6a57b-2469-4fbf-80ae-e172966a4c73)


Test Ping
Ping Test Admin to IT-Office

![Ping Test Admin to IT-Office](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/dc0d2f1a-38da-439b-99f9-5cccf9ecb0f4)

 
Ping Test Finance to CEO-Office
 
![Ping Test Finance to CEO-Office](https://github.com/hamad-tariq/Computer-Networking/assets/113939608/d4ac1eb6-1e12-46d5-913d-d318df2959ec)
