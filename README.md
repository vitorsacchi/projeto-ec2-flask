# 🚀 Projeto Flask rodando na AWS EC2

Este repositório contém um projeto simples desenvolvido em **Python + Flask**, com **deploy manual em uma instância AWS EC2**, com o objetivo de praticar conceitos fundamentais de **Cloud, Linux, Git e Deploy de aplicações web**.

---

## 📌 Visão Geral

A aplicação consiste em uma página HTML simples servida por uma API Flask, acessível publicamente através do **IP público da instância EC2**.

O foco do projeto não é apenas o código, mas todo o processo de:

* Criação da instância EC2
* Acesso via SSH
* Instalação e configuração do ambiente
* Deploy manual da aplicação
* Versionamento e publicação no GitHub

---

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Flask**
* **HTML / CSS**
* **AWS EC2 (Amazon Linux)**
* **Git & GitHub**
* **Linux (CLI)**

---

## 📂 Estrutura do Projeto

```bash
projeto-ec2-flask/
│── app.py
│── templates/
│   └── index.html
│── .gitignore
│── README.md
```

---

## ▶️ Como Executar o Projeto

### 1️⃣ Conectar na instância EC2

```bash
ssh -i "sua-chave.pem" ec2-user@IP_PUBLICO
```

### 2️⃣ Instalar dependências

```bash
sudo yum update -y
sudo yum install python3 -y
sudo python3 -m pip install flask
```

### 3️⃣ Executar a aplicação

```bash
sudo python3 app.py
```

A aplicação ficará disponível em:

```
http://IP_PUBLICO:80
```

---

## 🌐 Deploy

* Deploy realizado manualmente em uma instância **AWS EC2**
* Porta **80 liberada** no Security Group
* Aplicação escutando em **0.0.0.0** para acesso externo

---

## 🎯 Objetivo do Projeto

Este projeto foi criado com fins **educacionais**, visando:

* Prática de **deploy em cloud**
* Consolidação de conceitos de **infraestrutura e backend**
* Uso correto de **Git e boas práticas de versionamento**
* Preparação para vagas de **Cloud / Infra / Backend Júnior**

---

## 📸 Demonstração

✔️ Aplicação rodando via navegador
✔️ Repositório versionado no GitHub
✔️ Deploy funcional em EC2

---

## 👨‍💻 Autor

**Vitor Sacchi**
Estudante de Cloud, Infraestrutura e Backend

🔗 GitHub: [https://github.com/vitorsacchi](https://github.com/vitorsacchi)

---

Se você curtiu, deixa uma ⭐ no repositório!
