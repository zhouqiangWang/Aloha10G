# Aloha10G
This is a project for the assignment of CSC 550 Big Data. 

## 1. Quick Start
### 1. How to build
```
cd Aloha10G/hadoop-mapreduce-examples 
mvn package
```
### 2. How to run
```
hadoop jar target/hadoop-mapreduce-examples-3.2.0.jar teragen -Dmapred.map.tasks=10 10000000 /terasort/input10GB
hadoop jar target/hadoop-mapreduce-examples-3.2.0.jar terasort /terasort/input10GB /terasort/output10GB
hadoop jar target/hadoop-mapreduce-examples-3.2.0.jar teravalidate /terasort/output10GB /terasort/validate10GB

```
### 2. Workspace 
Our work direction is under `hadoop-mapreduce-examples/src/main/java/org/apache/hadoop/examples/terasort`.
