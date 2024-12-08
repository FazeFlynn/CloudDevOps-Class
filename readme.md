14 Sept 2024
---------------------------------------------
Agile Framework:-
    1. To deliver the efficient Modules in time
    2. Enchances Collaboration and Adabtability

Scrum FrameWork:-
    1. On priority (Sprint) time period.
    2. Sprint review
    3. Retrospective process
    4. Rigid framework because it is time bound

Canwan FrameWork:-
    1. There is not time limit in this ie there is no sprint here  
    2. It depends on the time that you take to complete the time  
    3. It is Flexible framework because we are not bounded by time  
    4. It focuses on efficiency of work rather than the time  



19 Sept 2024 - Sandhya mam
-----------------------------------------------------------------------------
# CI/CD Pipeline:- Contineous Integration and Contineous Delivery/Deployment
    
    VCS: Tracks changes and enhances collaboration like github and git
        when we commit our project to git and pipeline formed (CD Pipeline started)



Topics for exams
-----------------------------
Unit 1 (Every topic) - ISE
defination and histroy of devops
importance of devops
agile develpoment framework

lecture 1 2 3 full 



20 Sept 2024 - Sandhya Mam
--------------------------------------------------------------------------------------------
# Creating, Testing, Deployment

CI Prelims - 
            Version Control System
            Virtual Machine
            Hosted CI Tools
            CI Tools


Cotineous Deployment - 

IAC (Infrastructure as Code) - 
                            Server Provisioning - How many server are needed for our System as per requirements
                                
---

# 9 November - Ashad Sir

## Topic -`Kubernetes` - `Used to Manage and Track Containers`

- we can install it in command line and then use it
- It guides multiple containers

---

# Containers

A **container**  is a lightweight, standalone unit that packages an application and its dependencies (libraries, binaries, configuration files) together, ensuring that it runs consistently across different computing environments.
### Why Do We Need Containers? 
 
1. **Consistency Across Environments** :
  - Containers ensure that an application behaves the same way in development, testing, and production environments because it includes everything needed to run the app.
 
2. **Isolation** :
  - Each container runs in its own isolated environment, avoiding conflicts between applications (e.g., different versions of the same library).
 
3. **Efficiency** :
  - Containers share the host operating system's kernel, making them faster and more efficient than virtual machines (VMs) because they use fewer system resources.
 
4. **Portability** :
  - Containers can run on any platform that supports container runtimes (e.g., Docker), making it easy to move applications between cloud providers or local systems.
 
5. **Scalability** :
  - Containers can be quickly started or stopped, allowing applications to scale up or down based on demand.

### Examples of Containers: 
 
1. **Docker** : The most common container platform, used for packaging and running applications.
  - Example: A web application containerized with Nginx for the web server and Node.js for the backend logic.
 
2. **Apache HTTP Server Container** :
  - Runs the Apache server inside a container to serve static or dynamic content without needing to configure the host system.
 
3. **MySQL Container** :
  - Provides a containerized version of the MySQL database, allowing developers to easily run and manage a database without complex setup.
In summary, containers solve the problem of **"it works on my machine"**  by providing a consistent environment everywhere they run.



# Kubernetes

**Kubernetes**  is an open-source platform for automating the deployment, scaling, and management of containerized applications. It helps you run and manage applications across multiple servers by organizing them into units called *pods*.
### Examples of Kubernetes Use: 
 
1. **Auto-scaling a Web App**: When user traffic increases on a web application, Kubernetes automatically creates more instances of the app to handle the load.
 
2. **Rolling Updates**: It allows seamless updates of applications without downtime by rolling out new versions while keeping the old ones running until the new ones are ready.
 
3. **Load Balancing**: If you have multiple instances of an app running, Kubernetes distributes user requests evenly among them to prevent any single instance from being overwhelmed.


`Why do we need Kubernetes`:

We need **Kubernetes**  to efficiently manage and scale applications in a containerized environment. It solves the complexity of deploying, scaling, and maintaining container-based applications across a cluster of machines.
### Key Roles of Kubernetes: 
 
1. **Container Orchestration** :
  - Manages the deployment of containers across multiple machines.

  - Ensures containers are running as expected and restarts them if they fail.
 
2. **Scalability** :
  - Automatically scales the number of containers up or down based on the application’s demand (e.g., more traffic = more instances).
 
3. **Load Balancing** :
  - Distributes traffic evenly across multiple container instances to ensure no single instance is overwhelmed.
 
4. **Self-Healing** :
  - Detects failed containers and replaces them automatically without user intervention.
 
