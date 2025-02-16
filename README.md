# Load-Balancers-and-Auto-Scaling-group-in-AWS

Introduction

Imagine Load Balancers as traffic directors, making sure every visitor to your website gets where they need to go without any jams. And when the crowd starts pouring in, Auto Scaling Groups kick into gear, bringing in extra servers to handle the rush.

# Project Goals:

- Understand the concepts of High Availability and Scalability in cloud computing.
- Learn about Load Balancers and Auto Scaling Groups in AWS.
- Gain practical experience setting up an Application Load Balancer (ALB) and configuring Auto Scaling Groups (ASG) in AWS.
- Explore the importance of load balancing and auto-scaling in maintaining the reliability, availability, and performance of web applications.

# Learning Outcomes:
- Understand the concepts of High Availability, Scalability, Load Balancers, and Auto Scaling Groups.
- Learn how to create target groups and set up an Application Load Balancer to evenly distribute incoming traffic across multiple servers.
- Gain knowledge of configuring Auto Scaling Groups to automatically adjust the number of instances based on demand.
- Acquire troubleshooting skills to identify and resolve issues related to connectivity, security groups, and instance health in AWS.

# What is scalability?

Scalability is like beind able to handle growth without breaking a sweat. Imagine vou have a small bakery, and suddeny, you get a lot more customers than expected. Scalability means you can
quickly bake more bread and pastries without the bakery falling apart. In tech, it's similar to set up your systems so that they can handle more and more users or customers without crashing or
slowing down. So, whether it's adding more servers to your website during a big sale or making sure your app can handle a sudden surge in downloads, scalability ensures everything runs smoothly.
Let's understand some terms before going ahead with our practical.

1. Server: Its like a big computer that stores and shares stuff, like websites or apps, with other computers
   
2. Client: This is your computer or phone, asking the server for stuff, like loading a web page or using an app.

![image](https://github.com/user-attachments/assets/47b37aaa-7747-4d76-9873-f4d086a4a3e8)

![image](https://github.com/user-attachments/assets/1f4c270e-e05b-40e0-bb10-981bb2e52f57)

3. Traffic: Think of the "busy road" as the network infrastructure, like highways and streets, that connects servers (where websites and apps are hosted) to clients (like your computer or phone). It's where data packets travel back and forth, carrying information between the servers and the clients.
4. Redundancy: This is like having backups for important stuff, just in case something breaks. It's like having spare parts for your bike so you can keep riding even if something breaks.
   
6. Server Load: Imagine a server like a superhero carrying heavy bags of data. Server load is like how heavy those bags are. Too many bags can slow the superhero down!
7. Routing: Routing refers to the process of determining the best path for data packets to travel from their source (like a server) to their destination (like a client device). It's like finding the most efficient route on a map to reach your destination while avoiding traffic jams and roadblocks. Routing ensures that data packets reach their intended destination quickly and reliably across the network..


