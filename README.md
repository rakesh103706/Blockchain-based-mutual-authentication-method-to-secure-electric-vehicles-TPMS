TITLE EXPLANATION

Blockchain- Blockchain technology, known for its decentralized and tamper-resistant nature, offers
potential solutions for secure authentication in EV networks. Blockchain’s properties (e.g., immutability,
transparency, and consensus mechanisms) make it a suitable choice for building trust and preventing fraud.
Mutual Authentication- Mutual authentication is a process where two entities, like an EV and a charging
station, authenticate each other before sharing data or initiating any transaction. This verification ensures both
the EV and the charging infrastructure are verified.
Electric Vehicles (EVs)- EVs rely heavily on electronic systems for operation and efficiency. They have
advanced communication networks, making them more susceptible to cyberattacks compared to traditional
vehicles. Ensuring the security of interconnected systems, like TPMS, is crucial for EV safety and reliability.
Tire Pressure Monitoring System (TPMS)-TPMS is a critical system in vehicles that monitors the air
pressure inside tires and alerts the driver if the pressure falls below a safe threshold. Ensures vehicle safety
and efficiency. Often uses wireless communication to send data to the car's central system.



ABSTRACT

• Despite the widespread use of Radio Frequency Identification (RFID) and wireless connectivity such as
Near Field Communication (NFC) in electric vehicles, their security and privacy implications in Ad-Hoc
networks have not been well explored.
• This paper provides a data protection assessment of radio frequency electronic system in the Tire Pressure
Monitoring System (TPMS). It is demonstrated that eavesdropping is completely feasible from a passing
car, at an approximate distance up to 50 meters.
• Furthermore, our reverse analysis shows that the static n-bit signatures and messaging can be
eavesdropped from a relatively far distance, raising privacy concerns as a vehicles’ movements can be
tracked by using the unique IDs of tire pressure sensors.
• Unfortunately, current protocols do not use authentication, and automobile technologies hardly follow
routine message confirmation so sensor messages may be spoofed remotely. To improve the security of
TPMS, we suggest a novel ultra-lightweight mutual authentication for the TPMS registry process in the
automotive network. Our experimental results confirm the effectiveness and security of the proposed
method in TPMS.




INTRODUCTION

1.1 OVERVIEW
• The majority of cars are fitted with direct TPMSs. In order to measure tire pressure, these structures depend
on battery operated- powered pressure sensors within the tire and communicate their message signal through
a radio frequency (RF) transmitter.
• Bypenetrating into the wireless module, the attacker can eavesdrop on the TPMS sensors communication. It
also implement a shared ultra light weight RFID authentication mechanism for inclusion in a block chain
enabled TPMS to guarantee the data security. The implementation itself is a new concept and the suggested
technique gives security benefits toward potential attacks like spoofing, replay, and man-in-the-middle,
making sure the privacy of the information are been written to the public ledger of the block chain

1.2 PROBLEM STATEMENT

• The increasing reliance on wireless communication systems in electric vehicles (EVs), such as Tire Pressure
Monitoring Systems (TPMS), has introduced significant cybersecurity vulnerabilities.
• These systems are susceptible to attacks such as eavesdropping, spoofing, and unauthorized data tampering,
which can compromise the integrity of critical safety information and pose risks to vehicle operation and
passenger safety.
• Existing security mechanisms for TPMS often lack the robustness to address these threats comprehensively,
especially in the dynamic and distributed environments of modern EVs.
• There is a pressing need for a secure, efficient, and decentralized method to authenticate TPMS sensors and
ensure reliable communication with the vehicle's control system.



EXISTING SYSTEM