5. **Rolling Updates and Rollbacks** :
  - Updates applications seamlessly without downtime and can roll back to a previous version if there are issues.

### Why Use Kubernetes? 

Without Kubernetes, managing containers manually across multiple servers can become complex and error-prone. Kubernetes automates these tasks, making it easier to deploy, scale, and maintain applications reliably in production environments.



---


# 2nd Insem


### 1. **Introduction to DevOps**
- **What is DevOps?**
  - DevOps is a set of practices that combines software development (Dev) and IT operations (Ops) to automate and integrate the processes of software development and deployment.
- **Benefits of DevOps:**
  - Faster software delivery, improved collaboration, better quality, and reduced time to market.
- **Real-life Example:**
  - Netflix uses DevOps practices to ensure continuous delivery of content updates and features without downtime.

### 2. **Git and GitHub**
- **What is Git?**
  - Git is a version control system that tracks changes in source code during software development.
- **What is GitHub?**
  - GitHub is a cloud-based platform that hosts Git repositories and facilitates collaboration among developers.
- **Git vs GitHub:**
  - **Git:** Local tool for version control.
  - **GitHub:** Cloud-based service for hosting and sharing Git repositories.
- **Real-life Example:**
  - Developers use GitHub to collaborate on open-source projects like React and TensorFlow.

### 3. **Docker**
- **Introduction to Docker:**
  - Docker is a containerization platform that packages applications and their dependencies into isolated containers.
- **Docker Architecture:**
  - **Components:**
    - **Docker Client:** Interface for users to interact with Docker.
    - **Docker Engine:** Runs and manages containers.
    - **Docker Hub:** Centralized repository for Docker images.
- **Docker Desktop and Docker Hub:**
  - **Docker Desktop:** Local tool for building and running containers.
  - **Docker Hub:** Online repository for sharing and storing Docker images.
- **DockerHub: Working Process:**
  - Users can upload images to DockerHub for public or private use, making them easily accessible for deployment.
- **Downloading Images through DockerHub or CLI:**
  ```bash
  docker pull nginx
  ```
- **Real-life Example:**
  - Spotify uses Docker to manage microservices, allowing faster deployments and better resource utilization.

### 4. **Kubernetes**
- **What is Kubernetes?**
  - Kubernetes is an open-source platform for automating the deployment, scaling, and management of containerized applications.
- **Kubernetes vs. Jenkins:**
  - **Kubernetes:** Manages containerized applications.
  - **Jenkins:** Automates the CI/CD pipeline.
- **Real-life Example:**
  - Google uses Kubernetes to manage its cloud services and scale workloads efficiently.

### 5. **Jenkins**
- **What is Jenkins?**
  - Jenkins is an open-source automation server used to automate the CI/CD pipeline.
- **Jenkins in Continuous Integration (CI):**
  - Jenkins automates the process of building, testing, and deploying code, ensuring faster feedback loops.
- **Working Process of Jenkins:**
  1. Code is pushed to a repository.
  2. Jenkins pulls the code, builds it, runs tests, and deploys it if tests pass.
- **Real-life Example:**
  - LinkedIn uses Jenkins to automate testing and deployments, reducing manual effort.

### 6. **Cloud Services**
- **Introduction to Cloud Services:**
  - Cloud services provide on-demand computing resources over the internet.
- **Types of Cloud Services:**
  - **IaaS (Infrastructure as a Service):**
    - Provides virtualized computing resources.
    - **Example:** AWS EC2
  - **SaaS (Software as a Service):**
    - Delivers software over the internet.
    - **Example:** Google Workspace
  - **PaaS (Platform as a Service):**
    - Provides a platform for building, testing, and deploying applications.
    - **Example:** Heroku
- **Real-life Example:**
  - Startups use AWS (IaaS) for scalable infrastructure, Salesforce (SaaS) for CRM, and Azure App Service (PaaS) for hosting web apps.

### 7. **Infrastructure as Code (IaC)**
- **What is Terraform?**
  - Terraform is an open-source tool for defining and provisioning infrastructure using code.
- **Terraform for Infrastructure Support:**
  - Uses configuration files to manage infrastructure like servers, databases, and networking.
- **Real-life Example:**
  - Uber uses Terraform to automate cloud infrastructure across multiple providers.

### 8. **Server-Oriented Architecture**
- **What is Server-Oriented Architecture?**
  - A traditional architecture where applications run on dedicated servers. Scaling is done by adding more servers.
- **Real-life Example:**
  - Legacy banking systems often use server-oriented architecture, relying on mainframe servers.

