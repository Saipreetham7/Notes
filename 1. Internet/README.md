# Internet

## Introduction to the Internet
A network is a group of computers or other devices which are connected to each other. All these networks when connected together form the internet.

<b><em>All these networks when connected together form the internet.</em></b>

## How the Internet Works: An Overview
At a high level, the internet works by connecting devices and computer systems together using a set of standardized protocols. These protocols define how information is exchanged between devices and ensure that data is transmitted reliably and securely.

The core of the internet is a global network of interconnected routers, which are responsible for directing traffic between different devices and systems. When you send data over the internet, it is broken up into small packets that are sent from your device to a router. The router examines the packet and forwards it to the next router in the path towards its destination. This process continues until the packet reaches its final destination.

To ensure that packets are sent and received correctly, the internet uses a variety of protocols, including the Internet Protocol (IP) and the Transmission Control Protocol (TCP). IP is responsible for routing packets to their correct destination, while TCP ensures that packets are transmitted reliably and in the correct order.

In addition to these core protocols, there are a wide range of other technologies and protocols that are used to enable communication and data exchange over the internet, including the Domain Name System (DNS), the Hypertext Transfer Protocol (HTTP), and the Secure Sockets Layer/Transport Layer Security (SSL/TLS) protocol.

## Basic Concepts and Terminology
- Packet: A small unit of data that is transmitted over the internet.
- Router: A device that directs packets of data between different networks.
- IP Address: A unique identifier assigned to each device on a network, used to route data to the correct destination.
- Domain Name: A human-readable name that is used to identify a website, such as google.com.
- DNS: The Domain Name System is responsible for translating domain names into IP addresses.
- HTTP: The Hypertext Transfer Protocol is used to transfer data between a client (such as a web browser) and a server (such as a website).
- HTTPS: An encrypted version of HTTP that is used to provide secure communication between a client and server.
- SSL/TLS: The Secure Sockets Layer and Transport Layer Security protocols are used to provide secure communication over the internet.

## The Role of Protocols in Internet
A protocol is a set of rules and standards that define how information is exchanged between devices and systems.

There are many different protocols used in internet communication, including the Internet Protocol (IP), the Transmission Control Protocol (TCP), the User Datagram Protocol (UDP), the Domain Name System (DNS), and many others.

IP is responsible for routing packets of data to their correct destination, while TCP and UDP ensure that packets are transmitted reliably and efficiently. DNS is used to translate domain names into IP addresses, and HTTP is used to transfer data between clients and servers.

One of the key benefits of using standardized protocols is that they allow devices and systems from different manufacturers and vendors to communicate with each other seamlessly. For example, a web browser developed by one company can communicate with a web server developed by another company, as long as they both adhere to the HTTP protocol.

## Understanding IP Addresses and Domain Names
An IP address is a unique identifier assigned to each device on a network. It’s used to route data to the correct destination, ensuring that information is sent to the intended recipient. IP addresses are typically represented as a series of four numbers separated by periods, such as “192.168.1.1”.

Domain names, on the other hand, are human-readable names used to identify websites and other internet resources. They’re typically composed of two or more parts, separated by periods. For example, “google.com” is a domain name. Domain names are translated into IP addresses using the Domain Name System (DNS).

DNS is a critical part of the internet infrastructure, responsible for translating domain names into IP addresses. When you enter a domain name into your web browser, your computer sends a DNS query to a DNS server, which returns the corresponding IP address. Your computer then uses that IP address to connect to the website or other resource you’ve requested.

## Introduction to HTTP and HTTPS
HTTP is the protocol used to transfer data between a client (such as a web browser) and a server (such as a website). When you visit a website, your web browser sends an HTTP request to the server, asking for the webpage or other resource you’ve requested. The server then sends an HTTP response back to the client, containing the requested data.

HTTPS is a more secure version of HTTP, which encrypts the data being transmitted between the client and server using SSL/TLS (Secure Sockets Layer/Transport Layer Security) encryption. This provides an additional layer of security, helping to protect sensitive information such as login credentials, payment information, and other personal data.

## Building Applications with TCP/IP
TCP/IP (Transmission Control Protocol/Internet Protocol) is the underlying communication protocol used by most internet-based applications and services. It provides a reliable, ordered, and error-checked delivery of data between applications running on different devices.

