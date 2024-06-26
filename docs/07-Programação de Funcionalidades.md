# Programação de Funcionalidades

# Lucas Chagas de Oliveira - Tela de Cadastro.

Visando aprender sobre Asp.Net, uso o segundo exemplo do Professor Kleber para ter uma base fundamental para criar a minha tela de cadastro. Com isso foquei na criação de banco de dados de usuarios, veiculos e consumo.

A base do código é definida principalmente por duas tabelas, veiculos e consumo:

-  ### A PRIMEIRA FEITA É A TABELA DE VEÍCULOS, ONDE A TABELA CONSEGUE MAPEAR ALGUNS DADOS DE VEÍCULO PREENCHIDOS PELO USUÁRIO FINAL.
   ![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/160962468/6d2b959d-0945-4477-a171-aeed12f66efd)

![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/160962468/ac3c4fae-7bf3-459c-9030-bd7f50e20520)

-  ### A SEGUNDA FEITA É A DE CONSUMOS, ONDE O USUÁRIO CONSEGUE REGISTRAR O CONSUMO DO CARRO.

   ![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/160962468/c41d3100-d53f-44ea-b1d4-314906559bea)

   ![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/160962468/0a747cbb-c74c-46e8-ae42-3d3c95141249)

-  ### TERCEIRA FEITA É A DE CADASTRO DE USUÁRIOS, ONDE O USUÁRIO CONSEGUE CADASTRAR SEU PERFIL E O BANCO DE DADOS SALVA AS INFORMAÇÕES E CRIPTOGRAFA.
   ![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/160962468/79f899fe-907c-40fd-88be-6e81ab0fdff2)

![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/160962468/d5222eb0-bf63-4761-b037-59f4e89d48d0)

# Nickolas Ribeiro de Mendonça - Feed do Aluno.

A página de feed tem a função de mostrar ao usuário cartões que incluem detalhes sobre os professores e as matérias que eles oferecem na plataforma. Além disso, exibe o custo por aula e uma descrição breve feita pelo professor, que ajuda o aluno na escolha de sua monitoria. Para disponibilizar essas informações ao usuário após ele entrar na plataforma, foi preciso desenvolver algumas tabelas:

-  Usuarios
-  Disciplinas
-  ProfessorDisciplina
-  AlunoProfessoresDisciplinas

-  ### Imagens aos models utilizados para poder definir as tabelas do banco.

-  #### Usuários

<img src="img/feedAluno1.png">

-  #### Disciplinas

<img src="img/feedAluno2.png">

-  #### ProfessorDisciplinas

<img src="img/feedAluno3.png">

-  #### AlunoProfessoresDisciplinas

<img src="img/feedAluno4.png">

-  ### Após a definição dos modelos de dados, procedeu-se à criação das migrações correspondentes, que foram posteriormente executadas para efetivar a criação das tabelas no banco de dados. Com a estruturação das tabelas completada, em seguida, desenvolveram-se os controladores (controllers) e as visualizações (views). Esse processo marca um ponto crucial, pois é nesse estágio que se torna viável a manipulação de dados por meio de interfaces. Seguem imagens das interfaces geradas

<img src="img/feedAluno5.png">
<img src="img/feedAluno6.png">
<img src="img/feedAluno7.png">
<img src="img/feedAluno8.png">
<img src="img/feedAlunos9.png">
---

# Mailson Da Silva Costa - PERFIL ALUNO
Estudando sobre Asp.Net, eu usei o exemplo do Professor Kleber para ter uma base fundamental para criar a minha tela do Perfil do aluno. Tive muitos erros pois meu sistema é um Linux.

O exemplo do Professor Kleber foi tentado reproduzir no meu sistema, que é um linux. Eu tentei fazer de tudo para sair perfeitamente, porém deu error, então recorri à documentação oficial da microsoft e desenvolvi um CRUD (Create, Read, Update, Delete) de uma aplicação de filmes.


## Ferramentas usadas
| OS  | IDL |
| --- | --- |
| XUBUNTU XFCE 22.04.4 LTS | VISUAL STUDIO CODE |

| num | ferramenta|versão testada|
| --- |    ---    |---      |
| 1   | dotnet    |V8.0.103|
| 2   | dotnet ef |6.0.10   |
| 3   | nuget.exe |6.9.1.3  |
| 4   | mono      |6.8.0.105|

---


### extensões usadas

| num  | extensão |
| --- | --- |
| 1 | .NET Install Tool |
| 2 | C# |
| 3 | C# Dev Kit |
| 4 | C# Extensions |
| 5 | NuGet Gallery |
---



### pacotes usados
| num | pacote                                         |versão testada|
| ---|              ---                                |--- |
| 1  |Microsoft.EntityFrameworkCore.Design             |V8.0.4|
| 2  |Microsoft.EntityFrameworkCore.SQLite             |V8.0.4|
| 3  |Microsoft.VisualStudio.Web.CodeGeneration.Design |V8.0.4|
| 4  |Microsoft.EntityFrameworkCore.SqlServer          |V8.0.4| 
| 5  |Microsoft.EntityFrameworkCore.Tools             |V8.0.4| 
    
---




 # captura de tela do app feito
 ## Abaixo segue as capturas de tela da aplicação web crude, CREATE, UPDATE, DELETE.

<img alt="gerar pagina " src="img/mailsongerar_paginas.png">


### Pagina gerada com o comando `aspnet-codegenerator`
---


<img alt="pagina migration" src="img/mailson_migration.png">

