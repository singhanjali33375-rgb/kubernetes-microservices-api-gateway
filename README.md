# kubernetes-microservices-api-gateway
Kubernetes-based microservices architecture with API Gateway using Ingress for centralized traffic routing.Microservices deployment on Kubernetes with API Gateway and Ingress.
# Kubernetes Microservices with API Gateway

This project demonstrates a Kubernetes-based microservices architecture using an API Gateway implemented with Kubernetes Ingress.

## Project Overview
The application is designed using microservices architecture where each service runs independently inside a Kubernetes cluster.
Ingress acts as a single entry point (API Gateway) to route traffic to multiple services.

## Microservices Used
- User Service
- Order Service
- Product Service

## Technologies Used
- Kubernetes
- Docker
- Kubernetes Ingress
- YAML
- GitHub

## Architecture Flow
Client → Ingress (API Gateway) → Microservices → Pods

## Kubernetes Components
- Pods
- Deployments
- Services
- Ingress

## Features
- Centralized API Gateway
- Independent microservices
- Scalable architecture
- Cloud-native design

## Use Case
This project represents how real-world microservices are deployed and managed using Kubernetes.

## Author
Anjali Singh  
GitHub: https://github.com/singhanjali33375-rgb
kubernetes-microservices-api-gateway/
│
├── README.md
├── .gitignore
│
├── services/
│   ├── user-service/
│   │   ├── Dockerfile
│   │   └── app.py
│   │
│   ├── order-service/
│   │   ├── Dockerfile
│   │   └── app.py
│   │
│   └── product-service/
│       ├── Dockerfile
│       └── app.py
│
├── kubernetes/
│   ├── user-deployment.yaml
│   ├── order-deployment.yaml
│   ├── product-deployment.yaml
│   ├── user-service.yaml
│   ├── order-service.yaml
│   ├── product-service.yaml
│   └── ingress.yaml
│
└── images/
    └── architecture.png
    Kubernetes-based microservices architecture with API Gateway using Ingress for centralized traffic routing.
    Microservices deployment on Kubernetes with API Gateway and Ingress.
    ✅ 6️⃣ Presentation (PPT) में क्या-क्या लिखना है
🔹 Slide 1 – Title
Kubernetes Microservices with API Gateway
🔹 Slide 2 – Problem Statement
Managing multiple services without centralized routing is complex and hard to scale.🔹 Slide 3 – Solution
🔹 Slide 3 – Architecture
Client → Ingress → User / Order / Product Services
🔹 Slide 4 – Benefits
Scalability
Independent services
Centralized traffic management
Cloud-native approach
🔹 Slide 5 – Conclusion
This project demonstrates a real-world Kubernetes microservices architecture using best practices.
• Designed Kubernetes-based microservices architecture with API Gateway using Ingress.
• Deployed multiple containerized services using Kubernetes deployments and services.
• Implemented centralized traffic routing for microservices.
“This project demonstrates a Kubernetes-based microservices architecture where Ingress acts as an API Gateway to route traffic to multiple services.”