When building applications with TCP/IP, there are a few key concepts to understand:
- Ports: Ports are used to identify the application or service running on a device. Each application or service is assigned a unique port number, allowing data to be sent to the correct destination.
- Sockets: A socket is a combination of an IP address and a port number, representing a specific endpoint for communication. Sockets are used to establish connections between devices and transfer data between applications.
- Connections: A connection is established between two sockets when two devices want to communicate with each other. During the connection establishment process, the devices negotiate various parameters such as the maximum segment size and window size, which determine how data will be transmitted over the connection.
- Data transfer: Once a connection is established, data can be transferred between the applications running on each device. Data is typically transmitted in segments, with each segment containing a sequence number and other metadata to ensure reliable delivery.

When building applications with TCP/IP, you’ll need to ensure that your application is designed to work with the appropriate ports, sockets, and connections. You’ll also need to be familiar with the various protocols and standards that are commonly used with TCP/IP, such as HTTP, FTP (File Transfer Protocol), and SMTP (Simple Mail Transfer Protocol). Understanding these concepts and protocols is essential for building effective, scalable, and secure internet-based applications and services.

## Securing Internet Communication with SSL/TLS
SSL/TLS is a protocol used to encrypt data being transmitted over the internet. It is commonly used to provide secure connections for applications such as web browsers, email clients, and file transfer programs.

When using SSL/TLS to secure internet communication, there are a few key concepts to understand:
- Certificates: SSL/TLS certificates are used to establish trust between the client and server. They contain information about the identity of the server and are signed by a trusted third party (a Certificate Authority) to verify their authenticity.
- Handshake: During the SSL/TLS handshake process, the client and server exchange information to negotiate the encryption algorithm and other parameters for the secure connection.
- Encryption: Once the secure connection is established, data is encrypted using the agreed-upon algorithm and can be transmitted securely between the client and server.

When building internet-based applications and services, it’s important to understand how SSL/TLS works and to ensure that your application is designed to use SSL/TLS when transmitting sensitive data such as login credentials, payment information, and other personal data. You’ll also need to ensure that you obtain and maintain valid SSL/TLS certificates for your servers, and that you follow best practices for configuring and securing your SSL/TLS connections. By doing so, you can help protect your users’ data and ensure the integrity and confidentiality of your application’s communication over the internet.

## Client Server Architecture
![alt](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works/simple-client-server.png)

- Clients are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).

- Servers are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.

## What is the difference between web page, website, web server, and search engine?

### Web Page
A document which can be displayed in a web browser such as Firefox, Google Chrome, Opera, Microsoft Edge, or Apple Safari. These are also often called just "pages."

### Website
A website is a collection of linked web pages (plus their associated resources) that share a unique domain name. Each web page of a given website provides explicit links—most of the time in the form of clickable portions of text—that allow the user to move from one page of the website to another.

### Web Server
A web server is a computer hosting one or more websites. "Hosting" means that all the web pages and their supporting files are available on that computer. The web server will send any web page from the website it is hosting to any user's browser, per user request.

### Search Engine
Search engines are a common source of confusion on the web. A search engine is a special kind of website that helps users find web pages from other websites.

A browser is a piece of software that retrieves and displays web pages; a search engine is a website that helps people find web pages from other websites.

# WHat is HTTP
HTTP is a TCP/IP-based application layer communication protocol that standardizes how clients and servers communicate with each other.

It defines how content is requested and transmitted across the internet. By application layer protocol, I mean that it’s simply an abstraction layer that standardizes how hosts (clients and servers) communicate.

HTTP itself depends on TCP/IP to get requests and responses between the client and server. By default, TCP port 80 is used, but other ports can also be used. HTTPS, however, uses port 443.

## What is an HTTP Request?
An HTTP request is the way Internet communications platforms such as web browsers ask for the information they need to load a website.

Each HTTP request made across the Internet carries with it a series of encoded data that carries different types of information. A typical HTTP request contains:
1. HTTP version type
2. a URL
3. an HTTP method
4. HTTP request headers
5. Optional HTTP body.

### What is an HTTP method?
An HTTP method, sometimes referred to as an HTTP verb, indicates the action that the HTTP request expects from the queried server. For example, two of the most common HTTP methods are ‘GET’ and ‘POST’; a ‘GET’ request expects information back in return (usually in the form of a website), while a ‘POST’ request typically indicates that the client is submitting information to the web server (such as form information, e.g. a submitted username and password).