### 9. **Automation Tools**
- **What is Puppet?**
  - Puppet is a configuration management tool used to automate server setup, configuration, and management.
- **Puppet for Automation Management:**
  - Uses "manifests" (scripts) to define the desired state of infrastructure, ensuring consistency across environments.
- **Real-life Example:**
  - Spotify uses Puppet to automate the configuration of its servers, reducing manual effort and errors.

---

## Detailed Explanation

A **detailed explanation** of all the formatted topics with comprehensive information, examples, and how each fits into a real-world DevOps and cloud setup.

---

### 1. **DevOps: An Introduction**
- **Definition:**
  - DevOps is a set of practices that combines software development (Dev) and IT operations (Ops). The goal is to shorten the software development lifecycle and deliver features, fixes, and updates frequently in close alignment with business objectives.
- **Key Principles:**
  - **Continuous Integration (CI):** Regularly integrating code changes into a shared repository.
  - **Continuous Delivery (CD):** Automating the release process so code changes are ready for deployment at any time.
  - **Automation:** Using tools to automate repetitive tasks like testing, deployment, and infrastructure management.
  - **Collaboration:** Improved communication between development, testing, and operations teams.
- **Real-life Example:**
  - At Facebook, DevOps practices ensure the platform is updated several times a day without downtime.

### 2. **Git and GitHub**
- **Git:**
  - Git is a distributed version control system that allows developers to track changes in code, collaborate on projects, and manage different versions of their software.
- **GitHub:**
  - GitHub is a cloud-based platform that hosts Git repositories, enabling developers to collaborate on projects, perform code reviews, and manage releases.
- **Key Concepts:**
  - **Repository:** A storage location for your code.
  - **Branch:** A separate version of the repository, used for developing features.
  - **Commit:** A snapshot of code changes.
  - **Pull Request:** A request to merge changes from one branch to another.
- **Example Workflow:**
  1. Developer creates a branch for a new feature.
  2. Code is pushed to GitHub.
  3. Team members review the changes via a pull request before merging it into the main branch.
- **Real-life Example:**
  - The development team at Microsoft uses GitHub to collaborate on open-source projects like Visual Studio Code.

### 3. **Docker and Its Architecture**
- **What is Docker?**
  - Docker is a platform for developing, shipping, and running applications inside **containers**. Containers are lightweight, standalone, and executable packages that include everything needed to run an application.
- **Docker Architecture:**
  - **Docker Client:** Interface that sends commands to the Docker Engine.
  - **Docker Engine:** The core part of Docker that builds, runs, and manages containers.
  - **Docker Daemon:** Runs on the host machine and listens for Docker API requests.
  - **Docker Images:** Read-only templates used to create containers.
  - **Docker Containers:** Instances of Docker images running as isolated processes.
  - **Docker Hub:** A cloud-based repository for storing and sharing Docker images.
- **Benefits:**
  - Portability, environment consistency, and resource efficiency.
- **Real-life Example:**
  - PayPal uses Docker to run thousands of microservices, ensuring consistent deployments across environments.

### 4. **Docker Desktop and Docker Hub**
- **Docker Desktop:**
  - A local application that provides an easy-to-use interface for managing Docker containers on a developer’s workstation. It includes Docker Engine, Docker CLI, and Docker Compose.
- **Docker Hub:**
  - A cloud-based registry where Docker images are stored and shared.
- **Key Commands:**
  ```bash
  docker pull nginx           # Download an image
  docker run -d nginx         # Run a container
  docker push myimage:tag     # Push an image to Docker Hub
  ```
- **Real-life Example:**
  - The development team at Airbnb uses Docker Desktop for local development and testing before pushing images to Docker Hub for deployment.

### 5. **Jenkins and Its Working Process**
- **What is Jenkins?**
  - Jenkins is an open-source automation server used for **continuous integration (CI)** and **continuous delivery (CD)**. It helps automate parts of the software development process such as building, testing, and deploying code.
- **Key Features:**
  - **Pipeline as Code:** Define build and release pipelines using code.
  - **Plugins:** Over 1,000 plugins for integrating with other tools (e.g., GitHub, Docker).
- **Jenkins Workflow:**
  1. Developer pushes code to GitHub.
  2. Jenkins detects the code change, triggers a build, runs automated tests, and deploys if tests pass.
  3. Feedback is provided to the developer.
- **Real-life Example:**
  - LinkedIn uses Jenkins to automate testing and deployment, reducing time to release new features.

