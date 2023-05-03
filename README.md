###SYFE ASSIGNMENT

##Run a Production-Grade Wordpress App on Kubernetes ---

This repository contains a set of files and instructions to help you deploy a production-grade WordPress application on Kubernetes.

mysql-pv.yml.txt
mysql-secrets.yaml.txt
mysql-service.yaml.txt
mysql-volume.yaml.txt
mysql.yml.txt
sc.yml.txt
wordpress-pv.yml.txt
wp-service.yaml.txt
wp-volume.yaml.txt
wp.yml.txt

##Installing Kubernetes on Ubuntu 20.04 running on AWS EC2 Instances on Kubernetes
Part 1 Configuring Security Groups
Part 2 Creating instances
Part 3 Working with instances
Part 4 — Setting Up Master Node for Kubernetes
Part 5 — Adding the Worker Node to the Cluster

##Deploying WordPress and MySQL with Persistent Volumes | WordPress Deployment on Kubernetes

Setup MySQL on Kubernetes
1. Create Secret for MySQL
2. Create PV and PVC for MySQL
3. Create Deployment for MySQL
4. Create Service for MySQL

Deploy the WordPress on Kubernetes and connect with MySQL Pod.
1. Create PV PVC for WordPress
2. Create Deployment for WordPress
3. Create Service for WordPress

Create docker file for wordpress , Mysql amd Nginx

Install WordpressPress using Helm chat Use Helm chat to install Wordpress

###Setup monitoring and alerting for wordpress app

USING GRAFANA STACK FOR MONITORING 

Add the Grafana helm repository

helm repo add grafana https://grafana.github.io/helm-charts Install the Grafana stack using Helm
helm install grafana/grafana

ALL files are attached.
