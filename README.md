# ansible-elasticsearch
This is repo to deploy the Elasticsearch  using Ansible

Elasticsearch Nodes
  1. elastic-node-5
  2. elastic-node-6
  3. elastic-node-7

Kibana Node
  1. elastic-node-5

Filebeat and Nginx node
  1. elastic-node-1

Required packages on elastic-nodes
  - elasticsearch
  - java-21-openjdk
  - python3-cryptography
  - expect
  - unzip

Additional ansible collection required on Ansible Controller
  - community.elastic