In 2019 proposed a model to secure the charging system in the electric vehicles. To this end, it suggests a
mutual authentication using Burrows– Abadi–Needham logic.
In relation to the prevailing distribution, suggested a random key pre-distribution strategy, in which every 
single node preserves a series of keys arbitrarily from the maximum allowable secret key. 
TESLA is a well-known authentication protocol used by wireless sensor networks (WSNs) to validate the 
broadcaster. Usually, validating a transmitted sender involves the use of asymmetric cryptographic algorithms 
(e.g., RSA), which is not really sufficient for resource-restricted sensor networks. 
With TPMSs, these key management systems do not function well, as sensor nodes in automotive network are
concerned with setting keys among a big numbers of sensors, whereas TPMSs concentrate on setting keys
among only four sensors and the Electrical Control Unit (ECU).
It also suggests to implement a shared ultra light weight RFID authentication mechanism for inclusion in a
blockchain-enabled TPMS to guarantee the data security.



DRAWBACKSOFEXISTINGSYSTEM

• More stringent computing operations can not also be performed, like creating the SHA-256 hash function 
and verifying the history of the commodity regarding the data contained in the block chain.
• Latency issue and real time constraints.
• Security compramises



PROPOSED SYSTEM

This paper focuses on tracking threats through listening to sensor identifiers and Denial Of Service (DOS)
attacks with message spoofing risks through injecting forged data into the tire monitoring device.
We would consider attacks where, by deliberately inserting forged messages, an attacker interferes with the
regular operations of TPMS. For instance, an attacker can attempt to submit a low-pressure packet to cause a
low-pressure alert.
If feasible, such attacks could weaken the confidence of drivers in the system and possibly contribute to fully 
neglect TPMS-related alerts.
In conclusion, even though tire sensors every time react to the corresponding activation signal, an attacker who
repetitively communicates activation signals can force tire sensors to transmit messages continuously, massively
reducing the life of TPMS.



ADVANTAGES OF PROPOSEDSYSTEM

• In order to create a chain of data according to the order in which they were created, blocks are connected in 
an ordered manner. The block relation is confirmed via the hash value of the block header data. 
• The blockchain uses this hash value as the individual identifier number for all blocks, and by the root block 
hash values determined in the block header, the unique related block can be found in the blockchain.




SYSTEM ARCHITECTURE

<img width="1711" height="745" alt="image" src="https://github.com/user-attachments/assets/1a333ca6-bfe9-4ce6-8d41-737e25e17cb5" />


SYSTEM TESTING

<img width="1390" height="752" alt="image" src="https://github.com/user-attachments/assets/68ecf19f-75ea-4fae-ba40-9fd3ff7f37bb" />

<img width="1380" height="776" alt="image" src="https://github.com/user-attachments/assets/77b87bac-4c03-440b-921d-e06be921c00f" />

<img width="1511" height="851" alt="image" src="https://github.com/user-attachments/assets/3d274321-b65d-4368-af40-d530c86f257a" />

<img width="1471" height="828" alt="image" src="https://github.com/user-attachments/assets/e27e1e85-a085-473d-a7cf-7491cb293226" />

<img width="1486" height="836" alt="image" src="https://github.com/user-attachments/assets/ce3c3a2e-cad5-4e23-baf0-d8546338d550" />

<img width="1549" height="872" alt="image" src="https://github.com/user-attachments/assets/16bf1c3c-46e6-45e7-aa31-7f07aa142334" />

<img width="1516" height="852" alt="image" src="https://github.com/user-attachments/assets/c701d87d-e3a2-4980-ba4b-726c59e30f2e" />





CONCLUSION

This study describes an effective Ultra light weight RFID Secure protocol with mutual authentication that is
integrated into a tire data monitoring system. TPMSs are one of the built-in wireless automotive networks
which are integrated into novel electric vehicles (EVs)
This paper assesses the venerable area in tire pressure monitoring systems by experimentally evaluating
representatives. Our study shows that spoofing attack can disable the normal operation of the tire monitoring
system.



FUTURE SCOPE

It is seen that the authentication methodology of the proposed method is cost effective in terms of storage,
computation, and communication. Finally, we present a secure block chain-based mutual authentication for
integration in the EVs network








