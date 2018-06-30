This repository creates a local development environment for Apache Spark(2.3.0) cluster with 3 Node Hadoop(2.8.4) using a Yarn resource manager
##############################################################################

How to build
------------
At the root of the repo:

docker-compose build
  
How to run
----------
At the root of the repo:

docker-compose up


Services:
---------
1. Hadoop namenode 
2. Hadoop Datanodes x 2
3. Yarn Resource Manager
4. Yarn Node Managers x 2
5. Spark 2.3.0(which uses Yarn for cluster management, allocation and shuffle)
---------

Setting up a production from needs a bit more work. However you are ready to begin building data/ml applications
