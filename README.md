
# Docker Todo List
## Projeto da Trybe - Bloco 19 - Lidando com containers com Docker.

# 💻 Projeto
"Trabalho com aplicações de frontend, backend e testes com o uso de Docker, criando uma conexão entre elas e organizando sua operação.

<details>
  <summary><strong>🏆 Meu desempenho</strong></summary><br />

  <img src="project-info/docker-todo-list.png"/>
</details>

## 🚀 Tecnologias

* _Bash_
* _Docker_
## 📌 Habilidades
Desenvolvi as seguintes habilidades:

Usar comandos Docker na CLI;
Criar imagens Docker de aplicações;
Criar e executar contêineres Docker;
Orquestrar contêineres utilizando o Docker Compose.
## ⬇️ Instalando dependências
 ```bash
 npm install
 cd docker
 ```
## ⚡ Executando a aplicação
Inicialmente fazemos o build das imagens de back-end, front-end e testes:

```bash
docker image build -t todobackend ./todo-app/back-end
docker image build -t todofrontend ./todo-app/front-end
docker image build -t todotests ./todo-app/tests
```
Então subimos e orquestramos os containers:

```bash
docker-compose up -d
```
Para executar a aplicação, basta acessar o endereço http://localhost:3000 no browser.

## 🧪 Executando os testes
Para rodar os testes:

```bash 
docker attach docker-todotests-1
```