### Fazendo a Migração com `dotnet ef migrations`

---

<img alt="update" src="img/mailson_dtabase_update.png">

### Atualizando  o banco de dados `dotnet ef database update`

---






<img alt="inserindo banco de dados" src="img/mailson_dados_inseridos_no_sqlite.png">

### Dados inserido no banco de dados sqlite
---


<img alt="pagina crud" src="img/mailson_crud.png">

### CRUD DA APLICAÇÃO `CREATE`,`READ` `UPDATE`, `DELETE`
---


<img alt="aplicaçao com banco de ddos" src="img/mailson_prova.png">
APLICAÇÂO COM BANCO DE DADOS

---


# Lizandra Ruiz Cavalcante dos Santos - Feed Professor
Aprendendo sobre Asp.Net, usei os exemplos do Professor Kleber para ter uma base fundamental para criar a minha tela de Feed de Professor. Com isso foquei na criação de banco de dados de professores para poder testar no minha tela sobre o professor, onde os alunos vao saber um pouco sobre ele e ver sobre oque ele ensina.


<img src="img/FeedProfessor1.png">
<img src="img/FeedProfessor2.png">
<img src="img/FeedProfessor3.png">

# Marco Antonio de Oliveira C. Júnior - HOME (página inicial)

---

O QUE FOI REALIZADO ATÉ O MOMENTO:
- A tela home foi realizada.
- Exemplos foram reproduzidos.
- Uma aplicação variante do exemplo dos microfundamentos foi criada.
- Foi associada à tela de login uma funcionalidade de registro/login utilizando o modelo de autenticação "Individual Accounts" junto ao IdentityDbContext.

COMO FOI ESTUDADO:
- Através dos exemplos do microfundamento, mas principalmente por meio de exemplos encontrados em videoaulas diversas e na própria documentação do ASP.NET.

PROBLEMAS ENCONTRADOS:
- Foram encontrados diversos problemas durante a implementação, desde não conseguir enviar dados ao Banco de Dados até problemas em instanciar as classes do Entity Framework.

---

| Prints referentes aos exemplos do microfundamento |
| ------------------------------------------------- |

<img src="img/marco-imgs/exemplo-db.png">
<img src="img/marco-imgs/exemplo-detalhes.png">
<img src="img/marco-imgs/exemplo-produtos.png">


| Prints referentes a tela Home |
| ----------------------------- |

<img src="img/marco-imgs/aplicação-home.png">

| Prints referentes a outras funcionalidades desenvolvidas |
| -------------------------------------------------------- |

<img src="img/marco-imgs/aplicação-professorregister.png">
<img src="img/marco-imgs/aplicação-alunoregister.png">
<img src="img/marco-imgs/aplicação-login.png">
<img src="img/marco-imgs/aplicação-DBroles.png">
<img src="img/marco-imgs/aplicação-DBusers.png">
<img src="img/marco-imgs/aplicação-DBuserroles.png">
<img src="img/marco-imgs/aplicação-seed.png">

# Frederico Arleo - Cadastro Professor

![image](img/codigo_professor.png)
![image](img/codigo_cadastro_professor.png)
![image](img/tela_create.png)
![image](img/view_dados.png)

# Arthur de Oliveira Viotti - Perfil Professor

Comecei minha parte do projeto seguindo os passos do professor nas aulas e tentando adaptar para a realidade do nosso projeto.
Enquanto ele fazia uma tabela de veículos, comecei a fazer uma tabela parecida,porém, de professores.
Quando chegou na parte de Adicionar Exibição do "Details" a opção não parecia pra mim.
Fiquei horas tentando resolver o problema e até comecei o código do zero fazendo exatamente como o professor,mas o erro persistiu.
Tentei pular a parte do "Details" e fazer o "Delete", mas como mostra a foto, ocorreu o mesmo problema. Não consegui achar a solução, por isso ambos os links não estão funcionando no código.
![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/131665533/128c455d-941a-44d6-8765-90d18b9850c3)
Nas aulas seguintes o professor fez outras tabelas usando os mesmos processos, as quais não repliquei pois já havia entendido o processo e não seriam úteis no nosso projeto.
Nas últimas aulas, o professor ensinou a parte de Cadastro, perfil, senha e segurança. Repliquei o que ele fez na aula mas tive um problema com a caixa de escolhas do perfil, como mostra a foto.
![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/131665533/a1f91ec7-5c54-4ceb-8024-e6a0eda2952c)
A caixa de escolhas precisava de um código usado nas aulas que não repliquei. Tentei fazer separadamente e adaptar ao meu código mas sempre acontecia algum erro.
Em geral, a maior parte do código está bem parecida com os códigos do professor. Minha página ficou um pouco sem sentido pois foquei mais em replicar o que o professor mostrava enquanto tentava adaptar.
Essa etapa foi útil para aprender a criar as tabelas e a conectar tudo com facilidade, e na próxima etapa pretendo a página bonita e bem eficiente em relação ao backend.
Algumas fotos do resultado:
![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/131665533/7567bec7-ae94-4366-aa85-2c68d3f8e159)
![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/131665533/88868cf6-026e-4e2f-9605-7dc9be9551c2)
![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/131665533/f23358fa-46c8-490a-92e3-14a0469f21ba)
![image](https://github.com/ICEI-PUC-Minas-PMV-SInt/pmv-sint-2024-1-e3-proj-back-t1-time-3/assets/131665533/ba718839-1c87-461f-a112-45b7780964e4)
