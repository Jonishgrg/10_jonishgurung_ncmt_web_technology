# Web Technology  
## Assignment 1

**Student Name:** Jonish Gurung  
**Roll/ID No:** 10  
**Program:** BIT  
**Date:** 2025/12/18  

## CHAPTER 1: AN OVERVIEW OF THE INTERNET AND THE WEB

## Group A: Short Questions (2 Marks)

### 1. Define the term “Protocol” in the context of the Internet.
**Answer:**  
In the context of the Internet the term "Protocol" is a set rule that computer follows to communicate with each other on the internet.
Like, for example people need a common language to talk, computers need protocols so they know how the data should be sent, received, and understood.

### 2. What is the primary difference between a Web Browser and a Search Engine?
**Answer:**  
A web browser is a software application that is used to open and view websites. Without a browser,you connot access the web.A search engine is a tool or service that helps you search for information or websites on the internet. Browser is access tool Search engine is finding tool

### 3. Define the World Wide Web (WWW).
**Answer:**  
The World Wide Web (WWW) is a huge collection of web pages, images, videos, and other resources that are connected through links and stored on server aross the world.  
The Internet is the physical network (cables, routers, satellites), while the WWW is a service that runs on the internet, accessed using browers and web protocols.

### 4. Distinguish between a static web page and a dynamic web page.
**Answer:**  
A static web page is fixed. Every visitor sees the same content, and it only changes if a developer manually edits the file.  
Where as dynamic web page changes the contents itself or automatically without a manual procedures.

## Group B: Long Questions (4 Marks)

### 5. Explain the client-server architecture of the web with a neat diagram.
**Answer:**  
The client server architecture of the web is a model in which two types of computers communicate with each other i.e the client and server.
- The client is a device such as a cumputer or mobile phone that uses web browser like chrome, firefox or safari to request web pages or resources.  
- The server is a powerful computer that storesweb pages, images, data and responds to client request.
When a user enters a URL in a web browser, the browser sends an http reaquest to the web server.  
The server processes the request and sends back an http response containing the requested web page.  
This communication follows standard protocols suchc as http or https.

                            Client(Brower)   --->   Server(Web app) --->   Client(Brower)
                                              ^                       ^                  
                                              |                       |                   
                                        http request              http response

### 6. Describe the functions of the following Internet services: Email, FTP, and VoIP.
**Answer:**  
**i. Email:**  
Electronic Mail is known as Email in short term, It is an internet service that is used for sending & receiving message in a digital way.  
It allows users to exchange text, images, documeents, and other files over the internet.  
Email supports one to one and one to many communication and is commonly used for personal, educational, and professional communication.
**ii. FTP:**  
File Transfer Protocol is known as FTP in short term, It is an Internet service used for transfering files between a client and a server.  
It allows users to upload files to a server and download files from a server.  
FTP is commonly used for website hosting, sharing large files, and managing files on remote computers.
**iii. VoIP:**  
Voice over Internet Protocol is known as VoIP in short term, It is an Internet service that enables voice communication over the internet instead of traditional telephone networks.  
It converts voice signals into digital data packets and transmit them online.  
VoIP allows users to make voice and video calls at low cost or free, using application such as zoom, skype and whatsapp.
### 7. “The Internet is a network of networks.” Elaborate on this statement explaining how packet switching works.
**Answer:**  
The internet is called a "network of networks" becahse it is made up of millions of smaller computer networks connected together worldwide.  
These networks include home networks, school and college networks, company networks, Internet Service Providers(ISPs), and large backbone networks.  
All these independent networks are interconnected to form the global internet.
Packet switching is the technique used by the internet to transmit data.  
In packet switching, large data such as web pags, emails, or videos are broken into small units called packets.  
Each packet contains the source address, destination address anf a sequence number.  
These packets may take diferent paths through various routers and networks to reach the destination.  
At the destination, all packets are reassembled in the correct order to recontruct the original data.  
If any packet is lost during transmission, it is retransmitted.

## Group C: Scenario-Based Questions (5 Marks)

### 8. A startup company wants to host a website that displays the same information to all visitors and requires very low maintenance costs. As a consultant, would you agree? Justify your answer.
**Answer:**  
As a consultant, I would not agree with the advice to use a dynamic website for this requirement.  
Since the website displays the same information to all visitors and requires very low maintenance, a static website is more suitable.  
A static website consists of fixed web pages created using HTML and CSS.  
The content remains same fir every user and does not require a database or server-side processing.  
This makes static websites faster, more secure, and cheaper to host compared to dynamic websites.
Dynamic websites are useful when the content needs to change frequently, susch as user login systems, online shopping, or personalized content.  
They require server-side scripting, databases, and regular maintenance, which increases cost and complexity.  
Therefore, for a startup that needs a simple website with identical content for all users and minimal maintenance cost, a static website is the best choice rather than a dynamic website.

### 9. A user types www.google.com but gets “Server Not Found” error. Diagnose the problem.
**Answer:**  
The problem occurs due to the failure of the Domain Name System(DNS).  
DNS is the INternet service that translate human readable domain names such as www.google.com into numerical IP addresses like 142.250.190.46.  
When the user types www.google.com, the browser sends a DNS request to a DNS server to find the corresponding IP address.  
In this case, the DNS server fails to respond correctly or cannot resolve the domain name.  
When the user directly enters the IP address, the browser bypasses the DNS lookup process and connects directly to the server.  
Therefore, the underlying technology that failed is the Domain Name System(DNS).

### 10. Which network type should be used to share sensitive inventory data with suppliers?
**Answer:**  
The corporation should implement an Extranet for this purpose.
An Extranet is a private network that allows controlled access to authorized external users such as suppliers, partners, or vendors.  
It is protected by security mechanisms like user authentication, passwords, and encryption.  
An Intranet is restricted only to internal employees and the Internet is public, so both are unsuitable.  
Therefore, an Extranet is the most appropriate network type for securely sharing sensitive information with specific external partners.