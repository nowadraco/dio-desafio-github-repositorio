# Introdução ao Git e ao GitHub
## Entendendo o que é Git e sua importância

> benefícios 
1 controle de versão 
2 armazenamento em nuvem
3 trabalho em equipe
4 melhorar seu código
5 reconhecimento


**comandos básicos**
Windows | Unix | o que faz
---|---|---
cd | cd | possibilita que navegue entre as pastas
dir | ls | lista pasta dentro do diretório contido que estamos
mkdir | mkdir | para criar um nova pasta no diretório que você está
del/rmdir | rm rf | excluir pastas do diretório
cls | clear | limpar console
echo | echo | responte o que escrevo 
echo > | echo> | colocando o nome do arquivo mais a extensão cria o arquivo

>obs: comando git 
git --- version mostra a versão do GIT

## Tópicos fundamentais para entender o funcionamento do Git

- sha1
- Objetos fundamentais
- sistema distribuído
- segurança 


### SHA1
a sigla SHA significa secure hash algorithm (  algoritmo de Hash Seguro), é um conjunto de funções hash criptográficas projetadas pela NSA ( agencia de segurança Nacional dos EUA). ela faz a encriptação gerando um conjunto de caracteres identificador de 40 dígitos

### objetos fundamentais do GIT

Blobs
trees
commits

##### blobs
Um blobs (objeto binário grande) é o tipo de objeto usado para armazenar o conteúdo de cada arquivo em um repositório . O hash SHA-1 do arquivo é calculado e armazenado no objeto blob. Esses end points permitem que você leia e grave objetos blob em seu banco de dados Git no GitHub. Os blobs aproveitam esses tipos de mídia personalizados.

##### trees
A Tree no Git armazena os blobs, é um diretório (e seus arquivos e subdiretórios) em seu sistema de arquivos que está associado a um repositório . Está cheio de arquivos que você edita, onde você adiciona novos arquivos e dos quais você remove arquivos desnecessários.

##### commits
Os commits são as principais unidades de bloco de construção de uma linha de tempo do projeto Git . Os commits podem ser considerados instantâneos ou marcos ao longo da linha do tempo de um projeto Git. Os commits são criados com o comando git commit para capturar o estado de um projeto naquele momento.

### sistema distribuído seguro
Como um bom sistema de controle de versão, o Git registra as mudanças que ocorrem no código-fonte de um projeto. Logo, permite que os arquivos sejam alterados de forma simultânea, por inúmeras pessoas, sem a preocupação que essas alterações sejam sobrescritas umas pelas outras.

#### chave SSH e Token

###### SSH
SSH (Secure Shell) é um protocolo criptográfico que permite a conexão em servidores de maneira segura sem expor nome de usuário e senha. Para isso, é necessário estabelecer uma conexão informando uma chave SSH válida.

###### Token
tokens oferecem alguns benefícios, como ter a possibilidade de salvar as informações do usuário no token e não no servidor, bem como o fato de ser configurado para ter as permissões que você quiser e ter um período de expiração. Ou seja, ele para de funcionar após determinado tempo, como se fosse uma senha única e descartável.

Assim, caso outra pessoa tenha acesso ao seu token, ela estará restrita apenas às permissões que você configurou para o mesmo. Assim você não irá correr o risco de perder sua conta do GitHub, podendo descartar o token perdido e gerar outro novamente.

> comando gerar SSH
ssh-keygen -t ed25519 -c (mais e-mail) enter
vai pedir uma senha colocar a senha
pronto criado e vai falar aonde será salvo

>  copiar o conteúdo na chave publica 

> criar o ssh agent
eval $(ssh-agent -s) enter
entregar a chave para ele (privada)
ssh-add (nome da chave) enter 
e senha

> comando de clone 
git clone (mais o caminho ssh do github)
yes


#### Iniciando o Git e criando um commit
~~~
Inicia o GIT
iniciar o versionamento 
criar um commit
todo comando git leva a palavra git no começo

git init  criar um repositório no github
git add criar e mover aquivos 
git commit criar o primeiro commit

obs
ls -a ( mostra aquivos ocutos )
cd .. (volta um nivel )

primeira vez usando o git ele pede algumas informações 
git config --global user.email "seu email"
git config --global user.name nome de usuario

git add* adicionar os arquivos 
git commit -m "commit inicial" criar o comentário 
~~~

### ciclo de vida dos arquivos

>trackad

>untacked arquivos que não estão no GitHub

>unmodified arquivos que não tem modificação

>modifild arquivos modificados 

>staged

>git config -- list
trás lista de todas as configurações no git

>conflitos github
vai do sistema fácil resolver


