# Hosting-a-Web-App-on-Google-Cloud-Platform-Using-Compute-Engine
🚀 Deploying Websites on Google Cloud – Overview

There are multiple ways to deploy websites on Google Cloud, each offering its own level of flexibility, control, and operational overhead.
Compute Engine provides the highest degree of infrastructure control—allowing you to manage virtual machines, networking, load balancers, storage, and scaling. However, this also means slightly more operational effort compared to managed platforms like Google Kubernetes Engine (GKE) or App Engine.

In this lab, you will deploy a sample e-commerce application called “Fancy Store” using Compute Engine to understand how to deploy and scale a website with ease while retaining full operational control.

🎯 What You Will Learn

By completing this lab, you will gain hands-on experience in:

🖥️ Compute Engine & VM Management

Creating Compute Engine VM instances

Building instance templates from existing VMs

📈 Auto Scaling & Reliability

Creating Managed Instance Groups (MIGs)

Configuring auto-healing, auto-scaling, and rolling updates

Creating and validating health checks for MIGs

🌐 Load Balancing & Traffic Distribution

Setting up HTTP(S) Load Balancers

Associating health checks with load balancers

Routing traffic across regions/zones

⚡ Performance Optimization

Enabling Content Delivery Network (CDN) integration for website caching and global performance

🏁 Final Outcome

By the end of the lab, your website will be deployed on a fully automated, production-ready Google Cloud architecture with:

Load balancing

Auto-scaling

Auto-healing

Rolling updates

CDN caching

Your Compute Engine instance group will serve your website reliably under varying workloads with minimal manual intervention.
