# PHP utilizando container

## Requirements

É necessário ter o Docker instalado na sua máquina. Recomendo seguir o tutorial https://docs.docker.com/get-docker/

## Como executar

Para executar nossa página de forma containerizada é bem simples. Apenas siga os steps abaixo:

1. Clone o projeto na sua máquina no diretório de sua preferencia.
2. Execute o comando `docker build -t php-web .` Este comando ira realizar o build do container que possue s aplicação.
3. Execute o comando `docker run -p 80:80 php-web` Este comando ira rodar o container com a aplicação PHP.
4. Ao acessar o seu `localhost` a página PHP deve aparecer no seu browser.