### 6. **Kubernetes: Container Orchestration**
- **What is Kubernetes?**
  - Kubernetes is an open-source platform for automating the deployment, scaling, and management of containerized applications.
- **Components:**
  - **Node:** A machine (virtual or physical) running Kubernetes.
  - **Pod:** The smallest deployable unit, consisting of one or more containers.
  - **Service:** Defines a logical set of pods and a policy for accessing them.
  - **Ingress:** Manages external access to services.
- **Benefits:**
  - Scalability, self-healing, load balancing, and service discovery.
- **Real-life Example:**
  - Google Cloud uses Kubernetes to manage its massive infrastructure and services like Gmail and Google Search.

### 7. **Cloud Services (IaaS, PaaS, SaaS)**
- **IaaS (Infrastructure as a Service):**
  - Provides virtualized computing resources over the internet (e.g., AWS EC2).
- **PaaS (Platform as a Service):**
  - Provides a platform for building, testing, and deploying applications without managing underlying infrastructure (e.g., Google App Engine).
- **SaaS (Software as a Service):**
  - Delivers software applications over the internet (e.g., Microsoft 365).
- **Real-life Example:**
  - Netflix uses AWS (IaaS) for its infrastructure, Heroku (PaaS) for backend services, and Salesforce (SaaS) for CRM.

### 8. **Terraform: Infrastructure as Code (IaC)**
- **What is Terraform?**
  - Terraform is an open-source tool for building, changing, and versioning infrastructure using code.
- **Key Features:**
  - **Declarative Configuration:** Describe the desired state of infrastructure.
  - **Provider Support:** Works with AWS, Azure, GCP, and other services.
- **Example Usage:**
  ```hcl
  provider "aws" {
    region = "us-west-2"
  }

  resource "aws_instance" "web" {
    ami           = "ami-0c55b159cbfafe1f0"
    instance_type = "t2.micro"
  }
  ```
- **Real-life Example:**
  - Spotify uses Terraform to manage cloud resources across AWS and Google Cloud.

### 9. **Server-Oriented Architecture**
- **Definition:**
  - A traditional architecture model where applications run on dedicated physical or virtual servers.
- **Benefits:**
  - Simplicity and control over hardware resources.
- **Drawbacks:**
  - Limited scalability and flexibility compared to microservices and serverless architectures.
- **Real-life Example:**
  - Legacy banking systems often use server-oriented architecture for core banking applications.

### 10. **Puppet: Automation and Configuration Management**
- **What is Puppet?**
  - Puppet is an open-source configuration management tool that automates the process of configuring and maintaining servers.
- **How It Works:**
  - Uses "manifests" (scripts) to define the desired state of the infrastructure.
- **Key Components:**
  - **Puppet Master:** Manages the configuration of nodes.
  - **Puppet Agent:** Runs on nodes to apply configurations.
- **Real-life Example:**
  - NASA uses Puppet to automate the configuration of its servers, reducing manual errors.

---




# Real Life Scenerios

Let's consider a real-life analogy of building and launching an **online e-commerce platform** (like Amazon or Flipkart). In this scenario, we'll see how each DevOps and cloud technology/tool plays an essential role in different stages of development, deployment, and maintenance.

### **Scenario: Launching an E-commerce Platform**

Your company, **ShopifyHub**, aims to launch a new e-commerce platform. You need a scalable, high-performing solution that can handle millions of users, provide a smooth user experience, and ensure continuous updates without downtime. Let's see how DevOps tools, cloud services, and automation play a part in making this happen.

#### **1. Git and GitHub: Code Version Control and Collaboration**
- **Problem:** Your development team needs a system to manage code changes, collaborate effectively, and track versions.
- **Solution:** Developers use **Git** for version control to manage changes in the source code. They push the code to a shared **GitHub** repository, where team members can review, merge, and track code changes.
- **Real-life Role:** The development team creates branches for features like payment integration and product catalog. GitHub is used to handle pull requests and code reviews, ensuring high code quality.

#### **2. Docker: Containerization for Environment Consistency**
- **Problem:** Your app works on the developer's local machine but has compatibility issues when deployed on different environments (staging, testing, and production).
- **Solution:** Use **Docker** to package the application and its dependencies into a container, ensuring it runs the same everywhere.
- **Real-life Role:** The development team creates Docker images for the frontend (React), backend (Node.js), and database (MySQL). These images are pushed to **DockerHub**, allowing the QA team and DevOps team to easily pull the images for testing and deployment.