### What are HTTP request headers?
HTTP headers contain text information stored in key-value pairs, and they are included in every HTTP request (and response, more on that later). These headers communicate core information, such as what browser the client is using and what data is being requested.

Example of HTTP request headers from Google Chrome's network tab:

![alt](https://www.cloudflare.com/img/learning/ddos/glossary/hypertext-transfer-protocol-http/http-request-headers.png)

### What is in an HTTP request body?
The body of a request is the part that contains the ‘body’ of information the request is transferring. The body of an HTTP request contains any information being submitted to the web server, such as a username and password, or any other data entered into a form.

### What is in an HTTP response?
An HTTP response is what web clients (often browsers) receive from an Internet server in answer to an HTTP request. These responses communicate valuable information based on what was asked for in the HTTP request.

A typical HTTP response contains:
1. an HTTP status code
2. HTTP response headers
3. optional HTTP body

#### What’s an HTTP status code?
HTTP status codes are 3-digit codes most often used to indicate whether an HTTP request has been successfully completed. Status codes are broken into the following 5 blocks:

- 1xx Informational
- 2xx Success
- 3xx Redirection
- 4xx Client Error
- 5xx Server Error

The “xx” refers to different numbers between 00 and 99.

#### What are HTTP response headers?
Much like an HTTP request, an HTTP response comes with headers that convey important information such as the language and format of the data being sent in the response body.

Example of HTTP response headers from Google Chrome's network tab:

![alt](https://www.cloudflare.com/img/learning/ddos/glossary/hypertext-transfer-protocol-http/http-response-headers.png)

#### What is in an HTTP response body?
Successful HTTP responses to ‘GET’ requests generally have a body which contains the requested information. In most web requests, this is HTML data that a web browser will translate into a webpage.

# Domain Names
Domain names are a key part of the Internet infrastructure. They provide a human-readable address for any web server available on the Internet.

Any Internet-connected computer can be reached through a public IP Address, either an IPv4 address (e.g. 192.0.2.172) or an IPv6 address (e.g., 2001:db8:8b73:0000:0000:8a2e:0370:1337).

## Structure of domain names
A domain name has a simple structure made of several parts (it might be one part only, two, three…), separated by dots and read from right to left:

![alt](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_domain_name/structure.png)

### TLD (Top-Level Domain)
TLDs tell users the general purpose of the service behind the domain name. The most generic TLDs (.com, .org, .net) don't require web services to meet any particular criteria, but some TLDs enforce stricter policies so it is clearer what their purpose is. For example:
- Local TLDs such as .us, .fr, or .se can require the service to be provided in a given language or hosted in a certain country — they are supposed to indicate a resource in a particular language or country.
- TLDs containing .gov are only allowed to be used by government departments.
- The .edu TLD is only for use by educational and academic institutions.

TLDs can contain special as well as latin characters. A TLD's maximum length is 63 characters, although most are around 2–3.

### Label (or component)
The labels are what follow the TLD. A label is a case-insensitive character sequence anywhere from one to sixty-three characters in length, containing only the letters A through Z, digits 0 through 9, and the '-' character (which may not be the first or last character in the label). a, 97, and hello-strange-person-16-how-are-you are all examples of valid labels.

The label located right before the TLD is also called a Secondary Level Domain (SLD).

A domain name can have many labels (or components). It is not mandatory nor necessary to have 3 labels to form a domain name. For instance, informatics.ed.ac.uk is a valid domain name. For any domain you control (e.g. mozilla.org), you can create "subdomains" with different content located at each, like developer.mozilla.org, support.mozilla.org, or bugzilla.mozilla.org.

## How does a DNS request work?
1. Type mozilla.org in your browser's location bar.
2. Your browser asks your computer if it already recognizes the IP address identified by this domain name (using a local DNS cache). If it does, the name is translated to the IP address and the browser negotiates contents with the web server. End of story.
3. If your computer does not know which IP is behind the mozilla.org name, it goes on to ask a DNS server, whose job is precisely to tell your computer which IP address matches each registered domain name.
4. Now that the computer knows the requested IP address, your browser can negotiate contents with the web server.

![alt](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_domain_name/2014-10-dns-request2.png)

