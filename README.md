# Botão Móvel

Este projeto é uma aplicação simples que serve uma página HTML onde um botão se move quando você tenta clicar nele. A aplicação é construída usando Node.js e Express, e é empacotada em um contêiner Docker.

## Pré-requisitos

- Docker instalado na sua máquina

## Como executar

1. Clone este repositório:
    ```sh
    git clone https://hub.docker.com/r/danielpesilva/botao-movel
    cd botao-movel
    ```

2. Construa a imagem Docker:
    ```sh
    docker build -t botao-movel .
    ```

3. Execute o contêiner Docker:
    ```sh
    docker run -p 3000:3000 botao-movel
    ```

4. Abra seu navegador e acesse `http://localhost:3000`.

## Estrutura do Projeto

- `server.js`: Servidor Express que serve a página HTML.
- `public/index.html`: Página HTML com o botão móvel.
- `Dockerfile`: Arquivo de configuração do Docker para construir a imagem da aplicação.
- `README.md`: Instruções para configurar e rodar o projeto.

## Funcionalidade

Um botão no qual voce nunca vai conseguir clicar nele apenas para te irritar
