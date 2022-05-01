## Anotações Importantes: Git/GitHub

### Comandos do Git:

Principais comandos para serem utilizados no GitBash.

> #### Configurações iniciais:
>
> - **git init**: "inicia" o git no diretório local
>
> - **git config --global user.email "_seu email cadastrado no GitHub_"**: configura o Git globalmente com seu email
> - **git config --global user.name "_seu nome cadastrado no GitHub_"**: configura o Git globalmente com seu nome
> _Observação: recomenda-se utilizar na configuração o mesmo email e nome cadastrados no GitHub para que o mesmo reconheça você na plataforma e associe os commits com seu usário._
>
> - **git config --list**: lista/apresenta todas as configurações atuais.
>
> - **git config --global --unset user.email**: descadastra o email previamente configurado
> - **git config --global --unset user.name**: descadastra o nome previamente configurado
>
> - **git remote add origin link-do-repositório-no-GitHub**: cria o link entre o seu repositório local e o repositório remoto no GitHub.
>

> #### Comandos de versionamento:
>
> - **git add nome-do-arquivo**: torna staged o arquivo indicado
> - **git add * **: torna staged todos os arquivos do repositório que estejam com status modified
>
> - **git commit -m "_mensagem_"**: commita o diretório atual anexando uma mensagem
>
> - **git push origin master**: empurra o conteúdo do repositório local para o repositório remoto
>
> - **git pull origin master**: puxa o conteúdo do repositório remoto para o repositório local
>
> - **git clone _link_**: clona um repositório remoto através de um link criando um repositório local
>

> #### Comandos úteis:
>
> - **git status**: apresenta o status dos documentos e pastas do repertório, informando quais precisam passar a staged e ser commitados
>
> - **git remote -v**: lista os repositórios remotos cadastrados
>
> - **ls**: lista os arquivos e pastas dentro do diretório local
> - **ls -a**: lista todos os arquivos e pastas dentro do diretório local, inclusive os ocultos.
>
> - **cd caminho-do-diretório**: te move para dentro de um diretório conforme o caminho indicado. _Quando se deseja acessar um diretório existente dentro do diretório atual, basta indicar o nome do diretório, não se faz necessário digitar todo o caminho._
> - **cd ..**: te move para dentro do diretório anterior da estrutura 
>
> - **mkdir nome-do-diretório**: cria um diretório conforme o nome indicado
> - **rmdir nome-do-diretório**: deleta um diretório e todos os arquivos dentro dele
>
> - **del nome-do-arquivo**: deleta o arquivo indicado. _Quando utilizado para uma pasta, deleta os arquivos dentro da pasta, mas a pasta permanece._
>
> - **ctrl+l**: limpa a tela do GitBash
>
> - **mv _arquivo_ _caminho_**: move o arquivo definido para dentro do diretório indicado
>