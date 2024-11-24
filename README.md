# DevOps-Course-2024
This repository showcases the concepts, tools, and practices I learned during the DevOps Course FALL-2024, taught by @Saim Safdar. The repository also includes summaries of three blogs I authored on Medium, highlighting my understanding of DevOps concepts and practices.

# What I have learned
In this course, I acquired hands-on experience with various DevOps tools and practices, including but not limited to:

Version Control: GitHub
Containerization: Docker
Orchestration: Kubernetes, Istio
Cloud Services: ECS/EKS (got to play around with AWS)
Infrastructure as Code (IaC):
Terraform
Policy as Code: Kyverno
Serverless Frameworks: Knative
Networking: Ingress
Automation: GitHub Actions
These tools and practices provided me with the foundation to work efficiently in modern DevOps environments, emphasizing scalability, reliability, and automation.

# Blog 1
**A Beginner’s Guide to Kubernetes: Orchestrating Containers for Modern Applications**
This blog provides a comprehensive introduction to Kubernetes, a powerful tool for managing containerized applications. It explores why Kubernetes is essential for modern applications and explains its core components and benefits.

What I Learned
Kubernetes Basics:

Open-source container orchestration platform for deploying, scaling, and managing containers.
Manages distributed infrastructure across physical, virtual, cloud, or hybrid environments.
Why Kubernetes Matters:

Solves common container challenges like manual scaling, static networking, and lack of self-healing in Docker.
Offers automated scaling, self-healing, load balancing, rolling updates, and rollbacks.
Core Concepts:

Nodes & Clusters:
Clusters consist of master nodes (manage the system) and worker nodes (run containers).
Pods:
The smallest deployable unit, acting as a wrapper for one or more containers.
Deployments:
Declarative configurations for scaling, updating, and managing applications.
Services:
Provides stable endpoints for accessing pods, regardless of their lifecycle.
Ingress:
Manages external HTTP/S traffic, enabling routing and SSL termination.
ConfigMaps & Secrets:
Manage application configurations and sensitive data securely.
Horizontal Pod Autoscaling (HPA):
Automatically adjusts the number of pods based on resource metrics like CPU usage.
How Kubernetes Works:

Key Components:
API Server, etcd, Scheduler, Controller Manager, and Kubelet.
Ensures application resiliency, scalability, and ease of deployment.
Benefits of Kubernetes
Portability: Abstracts infrastructure, enabling flexibility across environments.
Scalability: Dynamically adjusts resources based on demand.
Resiliency: Self-healing features ensure application uptime.
DevOps Integration: Seamlessly integrates with CI/CD pipelines.
Conclusion
Kubernetes revolutionizes the management of containerized applications, making it necassary for modern, distributed systems. Whether you're running a small web app or a complex microservices architecture, Kubernetes provides the tools for efficient operation.

Link to medium: [A Beginner’s Guide to Kubernetes: Orchestrating Containers for Modern Applications](https://medium.com/@mibrahimzia48/a-beginners-guide-to-kubernetes-orchestrating-containers-for-modern-applications-1785aca50a67)

# Blog 2
**Deploying AWS Infrastructure with Terraform: A Step-by-Step Guide**
Terraform is an Infrastructure-as-Code (IaC) tool that enables efficient deployment and management of cloud resources. This guide provides a step-by-step overview of provisioning an EC2 instance on AWS using Terraform. The process includes installing Terraform, configuring AWS credentials, writing a basic configuration file (`main.tf`), and executing commands to initialize, plan, and apply the configuration.

With Terraform, you can automate infrastructure tasks, ensure consistency, and scale resources effectively. The tool also simplifies resource teardown through its `terraform destroy` command, making it easy to manage and clean up your cloud environment.

By following this guide, you can streamline the deployment process and gain hands-on experience with Terraform's capabilities, empowering you to handle cloud infrastructure more efficiently.

Link to medium: [Deploying AWS Infrastructure with Terraform: A Step-by-Step Guide](https://medium.com/@mibrahimzia48/deploying-aws-infrastructure-with-terraform-a-step-by-step-guide-d1a4d71bdec7)

# Blog 3
**Setting Up a Monitoring System with Prometheus and Grafana**
This guide explains how to set up a monitoring system using Prometheus and Grafana. First, you install Prometheus, configure it to scrape metrics (e.g., from Node Exporter), and run it on your system. Next, Grafana is installed, and Prometheus is added as a data source for visualization. Dashboards are created to monitor system metrics, and alerts are configured to notify on thresholds, such as high CPU usage. The setup ensures proactive monitoring, allowing you to analyze real-time data, set up alerts, and improve observability for your applications.

Link to medium: [Setting Up a Monitoring System with Prometheus and Grafana](https://medium.com/@mibrahimzia48/setting-up-a-monitoring-system-with-prometheus-and-grafana-e67a78d17c4a)

# Links
🌐 Platforms
# Medium
Discover my articles and insights:
[Visit Medium Profile](https://medium.com/@mibrahimzia48)

# GitHub
Explore my projects and contributions:
[Visit GitHub Profile](https://github.com/muhammad-12345)

# LinkedIn
Connect with me professionally:
[Visit LinkedIn Profile](www.linkedin.com/in/muhammad-ibrahim-zia-150ab5242)
