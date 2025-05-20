# Atividade 1 - Empacotar Aplicação Frontend com Nginx

### Objetivo
Esta atividade consiste em criar uma imagem Docker para servir um arquivo `index.html` usando o servidor Nginx. O container deverá ser configurado conforme os requisitos abaixo:

### Requisitos:
- A imagem oficial do **nginx** deve ser utilizada.
- O diretório de trabalho dentro do container deve ser `/app`.
- O arquivo `index.html` deve ser copiado para o diretório `/app`.
- Uma variável de ambiente chamada `APP_VERSION` deve ser configurada com o valor `1.0.0`.
- A porta TCP/80 deve ser exposta.
- Devem ser instalados os seguintes aplicativos dentro do container: `curl`, `htop` e `wget`.
- A instrução para iniciar o serviço do Nginx deve ser configurada no container.

### Como rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/desafio-modulo-docker-stackx.git

2. Navegue até a pasta 
   da Atividade 1:
   ```bash
   cd desafio-modulo-docker-stack/atv1

3. Construa a imagem Docker:
  ```bash
  docker build -t frontend .
  ```

4. Inicie o container:
  
 ```docker run -d -p 80:80 frontend
  

5. Acesse a aplicação no navegador:

   http://localhost
