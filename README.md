Internet frame
	1. Preamble: Đồng bộ clock
	- Length: 7 bytes
	- Pattern: 10101010
	2. SFD: Start Frame Delimiter: Start of frame - similar to SOF of CAN
	- Length: 1 bytes
	- Pattern: 10101011
	3. Destination MAC
	- Length: 6 bytes
	- Example: 00:11:22:33:44:55
	- Meaning: Who is this frame being sent to?
	4. Source MAC: - similar to Identifier of CAN 
	- Length: 6 bytes
	- Example: AA:BB:CC:DD:FF
	5. EtherType
	- Length: 2 bytes
	- IPv4: 0x0800
	- IPv6: 0x86Đ
	- ARP: 0x0806
	6. Payload (Data)
	- HTTP Request
	- UDP packets
	- TCP packet
	- SOME/IP Message
	- DoIP message
	7. FCS: Frame check sequence
	- Length: 4bytes
	- CRC32
	- Detect transmission error
	

SMI:
- Definition: SMI (also called MDIO) is a 2-wire serial bus used to read/write registers inside Ethernet PHYs and switches. Every transaction on the bus produces one "frame" in your trace.
- Definition: SMI (also called MDIO) is a 2-wire serial bus used to read/write registers inside Ethernet PHYs and switches. Every transaction on the bus produces one "frame" in your trace.
<img width="943" height="341" alt="image" src="https://github.com/user-attachments/assets/51ddb007-3765-4701-8b2b-cbc2f3fe99fc" />
