---
layout: page
title: Distributed web service
description: Implementing multiple microservices that communicate securely via gRPC and Diffie-Hellman key exchange.
img:
importance: 1
category: Computer Science
related_publications: false
permalink: /projects/webhw1/
---

<span style="color:green; font-weight:bold;">🟢 This project is completed.</span>

In this project, I implemented a **distributed web service** composed of multiple microservices that communicate using the **gRPC protocol**.  
To ensure secure communication between services, the system employs **Diffie-Hellman key exchange** to establish shared symmetric keys.  

Key features:
- **Microservices Architecture:** Each service handles a specific task and communicates with others through gRPC.  
- **Secure Communication:** Diffie-Hellman key exchange ensures encrypted messaging between services.  
- **Load Testing:** Locust scripts simulate multiple clients to evaluate performance.  
- **Containerized Deployment:** Docker and docker-compose enable isolated and reproducible environments for each service.

<a href="https://github.com/royadaneshi/webHW1" target="_blank">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Repository" width="40" style="vertical-align:middle; margin-right:8px;">
  View on GitHub
</a>
