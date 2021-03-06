---
title: Basic of Computer Network for Software Engineer
published: true
categories: ["Network", "communication"]
tags: ["Network", "HTTP", "TCP"]
layout: blog
thumbnail: "/assets/blog/communication/network-thumb.jpg"
image: "/assets/blog/communication/network.jpg"
description: Knowledge of basic networking and understanding the basic terminology of network is very helpful for software engineer. A big picture view of the network system will give you confident and capability of identifying problem faster.
---

## OSI Model 
<div class="row">
  <div class="col-12 col-md-7">
    <p>{{site.data.blog.network.osi.intro}}</p>
    <h3>The Problem OSI Model Solve</h3>
    <p>{{site.data.blog.network.osi.problem_solved}} </p> 
    <a class="btn btn-link text-success" href="/blog/network/communication/2020/12/28/osi-model.html">Read More About OSI Model</a>
  </div>
  <div class="col-12 col-md-5">
    <img class="img img-thumbnail" style="width:100%" src="/assets/blog/communication/osi/layers.png"/>
  </div>
</div>




--- 

## IP Address
---

## MAC Address
12 Digit Alpha Numerical Number Added in `Network Interface Card` of a Computer by The computer menufacturer. MAC Stand For `Media Access Control`, it identify the device in a local network. Generally mac address does not change. 

Router use MAC address to indentify device for receiving packet. Mac address has two section first is for OUI or "Organizatioally Unique Indentifire", It's Indentify Vendoer. Last segment is a unique number assigned by the vendor, which make the device unique. 

---
## Port 
One computer to communicate with other computer with endpoint / ip address. But if in a computer there are multiple software is running on a single computer such as web server, email server or etc. to specifically point the software in a endpoint/host compoter we use port. 

Port is a logical construct, it indentify a process of an system.

There are 1024 port, which are defined for commonly known program. 

Logical construct that identify an process of an system. A port is identified for each transport protocol and address combination by a 16-bit unsigned number, known as the port number. A port number is always associated with an IP address of a host and the type of transport protocol used for communication. It completes the destination or origination network address of a message. Specific port numbers are reserved to identify specific services so that an arriving packet can be easily forwarded to a running application.
[https://en.wikipedia.org/wiki/Port_(computer_networking)]
---




## Sockets
A network socket is a software structure within a network node of a computer network that serves as an endpoint for sending and receiving data across the network. The structure and properties of a socket are defined by an application programming interface (API) for the networking architecture. Sockets are created only during the lifetime of a process of an application running in the node.
[https://en.wikipedia.org/wiki/Network_socket]
---



## IPC (Inter Process Communication) 
It's the communication protocol between two processes. they used shared memory and also messaage passing system when try to communication. 
---




## RPC (Remote Procedure Calls)
RPC is a protocol that allow us to communicate with different program located on different network, without knowing the network details. 

In RPC it use message based communication scheme, and messages are structured. 

RPC listend to a port on a remote system
---


## NAT (Network Address Translation)
It's a process to mapping a ip address to another ip address. 
-----


## TCP 
-------


## UDP
----

## ARP (Adress Resolution Protocol)
---

## HTTP
-------


## HTTP2
-------

## Web Server
---

## Email Server
---

## VOIP
---
