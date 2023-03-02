# individual5ideia

# CHAT IN BLOCK!
 ##ENTENDENDO A PROPOSTA:
 <P style = "color: blue;"> O chat in block é uma plataforma/aplicativo que permite o armazenamento de diversos arquivos em pastas separadas semelhante ao github!com a possibilidade de armazenar  em uma parte separada: videos, audios e arquivos em textos, por se tratar de um bloco de notas também é possível manter os dados e anotações, todos os arquivos ficam salvos em nosso servidor, tendo a opção de salvar em seu dispositivo!além desta capacidade por ser um chat com bloco de notas, obviamente possui um espaço para conversas, não há necessidade de login, apenas para chats privados e pessoais, as conversas são disponibilzadas através de um link pessoal aonde qualquer pessoa pode ter acesso caso entre neste link, obviamente existe a possibilidade de manter este link privado, em cada conversa haverá um repósitorio guardando os arquivos compartilhados pelo chat, lembrando que o repositorio pessoal é separado dos chats que você entrar</p>
 
 ###PÁGINA PRINCIPAL DO SITE
 
 ![Site Educacional Desenhado à Mão Azul Vermelho Branco](https://user-images.githubusercontent.com/113534912/219960207-b42c9231-0c6b-45ad-9d0b-c12b8bb7f10e.png)

<p>O site pode ser acessado tanto por aplicativo e plataforma, além do mais ele é extremamente leve, e rápido! divirta-se compartilhando seus arquivos!


# Clone o repositório
$ git clone 

# Acesse a pasta do projeto no terminal/cmd
$ cd Chat

# Instale as dependências
$ npm install

# Execute a aplicação 
$ npm start

# Acesse o servidor
$ <http://localhost:8081>


#Rotas CRUD


## Rotas CRUD

### [ 1 ] <em>bate-papo</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`GET`** | **/bate-papo** | Retorna todos os bate-papos. |
|  **`GET`** | **/bate-papo/id** | Retorna um bate-papo. |
|  **`POST`** | **/bate-papo** | Cria um novo bate-papo.  |
|  **`PUT`** | **/bate-papo/id** | Altera os dados do bate-papos.
|  **`DELETE`** | **/bate-papo/id** | Remove o bate-papo.
  
### [ 2 ] <em>bloco de notas</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/bloco de notas** | Retorna todos os bloco de notas. |
|  **`GET`** | **/bloco de notas/id** | Retorna um bloco de notas. |
|  **`POST`** | **/bloco de notas** | Cria um novo bloco de notas.  |
|  **`PUT`** | **/bloco de notas/id** | Altera os dados do bloco de notas.
|  **`DELETE`** | **/bloco de notas/id** | Remove o bloco de notas.
  
  
### [ 2 ] <em>Pasta de arquivos</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/Pasta de arquivos** | Retorna todas as Pasta de arquivos. |
|  **`GET`** | **/Pasta de arquivos/id** | Retorna uma Pasta de arquivos. |
|  **`POST`** | **/Pasta de arquivos** | Cria uma nova Pasta de arquivos.  |
|  **`PUT`** | **/Pasta de arquivos/id** | Altera os dados das Pasta de arquivos.
|  **`DELETE`** | **/Pasta de arquivos/id** | Remove as Pasta de arquivos.


### [ 2 ] <em>Integração com outras plataformas</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/Integração com outras plataformas:** | Retorna todos as Integração com outras plataformas. |
|  **`GET`** | **/Integração com outras plataformas:/id** |  Retorna a Integração com outras plataformas. |
|  **`POST`** | **/Integração com outras plataformas:** | Cria uma novo Integração com outras plataformas.  |
|  **`PUT`** | **/Integração com outras plataformas:/id** | Altera as Integração com outras plataformas.
|  **`DELETE`** | **/Integração com outras plataformas:/id** | Remove as Integração com outras plataformas.
  
