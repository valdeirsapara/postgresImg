# Docker Compose para PostgreSQL e pgAdmin
Este repositório tem como objetivo simplificar o processo de configuração e execução de um servidor PostgreSQL e o pgAdmin usando Docker, permitindo subir um banco de dados PostgreSQL em qualquer máquina de maneira rápida e prática.

## dependências
 - Docker (certifique-se de ter o Docker instalado na sua máquina)

## Instalação
Antes de iniciar, certifique-se de que o Docker esteja instalado em sua máquina. Você pode obter o Docker [aqui](https://www.docker.com/products/docker-desktop/).

Siga os passos abaixo para rodar o projeto:

 1 - Clone o repositório:
```
git clone https://github.com/valdeirsapara/postgresImg.git db
```
2 -  Acesse o diretório do projeto:
```
  cd db
```
3 - Execute o Docker Compose para iniciar o PostgreSQL e o pgAdmin:
```
docker compose up -d
```


## Acessando o pgAdmin

Após a execução do comando acima, você pode acessar o pgAdmin em [http://localhost:9000](http://localhost:9000):

Credenciais de Acesso:
- Usuario: admin@admin.com
- Senha: admin@123

## Configuração Inicial do PostgreSQL
Depois de acessar o pgAdmin, você precisa registrar o servidor PostgreSQL:

- Servidor: postgres
- User: postgres
- Senha: admin@123


![image](https://github.com/user-attachments/assets/9aa9eb76-9d6b-4a70-aabe-7a4cc0fdd9a3)
![image](https://github.com/user-attachments/assets/0f2adbfb-e7c7-4961-83bf-683fcdbd8fde)
