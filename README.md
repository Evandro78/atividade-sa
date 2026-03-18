 🛡️ CyberShield - Proteção Digital
 📌 Descrição
O **CyberShield** é uma aplicação web desenvolvida como parte da atividade da UC de Programação Client-Side.
O projeto consiste em um sistema de proteção digital com funcionalidades simuladas de:
* 🔐 Login e cadastro de usuário
* 🦠 Verificação de ameaças
* 💾 Backup de arquivos (simulado)
* ♻️ Recuperação de arquivos
* 👤 Perfil do usuário
A aplicação foi integrada a um backend utilizando o framework **Flask**, responsável por servir todo o frontend desenvolvido.
---
 🧰 Tecnologias Utilizadas
 **Frontend:**
  * HTML5
  * CSS3
  * JavaScript (Client-Side)
  * LocalStorage
* **Backend:**
  * Python
  * Flask
---
📁 Estrutura do Projeto
```
projeto/
│
├── app.py
│
├── templates/
│   └── index.html
│
├── static/
│   ├── style.css
│   ├── script.js
│   └── logo.png
```
 ⚙️ Como Executar o Projeto
 1. Instalar dependências
```bash
pip install flask
```
 2. Executar a aplicação
```bash
python app.py
```
 3. Acessar no navegador
```
http://127.0.0.1:5000
```
🔗 Integração com Flask
O Flask é responsável por:
* Renderizar o HTML através da pasta `templates`
* Servir arquivos estáticos (CSS, JS e imagens) pela pasta `static`
* Gerenciar rotas da aplicação
Exemplo de uso no HTML:
```html
<link rel="stylesheet" href="{{ url_for('static', filename='style.css') }}">
```
💡 Funcionalidades
🔐 Autenticação (Simulada)
* Cadastro e login utilizando LocalStorage
🦠 Verificação de Segurança
* Simulação de análise de ameaças
💾 Backup
* Armazena nomes de arquivos localmente
 ♻️ Recuperação
* Permite restaurar arquivos salvos
 👤 Perfil
* Exibe dados do usuário
 🚀 Possíveis Melhorias
* Implementação de banco de dados (MySQL ou SQLite)
* Autenticação real com backend
* Upload real de arquivos
* API REST com Flask
* Deploy em servidor web
---
Este projeto é apenas para fins educacionais.
