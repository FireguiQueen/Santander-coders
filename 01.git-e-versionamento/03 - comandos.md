# Comandos locais

## `add`
Naturalmente, ao criar um repositório Git, nossos arquivos e diretórios não estarão sendo rastreados pelo Git. Isto é, eles ainda não podem ser versionados. Então, após criar um repositório Git, se eu adicionar um arquivo chamado "hello.txt" ao repositório, mesmo que eu faça alterações dentro deste arquivo, o Git não saberá que elas estão sendo realizadas, pois ele ainda não faz parte do repositório Git.

Para adiciona-los ao nosso repositório git, usaremos o comando `add` + `'nome_do_arquivo'`.
- `git add hello.txt`
ou também, aidiconar todos os arquivos de uma vez
- `git add .`

Após isto, nosso arquivo 'hello.txt' está em "staged", um estágio onde seus arquivos podem ser commitados.

### O que é Staged?
A nossa "staging area" é utilizada para controlar quais arquivos irão para o commit, isto é, quais arquivos farão parte da próxima versão. A staging area atua como intermediária entre uma versão antiga do projeto e uma nova. Por exemplo, digamos que eu modifiquei todos os meus arquivos do repositório. Agora, eu preciso fazer um commit para criar uma nova versão. Mas antes disso, esses arquivos precisam ir para o status "staged", permitindo que eu controle quais arquivos irão para o commit.

## `status`
Este comando nos mostra o status e diversas informações úteis do nosso repositório, como se há commits a serem feitos e quais arquivos estão sendo rastreados ou não.

Se o repositório foi clonado, ou seja, se ele também existe de forma remota, o comando status nos mostra se estamos à frente dele (com informações criadas localmente que ainda não foram enviadas) ou se estamos atrás dele (onde o repositório remoto recebeu atualizações, e agora precisamos puxá-las para o repositório local).
- `git status`

## `diff`
Através deste comando, somos capazes de ver a diferença entre muitas coisas. Por exemplo, após modificar um arquivo, somos capazes de ver quais mudanças ocorreram entre o arquivo modificado e o arquivo original.

Também somos capazes de ver quais mudanças ocorreram de um commit (de uma versão) para outro.
- `git diff`

## `commit`
É utilizado para registrar mudanças no repositório. Um commit captura o estado atual do projeto, permitindo que você crie um "ponto de restauração" que pode ser referenciado ou revertido no futuro.

Quando você realiza um commit, você está basicamente criando um snapshot do seu projeto naquele momento, incluindo um log de mensagens que descreve as alterações feitas. Isso ajuda a manter um histórico detalhado do desenvolvimento,

- `git commit -m "v1.7.10" -m "adicionado novos mobs e vilas ao mundo"`

## `log`
O comando log nos mostra os registros de todos os commits feitos no repositório, incluindo suas datas, quem os fez e outras informações relevantes. Por exemplo:
> Autor: author: guilherme fireguiqueen@proton.me
> Data: Data em que o commit foi realizado
> Mensagem do Commit: Descrição das alterações realizadas

- `git log`

## `restore`
Com o restore podemos restaurar, ou "voltar", a versões anteriores do projeto.

_______

# Comandos remotos 

## `push`

## `fetch`

## `pull`

-
