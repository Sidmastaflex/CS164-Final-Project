# CS164-Final-Project
CS164 Computer Networks Final Project - Fall 2018 - Mini Facebook

## Overview
This program uses mininet and VirtualBox to emulate a network topology that consists of one server and three client nodes to implement a simple 'Facebook-like' application using the client-server model. Clients C1-C3 run client code to connect to and interact with the server and the server authenticates users and manages posts and messages from the users.

## How To Run:
- Download mininet to VirtualBox and change its network to 'NAT Network'
- Copy finalTopol.py, server.py, and client.py into mininet
- in mininet, run this command: 'sudo mn --custom finalTopol.py --topo finaltopol -x'
- Run this command on 'host: H1' to start the server: python server.py
- Run this command on any client 'host: C(1-3)' to connect a client to the server: python client.py

## What it does
In this program a client can:
- Send global or private messages
- Manage a friends list
- Post a status to their timeline
- View their timeline, which consists of status updates from the client and their friends in chronological order

## Logins
Logins are currently hard coded and are listed here as Username, Password:
- sid, bang
- user, pass
- man, man
