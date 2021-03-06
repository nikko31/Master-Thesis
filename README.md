# Master's Thesis
## Context-Based  Authentication  and  Lightweight  Group-Key Establishment Protocol for IoT Devices

The concept of the Internet of Things is driven by advancements of the Internet with the interconnection of heterogeneous smart objects using different networking and communication technologies. 
With the rapidly increasing number of interconnected devices present in the life of a person, providing authentication and secure communication between them is considered a key challenge.
The integration of Wireless Sensor Networks in the Internet of Things creates new obstacles due to the necessity of finding a balance between the resources utilization and the applied security solutions.
In multicast group communications, the energy consumption, bandwidth and processing overhead at the nodes are minimized in comparison to a point-to-point communication system.
To securely transmit a message in order to maintain confidentiality of the data and the user's privacy, usually involves human interaction or the pre-agreement upon some key, the latter unknown to an external attacker. 
In this thesis, the author proposed an authentication protocol based on the similar context between the correct devices and lightweight computationally secure group-key establishment, avoiding any kind of human involvement.
The goal is achieved by having the devices calculate a fingerprint from their ambient context and through a fuzzy commitment scheme generating a commitment respectively opening value which is used to generate a common secret key between them.
The tests are effectuated on real world data accumulated from different environments.
The proposed scheme is based on elliptic curve cryptography and cryptographic one-way accumulators. 
Its feasibility is analyzed by implementing the group key establishment phase in the Contiki operating system and by simulating it with the Cooja simulator. 
Furthermore, the applicability of the protocol is analyzed and justified by an analysis of the storage overhead, communication overhead, and energy consumption.
The simulator shows an energy consumption of only  112 mJ per node for group key establishment.
The results obtained in this thesis demonstrate the feasibility of the scheme and its computational and communication costs are further comparable to other similar approaches.
