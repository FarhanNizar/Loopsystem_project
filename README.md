# CFD02 - Loop Project

## Introduction
The Loop Project is the Capston project assignment of the course of Certified Fabric Developer - batch 02 (CFD02), the course conducted by "The BlockchainHub and University of York", the Loop Project was assigned to four students and this the group work of following students:  
#### 1. HJalmar
#### 2. Jane
#### 3. Farhan Nizar
#### 4. Mohammed Huda

## Introduction to Loop
Loop is a technology-driven freight forwarder. Loop eliminates the jargon associated with high volume shipping and creates a collaborative logistics environment. The platform provides an arena for real time tracking and visibility for shipments across the entire supply chain.

## Loop in Hyperledger Fabric 
Loop wants to adopt decentralized technologies in private network, Hyperledger Fabric provides the decentralized network and distributed ledger in private network, Loop is looking forward to integrate their business functionalities with Hyperledger Fabric.

## Loop Business Process
As Loop provides shipping solutions to handle high volume shipping and creates a collaborative logistics environemnt, following Actors are involved in Loop business process:
1. **Shipper** - Sending the Request for Quotation (RFQ) for shipment from one country to another
2. **Loop** - Forwarder to send quotation to specific shipment, and the quotation can contain updatable status (“Requested”, “Ready”, “Cancelled”, “Expired”)
3. **Buyer** - Receiver need the frequent update on shipment from Loop

## Features available in Current version
As part of Capston project assignment, we covered **Ordering use case** of Loop and implemented following fuctionalities:
1. Create dedicated Loop private fabric network
2. Create Sender-Loop channel
3. Deploye Ordering Chaincode to cover following options:
	a - Update order Status
	b - Update order Location
	c - Get order by ID
	d - Get order by Sender
	e - Get order by Location
	f - Get All active order
	g - Get order history

## Documentation, Getting Started and Developer Guides

Please visit online documentation for information on getting started using and developing with the fabric, SDK and chaincode:
- [v1.2](http://hyperledger-fabric.readthedocs.io/en/release-1.2/)
- [v1.1](http://hyperledger-fabric.readthedocs.io/en/release-1.1/)
- [v1.0](http://hyperledger-fabric.readthedocs.io/en/release-1.0/)
- [master branch (development)](http://hyperledger-fabric.readthedocs.io/en/master/)

It's recommended for first-time users to begin by going through the Getting Started section of the documentation in order to gain familiarity with the Hyperledger Fabric components and the basic transaction flow.

## Congigure Hyperledger Fabric Envrionment
Please visit the [installation instructions](http://hyperledger-fabric.readthedocs.io/en/latest/install.html)
to ensure you have the correct prerequisites installed. Please use the version of the documentation that matches the version of the software you intend to use to ensure alignment.

## Configure Loop Network
Please make sure you have Installed all **Prerequisites** of Hyperledger Fabric as stated in **Configure Hyperledger Fabric environment**
1: Fork loopsystem_project from following GITHUB repository: 
2: 
