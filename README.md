# CI/CD PROJECT (pending)

 <p align=center><img width="700" height="300" alt="0" src="https://github.com/FrancisNtahimpera/DEV01/assets/27433619/e95e75e9-5bc5-4a2e-8f96-0fe5d76bcd62"></p>


Hi! Here is a ci/cd using **JENKINS**, **Ansible** and **Kubernetes**.
There is three server : WeBapp, Ansible and Jenkins. The dev commit with git command. Github send a trigger to jenkins trough a webhook (for the need of the build I decide to choose in this case, Ngrok to expose my localhost:8080 safetly. Ngrok delivers instant ingress to your apps in any cloud, private network, or devices
with authentication, load balancing, and other critical controls. ).
Then The Dockerfile is commit and past from the Jenkins server to the Ansible server. 

> **Note:Changes can be done 




# SPEC:



|                |ROLE                         |                         |
|----------------|-------------------------------|-----------------------------|
|ANSIBLE|`'Automation'`            |           |
|KUBERNETES          |`Container Orchestration`            |            |
|JENKINS          |`Continuous Integration and Continuous deployment`|


<p><img width="200" height="200"  alt="Capture" src="https://github.com/FrancisNtahimpera/DEV01/assets/27433619/f348d05f-94d2-4cc7-a283-f9b8c330ce6c">
<img width="200" height="200" alt="Capture2" src="https://github.com/FrancisNtahimpera/DEV01/assets/27433619/7c92645f-ecf9-4e63-bc4d-63484bd82251">
<img width="300" height="200" alt="Capture3" src="https://github.com/FrancisNtahimpera/DEV01/assets/27433619/e97a11f0-0c83-4768-b1c8-375889418f44">
<img width="300" height="200" alt="Capture4" src="https://github.com/FrancisNtahimpera/DEV01/assets/27433619/e29ec076-b0e0-40d2-90c5-ad3c8fab2f2e">
<img width="300" height="200" alt="Capture5" src="https://github.com/FrancisNtahimpera/DEV01/assets/27433619/15975ff0-4ef6-47f0-9c62-f3bdc06508cd">




</p>



`


```mermaid
graph LR
A[git] -- commit --> B[DockerFile push to dockerHub]
A  -- Trigger --> C(Jenkins)
B --> D{Ansible}
C --> D
D --> F
```
