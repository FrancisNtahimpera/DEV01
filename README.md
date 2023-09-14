# CI/CD PROJECT

Hi! Here is a ci/cd using **JENKINS**, **Ansible** and **Kubernetes**.


> **Note:Changes can be done 



# SPEC:



|                |ROLE                         |                         |
|----------------|-------------------------------|-----------------------------|
|ANSIBLE|`'Automation'`            |           |
|KUBERNETES          |`Container Orchestration`            |            |
|JENKINS          |`Continuous Integration and Continuous deployment`|




## diagrams



`


```mermaid
graph LR
A[git] -- commit --> B[DockerFile push to dockerHub]
A  -- Trigger --> C(Jenkins)
B --> D{Ansible}
C --> D
D --> F
```
