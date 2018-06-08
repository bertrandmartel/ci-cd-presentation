## CI/CD using <br/> Rancher & Gitlab

<div style='display: table;'>
  <div style='float:left;width:300px;'>
    <img  src="https://github.com/bertrandmartel/ci-cd-presentation/raw/master/assets/image/gitlab.png"/>
  </div>  
  <div style='display: table-cell;vertical-align: middle;'>
    <img src="https://github.com/bertrandmartel/ci-cd-presentation/raw/master/assets/image/rancher.png"/>
  </div>
</div>

---

<img src="assets/image/docker.png" style='border:0;'/>

> Docker is an open platform for developing, shipping, and running applications

Note:
Docker allows you to package an application with all of its dependencies into a standardized unit for software development.

---

## VM vs Docker

<img src="assets/image/VM-Diagram.png" />

Note:
Sandbox environment (develop, test, debug, educate), 
Continuous Integration & Deployment, 
Scaling apps, 
Development collaboration, 
Infrastructure configuration, 
Local development, 
Multi-tier applications, 
PaaS, SaaS, 

---

## GitLab

<img  src="assets/image/gitlab2.png"/>

- VCS
- Continuous Integration (Gitlab CI)
- Docker registry
- User / Group management

---

## Rancher

<img src="assets/image/rancher.png"/>

- Docker container management
- Distinct environments (Labo, Prod ...)
- Supported hosts : custom, Amazon, Azure ...
- User management per environment

---

#### CI/CD flow (simplified)

<img src="assets/image/archi_rancher.png" style='border: 0;'/>

---

## Demo