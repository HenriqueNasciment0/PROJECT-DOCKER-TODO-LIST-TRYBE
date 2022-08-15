
# Docker Todo List
## Projeto da Trybe - Bloco 19 - Lidando com containers com Docker.

# 💻 Projeto
"Trabalho com aplicações de frontend, backend e testes com o uso de Docker, criando uma conexão entre elas e organizando sua operação.

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
 ```
 npm install
 cd docker
 ```
## ⚡ Executando a aplicação
Inicialmente fazemos o build das imagens de back-end, front-end e testes:

```
docker image build -t todobackend ./todo-app/back-end
docker image build -t todofrontend ./todo-app/front-end
docker image build -t todotests ./todo-app/tests
```
Então subimos e orquestramos os containers:

```
docker-compose up -d
```
Para executar a aplicação, basta acessar o endereço http://localhost:3000 no browser.

## 🧪 Executando os testes
Para rodar os testes:

```
docker attach docker-todotests-1
```

<div> 
  <a href = "mailto:hsncorretor@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/henriquen-dev/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
    <a href="https://instagram.com/henrique.s.nasc" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a> 
</div>
