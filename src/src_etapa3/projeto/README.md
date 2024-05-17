# Instruções de utilização

No Visual Studio, tem um botão específico para rodar a aplicação. No terminal você pode rodar o comando:
```sh
$ dotnet run
```
... que irá compilar e rodar a aplicação. Mas não vai ter o hot-reload, então pra esse caso você utiliza o comando:
```sh
$ dotnet watch
```

Em ambos os casos você pode (focado no terminal) apertar CTRL + R para reiniciar a aplicação e dar rebuild nela.


## Tutorial simplificado:

   -  A aula do professor Kléber mostra como fazer a migração e a atualização no Visual Studio; no meu caso, como não estou usando ele, faço pelo terminal, onde os comandos são (pelo Dotnet CLI): `$ dotnet ef migrations add M<NÚMERO>_<NOME>`
      -  Para mantermos um padrão, faça as migrações neste padrão ali, começando com M, seguido de um número, underscore, e o nome (**TUDO JUNTO E CAMELCASE**) da ação que causou a migração (ex: `M2_AddCliente`, `M14-RemovidoPastel`, etc.)
   -  Depois de já ter migrado, faça a atualização (de novo, no Visual Studio o professor explica como é lá), no terminal é: `$ dotnet ef database update`
3. Após isso, crie o controlador e as views juntos. Não necessariamente todas as ações precisam corresponder à alguma view em si (por exemplo, no login, o logout (deslogar) é uma ação do controlador que não precisa de view)
   -  No Visual Studio tem uns recursos pra criar isso atuomaticamente pela GUI
   -  No terminal você precisa instalar (preferencialmente o `aspnet-codegenerator`) e daí:
      ```sh
          dotnet aspnet-codegenerator controller -name <NOME_DO_CONTROLADOR> -m <NOME_DO_MODELO> -dc projeto.Data.projetoContext --relativeFolderPath Controllers --useDefaultLayout --referenceScriptLibraries

      ```
      -  No caso, você pode omitir o `--useDefaultLayout` dependendo do caso (ele irá criar automaticamente o CRUD (view para **C**reate, **R**ead, **U**pdate, **D**elete, além de um de detalhes individuais e listando todos os objetos))


# Histórico de versões

- (11/04/2024): 0.0.1
    - Adicionado:
        - Estrutura básica do projeto
        - Cadastro de usuários
        - Documentação básica inicial