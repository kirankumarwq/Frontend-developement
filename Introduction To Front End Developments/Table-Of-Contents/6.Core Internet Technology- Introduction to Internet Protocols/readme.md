# Core Internet Technology

## Introduction to Internet Protocols

### Understanding IP Addresses and Data Transmission on the Internet

#### The Internet and the Postal System Parallel
- Data transmission on the internet is comparable to how the postal system works.
- **IP addresses** function like mailing addresses, enabling data packets to be delivered between computers.

#### What Are IP Addresses?

- **Definition**:
  - An IP (Internet Protocol) address is a unique identifier assigned to each computer on a network.
  - Essential for locating and communicating with devices on the internet.

- **Types of IP Addresses**:
  1. **IPv4**: Contains four octets separated by periods (e.g., `192.0.2.235`).
  2. **IPv6**: Contains eight groups of hexadecimal digits separated by colons (e.g., `4527:0a00:1567:0200:ff00:0042:8329`).

### How Data Is Sent Across the Internet

#### Data Packets
- Data is transmitted in units called **IP packets** or **datagrams**.
- Each packet contains:
  - **Header**: Includes the destination IP address, source IP address, and other delivery information.
  - **Payload**: The actual data being sent.

#### Sending Data
- Similar to mailing a letter, the header includes both the sender’s and recipient’s IP addresses.
- The payload carries the data, along with additional protocols for managing delivery.

### Common Issues in Data Transmission

#### Potential Problems:
- Packets may arrive **out of order**.
- Packets could become **damaged or corrupted** during transit.
- Some packets may be **dropped or lost**.

#### Solutions with Protocols:
- **Transmission Control Protocol (TCP)**:
  - Ensures data arrives in order, without corruption or loss.
  - Adds a slight delay but guarantees reliability.
  - Ideal for tasks requiring accuracy, like sending text or image files.

- **User Datagram Protocol (UDP)**:
  - Addresses corruption but allows out-of-order delivery or dropped packets.
  - Optimized for speed, making it ideal for activities like voice calls or live video streaming.

### Key Takeaways
- **Internet Protocol** governs data transmission, similar to how the postal system handles mail delivery.
- **IP addresses** serve as unique identifiers, ensuring packets reach the correct destination.
- **TCP** and **UDP** manage data reliability and speed, catering to different types of online activities.

