# Repositório 
De acordo com o "Oxford Languages", repositório é:
- lugar onde se guarda, arquiva, coleciona alguma coisa.

E é basicamente isto, um repositório de software, ou apenas repositório, nada mais é do um local onde todos 
os nossos arquivos de nossa aplicação irão ficar. 

Cada repositório pode ser estruturado de uma forma, podendo ser totalmente organizado ou desorganizado. 

Em um repositório organizado de um website, podemos ver: 
```md
.project
├── index.html
└── src
    ├── app
    │   ├── index.css
    │   └── main.js
    │
    └── assets
        ├── background
        │   └── background.png
        ├── fonts
        │   └── JAPANESE_2020.otf
        └── icons
            └── poker-chip.png
```
> Cada parte do site foi separada em diferenteas diretórios (pastas). As fontes estão em `fonts`, os ícones estão em `icons`. 

Em um repositório desorganizado de um website, podemos ver:
```md
.project
    ├── index.html
    ├── index.css
    ├── main.js
    ├── background.png
    ├── JAPANESE_2020.otf
    ├── poker-chip.png
```
> Todos os arquivos do website se encontram em um único nível de documento, todos estão no mesmo diretório (pasta), isto gera um repositório totalmente desorganizado.

_____________________

## Criando um repositório git 
Para transformar seu repositório local, isto é, o repositório que se encontra na sua máquina, em um repositório local git, basta
acessar ele pelo seu prompt de comando e digitar `git init`. Em português, seria algo como `git inicializar`. 

Mas antes de fazermos isto, precisamos dizer ao git quem nós somos, quem está mexendo neste repositório. 
Então, entraremos em nosso prompt de comando, e colocaremos: 
- `git config --global user.name [seu nome aqui]`
- `git config --global user.email [seu email aqui]`

Entender essas duas linhas é bem simples: 
1. `git` - significa que os comandos desta linha são do git. Precisamos executar ele. 
2. `config` - aqui acessamos a configuração da ferramente git 
3. `--global` - aqui definimos que o nome/email colocados serão utilizados para todos os repositóris git.
4. `user.name / user.email` - aqui utilizamos para definir nosso nome e email. 
5. `[....]` - seu nome e email serão colocados aqui. 

[terminal-git-config](../others/images/terminal-git-config.png)

# Clonando um repositório 
Clonar um 