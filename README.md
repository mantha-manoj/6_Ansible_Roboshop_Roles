# 🚀 Roboshop Automation using Ansible Roles

This repository contains **Ansible Roles** to automate the deployment of the **Roboshop microservices application**.

Instead of writing everything in a single playbook, this project uses **Ansible Roles** to make automation modular, reusable, scalable, and production-friendly.

---

## 📌 Project Overview

Roboshop is a microservices-based e-commerce application with multiple services.

Using this project, you can automatically configure and deploy:

- MongoDB
- MySQL
- Redis
- RabbitMQ
- Catalogue
- User
- Cart
- Shipping
- Payment
- Dispatch
- Web
- Ratings

This repository organizes deployment logic into reusable Ansible roles.

---

## 🏗️ Project Structure

```bash
6_Ansible_Roboshop_Roles/
│
├── roles/
│   ├── common/
│   ├── mongodb/
│   ├── mysql/
│   ├── redis/
│   ├── rabbitmq/
│   ├── catalogue/
│   ├── user/
│   ├── cart/
│   ├── shipping/
│   ├── payment/
│   ├── dispatch/
│   └── web/
│
├── inventory.ini
├── roboshop.yml
└── ansible.cfg
```

---

## ⚙️ Technologies Used

- Ansible
- Linux
- Shell Scripting
- AWS EC2
- YAML
- Git & GitHub

---

## 🔥 Features

✅ Modular automation using Ansible Roles  
✅ Reusable code structure  
✅ Faster deployments  
✅ Easy service management  
✅ Scalable microservices deployment  
✅ Production-ready folder structure  

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/mantha-manoj/6_Ansible_Roboshop_Roles.git
cd 6_Ansible_Roboshop_Roles
```

### 2. Update Inventory File

Add your server IPs inside:

```bash
inventory.ini
```

Example:

```ini
[mongodb]
<server-ip>

[mysql]
<server-ip>

[redis]
<server-ip>
```

### 3. Run Playbook

```bash
ansible-playbook -i inventory.ini roboshop.yml
```

---

## 📚 What I Learned

Through this project, I learned:

- Ansible Roles
- Playbooks
- Inventory Management
- Variables
- Templates
- Handlers
- Service Automation
- Infrastructure as Code (IaC)

--- 

## 🎯 Why Ansible Roles?

Using roles helps:

- Reduce code duplication
- Improve readability
- Separate service logic
- Scale deployments easily

---

## 👨‍💻 Author

**Manoj Mantha**

- GitHub: https://github.com/mantha-manoj
- LinkedIn: https://www.linkedin.com/in/manoj-mantha

---

## ⭐ Support

If you found this project useful:

⭐ Star this repository  
🍴 Fork this repository  
🛠️ Contribute improvements  

---