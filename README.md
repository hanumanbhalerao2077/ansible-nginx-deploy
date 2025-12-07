# Ansible Nginx Deploy 

Automated deployment of a styled web page on AWS EC2 using **Ansible**.

---

##  Project Overview
- Installs **Nginx** on Ubuntu EC2
- Deploys a **colorful, styled HTML page**
- Shows **deployment status, project info, public IP**
- Fully automated using **Ansible playbook**

---

## 📸 Screenshot

<img width="1364" height="731" alt="Screenshot 2025-11-17 111619" src="https://github.com/user-attachments/assets/8ca5423d-499a-4f89-8126-59b5cef753ef" />

---

##  How to Run

1. Clone this repository:

```bash
git clone https://github.com/hanumanbhalerao2077/ansible-nginx-deploy.git
cd ansible-nginx-deploy

Run the playbook (make sure you have a configured inventory):

ansible-playbook -i inventory nginx.yml


Open browser or curl to see live page:

curl http://<your-EC2-public-IP>

⚡ Prerequisites

AWS EC2 instance with Ubuntu

Security group with port 80 open

Ansible installed locally or on control node

✅ Outcome

Fully automated deployment of a styled HTML page on AWS EC2

Public IP shows live page: http://16.16.64.60
