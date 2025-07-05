# 🎬 MovieEnjoyer - Sistema de Avaliação de Filmes - Frontedn

MovieEnjoyer é uma aplicação web desenvolvida com Flask (backend) e HTML/CSS/JavaScript puro (frontend), que permite que usuários se cadastrem, façam login, visualizem os filmes mais assistidos, marquem filmes como assistidos e deixem suas avaliações.

---

## 🚀 Funcionalidades

- Cadastro e login de usuários
- Listagem dos filmes mais assistidos em cards
- Detalhes completos de cada filme
- Marcar filmes como assistidos
- Avaliar filmes assistidos
- Backend RESTful com documentação Swagger: integrada

---

## 🧰 Tecnologias Utilizadas

- **Backend:** Python 3.11+, Flask, Flask-RESTX, SQLAlchemy
- **Banco de dados:** SQLite
- **Frontend:** HTML5, CSS3, JavaScript
- **Documentação da API:** Swagger (via Flask-RESTX)

---

## ⚙️ Instalação e Configuração

### 🔁 1. Clone o repositório
```bash
git clone https://github.com/arthurmourab/frontend-mvp-full-stack-basico.git
```

### ▶ 2. Execute a aplicação
Na pasta raíz do repositório:

```bash
python -m http.server 8080
```

### 🔍 3. Abra sua aplicação
Acesse <http://localhost:8080/> para visualizar e interagir com a aplicação

<br />

#### Observações
Algumas funcionalidades (session, request, @app.route, etc..) podem não funcionar caso o arquivo index.html seja aberto diretamente no navegador
