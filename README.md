# Projeto DevOps - Grupo 2

Trabalho final da disciplina de DevOps da esteira de CI/CD.

## Link da API no Render
https://projeto-devops-wpzp.onrender.com/health

## Como rodar localmente com Docker

1. Clone o repositório para o seu computador:
git clone https://github.com/winycius19/projeto-devops.git

2. Entre na pasta do projeto:
cd projeto-devops

3. Monte a imagem do Docker:
docker build -t projeto-devops .

4. Rode o container mapeando a porta:
docker run -p 8000:8000 projeto-devops

5. Acesse no seu navegador:
http://localhost:8000/health