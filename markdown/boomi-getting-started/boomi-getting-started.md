author: Tamimi
summary: Getting started with Boomi and Solace
id: boomi-getting-started
tags:
categories: Boomi
environments: Web
status: Draft
feedback link: 
analytics account: UA-3921398-10

# Boomi featuring Solace

## 🤓 What you'll learn 
Duration: 0:02:00

In this tutorial, you will learn how to configure and use the Solace Boomi connector. This is done in 4 easy steps
1. Configure your Solace PubSub+ Event Broker (Hardware, Software, SasS)
1. Setup your Boomi platform
1. Configure the Solace connector in the Boomi platform
1. Send/Receive messages between Boomi and Solace

Positive
: Note that this tutorial is meant to be platform and programming language agnostic. Meaning that regardless what operating system you are running (Mac, Linux, Windows), programming languages or messaging AIPs you choose to use, the setup will be the same.

### Prerequisite 
This tutorial assumes:
* MacOS/Linux users have knowledge using Docker
* Access to a Solace broker (explained in Step 2)
* Access to a Boomi environment (explained in Step 3)

## 📌 Setup a Solace PubSub+ Broker 
Duration: 0:05:00

Access to a Solace messaging service, Solace PubSub+, can be achieved in either one of the three flavours
1. Hardware Appliance
1. Software broker image (Docker, Virtual image)
1. Solace Cloud service instance

This tutorial will walk you through setting up a Solace Cloud service instance. If you are interested in setting up a local broker running on Docker or a virtual machine check out the [PubSub+ Event  Broker: Software](https://docs.solace.com/Solace-SW-Broker-Set-Up/SW-Broker-Image-Setup.htm) documentation

### Sign up for free Solace Cloud account 
Navigate to the [Create a New Account](https://console.solace.cloud/login/new-account) page and fill out the required information. No credit card required!

### Create a messaging service
After you create your Solace Cloud account and sign in to the Solace Cloud Console, you'll be routed to the event mesh page.

![Solace Cloud Event Mesh Page](img/landing-page-event-mesh.png "Solace Cloud Event Mesh")


Click on 'Messaging Services' and all the messaging services associated with your account will show up if you have any already created. To create a new service, click either button as depicted in the image below:

![Solace Cloud Landing Page](img/landing-page-signup.png "Solace Cloud Landing Page")

Fill out all the details for your messaging service, and then click "Create" at the bottom of the page.

![Create Solace Cloud Messaging Service](img/create-service.png "Solace Cloud Messaging Service")

Your service should be ready to use in a couple seconds! 🌪

## 📌 Setup Boomi Platfrom 
Duration: 0:07:00

## 🛠 Configure Solace Broker 
Duration: 0:07:00

## 🛠 Setup Solace connector in Boomi 
Duration: 0:07:00

## Connect Everything!
Duration: 0:07:00

