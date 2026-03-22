# Network Protocols

## 1. HTTP (Hypertext Transfer Protocol)
- **Description**: HTTP is an application protocol used for transmitting hypermedia documents, such as HTML. It is the foundation of data communication on the World Wide Web.
- **Port**: 80
- **Example Implementation**: To request a webpage in a browser, a user types a URL (e.g., https://example.com) which sends an HTTP GET request to the server.

## 2. HTTPS (HTTP Secure)
- **Description**: HTTPS is the secure version of HTTP. It uses encryption to protect the integrity and confidentiality of data between the user's computer and the site.
- **Port**: 443
- **Example Implementation**: Online transactions on e-commerce websites use HTTPS to protect user credit card information.

## 3. FTP (File Transfer Protocol)
- **Description**: FTP is used for transferring files between a client and server on a network. FTP allows users to upload and download files easily.
- **Port**: 21
- **Example Implementation**: Web developers often use FTP to upload their website files to a web server.

## 4. SMTP (Simple Mail Transfer Protocol)
- **Description**: SMTP is a protocol for sending emails. It is a text-based protocol that facilitates the sending of messages from a client to a server.
- **Port**: 25
- **Example Implementation**: Sending an email via a web-based email client uses SMTP to transmit the message to the recipient's email server.

## 5. DNS (Domain Name System)
- **Description**: DNS translates human-friendly domain names into IP addresses. This system allows users to access websites using domain names instead of numerical IP addresses.
- **Port**: 53
- **Example Implementation**: When a user types in https://www.example.com, DNS servers translate it to the corresponding IP address.

## 6. DHCP (Dynamic Host Configuration Protocol)
- **Description**: DHCP is used to dynamically assign IP addresses to devices on a network, allowing them to communicate efficiently.
- **Port**: 67 (server), 68 (client)
- **Example Implementation**: When a device connects to Wi-Fi, it automatically receives an IP address from the DHCP server.

## 7. TCP (Transmission Control Protocol)
- **Description**: TCP is a connection-oriented protocol that ensures the reliable transmission of data between devices.
- **Port**: 6 (not an application port, but a transport layer protocol)
- **Example Implementation**: Sending a file over the Internet typically uses TCP to ensure that the entire file is transmitted correctly.

## 8. UDP (User Datagram Protocol)
- **Description**: UDP is a connectionless protocol that allows fast transmission of data but does not guarantee delivery or order.
- **Port**: 17 (not an application port, but a transport layer protocol)
- **Example Implementation**: Streaming video or gaming applications use UDP for faster data transmission, accepting potential packet loss.

---

This file provides a comprehensive overview of common network protocols, their functions, ports used, and practical implementation examples. 
