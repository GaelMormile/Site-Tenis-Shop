<h1 align="center">🛒 Tênis Shop</h1>
<p align="center">
  Sistema de vendas online desenvolvido em Django.
</p>

---

## 🔥 Objetivo

Este projeto foi desenvolvido para a disciplina **Desenvolvimento Web III** do curso de **Desenvolvimento de Software Multiplataforma**, com o intuito de aplicar conhecimentos em:

- Django (Python)
- Bootstrap 5
- Consumo de APIs externas (FakeStore e ViaCEP)
- Templates e herança de layout
- Controle de sessão e autenticação
- CRUD de usuários e produtos
- Gráficos com Chart.js

---

## 👨‍💻 Como executar o projeto

--- Em todos os comandos se atentar a qual versão do python você tem instalada na sua máquina (python, python3 e py podem funcionar) ---

1. Crie um ambiente virtual:

   py -m venv ambienteVirtual

2. Instale as dependências:
 
   py -m pip install django
   py -m pip install pillow
   py -m pip install requests

3. Aplique as migrações:
  
   py manage.py makemigrations
   py manage.py migrate
 

4. Crie um superusuário (opcional, para acessar o admin):
   
   py manage.py createsuperuser
   

5. Rode o servidor:
   
   py manage.py runserver
   

6. Acesse no navegador: `http://127.0.0.1:8000/`
