# 🛠️ Ansible Roboshop

This repository contains Ansible playbooks and roles to automate the deployment of the **Roboshop** microservices-based e-commerce application.

## 🚀 Features

- **Automated Deployment**: Set up Roboshop services using Ansible playbooks.
- **Modular Roles**: Each microservice has its own Ansible role for easy management.
- **Inventory Management**: Configurable `inventory.ini` for defining hosts and groups.

## 🧩 Services Included

- `cart`
- `catalogue`
- `frontend`
- `mongodb`
- `mysql`
- `nginx`
- `payment`
- `rabbitmq`
- `redis`
- `shipping`
- `user`

## 🛠️ Requirements

- Ansible 2.9 or higher
- Python 3.x
- Access to target servers with SSH enabled

## ⚙️ Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/mohammadsyed397/ansible-roboshop.git
   cd ansible-roboshop
