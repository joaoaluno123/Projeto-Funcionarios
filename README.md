## 🛠 Atividade de DevOps com *GitHub Actions*
* Realizar o fork da aplicação
* Criar um nova branch *(Opcional)*
* Realizar o clone da aplicação na sua máquina
* Tirar os comentários do método de teste **DELETE**
* Criar o banco de dados:
  ```
  create database funcionarioDB;
  
  use funcionarioDB;
  
  create table funcionario (
  	cod int primary key auto_increment,
      nome varchar(100),
      salario decimal(15,2)
  );
  ```  
* Configure o git, se caso haja a necessidade:  
  `git config --global user.name "Seu nome de usuário"`  
  `git config --global user.email "Seu email"`
  Realize o login quando der o push
* Realizar um commit e subir para o repositório  
  `git add .`
  `git commit -m "Nome do commit"`
  `git push`
* Verificar o *workflow*
* Corrigir o método **DELETE**, tirar o comentário e remover a última linha
* Realizar um novo commit e verificar novamente o *workflow*
* Fazer os testes para **PUT (Atualizar)** e **GET (Encontrar código)**  
