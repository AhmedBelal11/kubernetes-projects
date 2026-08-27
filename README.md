# Kubernetes Projects
# Kubernetes Projects

A collection of hands-on Kubernetes deployment projects covering databases, web applications, configuration management, Secrets, ConfigMaps, and Kubernetes Services.

## Projects

### 1. MongoDB + Mongo Express

* Deploys MongoDB database with Mongo Express web UI
* Uses Kubernetes Secrets for credentials
* Uses ConfigMap for database configuration
* Uses Kubernetes Deployments and Services

### 2. Nginx Application

* Deploys an Nginx web server
* Uses ConfigMap and Secrets for configuration
* Uses Kubernetes Deployment and Service

### 3. WordPress + MySQL

* Deploys WordPress with a MySQL database
* Uses Kubernetes Secrets for database credentials
* Uses Kubernetes Deployments and Services
* Uses ClusterIP Service for internal MySQL communication
* Uses LoadBalancer Service to expose WordPress
* Configures WordPress to connect to MySQL through a Kubernetes Service