#### **3. DockerHub: Image Repository**
- **Problem:** You need a centralized place to store and distribute Docker images.
- **Solution:** Use **DockerHub** as an image repository where you upload and manage your Docker images.
- **Real-life Role:** The DevOps team pushes the latest Docker images to DockerHub. During deployment, images are pulled from DockerHub using the CLI with a simple command:
  ```bash
  docker pull shopifyhub/backend:latest
  ```

#### **4. Jenkins: Continuous Integration (CI) and Continuous Deployment (CD)**
- **Problem:** You want to automate the process of building, testing, and deploying code to ensure faster releases.
- **Solution:** Use **Jenkins** for automating the CI/CD pipeline.
- **Real-life Role:** Whenever a developer pushes code to GitHub, Jenkins automatically pulls the code, builds the Docker images, runs tests, and deploys the containers to the staging environment. This process is automated, reducing manual effort and speeding up the release cycle.

#### **5. Kubernetes: Container Orchestration and Scaling**
- **Problem:** You need to manage multiple containers (frontend, backend, database) efficiently and ensure the application scales based on traffic.
- **Solution:** Use **Kubernetes** to automate the deployment, scaling, and management of containerized applications.
- **Real-life Role:** Kubernetes is used to deploy Docker containers across a cluster of nodes. It handles load balancing, automatic scaling, and self-healing (restarting failed containers). During a flash sale, Kubernetes automatically scales the backend service to handle the increased traffic.

#### **6. Cloud Services (IaaS, PaaS, SaaS): Hosting and Infrastructure Management**
- **Problem:** You need a scalable and flexible infrastructure to host the e-commerce platform without managing physical servers.
- **Solution:** Use a mix of **IaaS**, **PaaS**, and **SaaS** cloud services.
- **Real-life Role:**
  - **IaaS (e.g., AWS EC2):** Provides virtual machines to host the Kubernetes cluster.
  - **PaaS (e.g., AWS Elastic Beanstalk):** Manages the backend services and abstracts away infrastructure management.
  - **SaaS (e.g., Stripe for Payments):** Integrates third-party software for payment processing.

#### **7. Terraform: Infrastructure as Code (IaC)**
- **Problem:** Manually provisioning cloud infrastructure is error-prone and time-consuming.
- **Solution:** Use **Terraform** to automate the setup of cloud resources using configuration files.
- **Real-life Role:** The DevOps team writes Terraform scripts to provision AWS resources like EC2 instances, S3 buckets, and VPCs. This ensures consistent, repeatable infrastructure setup across environments.

#### **8. Server-Oriented Architecture: Legacy Systems Integration**
- **Problem:** Your company has a legacy ERP system that needs to be integrated with the new e-commerce platform.
- **Solution:** Use a **Server-Oriented Architecture** to connect the legacy ERP system with the new microservices-based architecture.
- **Real-life Role:** The ERP system runs on a dedicated server, and APIs are used to connect it with the new platform for order processing and inventory management.

#### **9. Puppet: Automation and Configuration Management**
- **Problem:** Manually configuring servers for deployment is time-consuming and prone to errors.
- **Solution:** Use **Puppet** for configuration management to automate server setup and ensure consistency.
- **Real-life Role:** Puppet scripts (manifests) are used to automate the configuration of web servers, database servers, and load balancers, ensuring they are set up with the correct software versions and settings.

---

### **End-to-End Flow of the E-commerce Platform:**
1. **Development:** The team uses Git and GitHub for version control and collaboration.
2. **Build:** Docker is used to package the application into containers, which are then uploaded to DockerHub.
3. **Testing and Integration:** Jenkins pulls the latest code from GitHub, builds the Docker images, and runs automated tests.
4. **Infrastructure Setup:** Terraform provisions the required cloud infrastructure on AWS.
5. **Deployment:** Kubernetes deploys and manages the Docker containers across the cluster, ensuring scalability.
6. **Configuration Management:** Puppet ensures consistent server setup and configuration.
7. **Maintenance:** The platform uses cloud services (IaaS, PaaS, SaaS) to handle infrastructure needs, allowing the DevOps team to focus on scaling and updates.

---

### **Real-life Example: Amazon's E-commerce Platform**
- **Amazon** uses a similar setup with containerization (Docker), orchestration (Kubernetes), and automation (Jenkins, Puppet) to manage its large-scale infrastructure and handle peak traffic during events like Prime Day. They use GitHub for version control and Terraform for provisioning cloud infrastructure on AWS.

This comprehensive scenario illustrates how each tool and technology plays a vital role in developing, deploying, and maintaining a large-scale, high-traffic application.


$$
\Large \text{2nd Insem Ends Here}
$$

---