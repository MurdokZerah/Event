# Event

# 🎯 Sistema de Cadastro de Eventos

Projeto desenvolvido com **Django** aplicando boas práticas de estruturação e segurança no desenvolvimento web.

---

## 📌 Objetivo

Criar a base de um sistema web seguindo padrões profissionais, incluindo:

* uso de ambiente virtual
* gerenciamento de dependências
* proteção de dados sensíveis

---

## ⚙️ Tecnologias utilizadas

* Python
* Django
* python-dotenv

---

## 🚀 Como executar o projeto

### 1. Clonar o repositório

```bash
git clone <link-do-repositorio>
cd eventos
```

### 2. Criar e ativar ambiente virtual

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/Mac:**

```bash
python -m venv venv
source venv/bin/activate
```

---

### 3. Instalar dependências

```bash
pip install -r requirements.txt
```

---

### 4. Criar arquivo `.env`

Crie um arquivo `.env` na raiz do projeto:

```env
SECRET_KEY=sua_chave_secreta_aqui
DEBUG=True
```

---

### 5. Rodar o servidor

```bash
python manage.py runserver
```

Acesse no navegador:

```
http://127.0.0.1:8000/
```

---

## 🔒 Boas práticas aplicadas

* Uso de `.env` para dados sensíveis
* `.gitignore` para evitar versionamento indevido
* `requirements.txt` para padronização de dependências
* Separação de ambiente de desenvolvimento

---

## ❗ Importante

O arquivo `.env` **não está no repositório** por motivos de segurança.

---

## 🧠 Respostas teóricas

### 1. Por que o `.env` não deve ser versionado?

Porque contém informações sensíveis que podem comprometer a segurança do sistema.

### 2. Função do `pip freeze`

Garantir que todos usem as mesmas versões das bibliotecas no projeto.

### 3. Risco de expor a `SECRET_KEY`

Permite ataques como falsificação de sessões e acesso indevido ao sistema.

### 4. Papel do `.gitignore`

Evitar que arquivos desnecessários ou sensíveis sejam enviados ao repositório.

---

## 📁 Estrutura do projeto

```
eventos/
│
├── eventos/
├── manage.py
├── requirements.txt
├── .gitignore
└── .env (não versionado)
```

---

## ✅ Status do projeto

✔ Estrutura inicial concluída
✔ Pronto para desenvolvimento de funcionalidades

---
