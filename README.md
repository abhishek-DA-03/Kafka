# Kafka Deployment on Kubernestes Cluster

Welcome to the Kafka Project! This repository contains sample code and resources to help you get started with Apache Kafka, a distributed streaming platform. Whether you're new to Kafka or looking to explore advanced features, this project provides a required config files inorder to deploy kafka into Kubernetes cluster.


# Prerequisite:

  1. Kubernetes Cluster
  2. Docker



# Clone the repository:
```bash
  mkdir kafka
  cd kafka
  git clone https://github.com/abhishek-DA-03/Kafka.git
```
Create a directory to store the data and log files for kafka and Zookeeper for below path
  1. /var/lib/zookeeper/log
  2. /var/lib/zookeeper/data
  3. /var/lib/kafka

# Apply the config files.
Use the following command to apply the YAML files from repository
```bash
  $ kubectl apply -f .
```
