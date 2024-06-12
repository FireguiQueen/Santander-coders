# Versionamento
Versionamento é o simples ato de gerar diferentes versões ao seu código a medida que novas mudanças surgem. 

Em praticamente todos os softwares existentes, é necessário realizar correções de bugs e aprimoramentos no código com certa regularidade, geralmente em etapas bem definidas. Por exemplo, considere um software na versão 2.0.5 que apresenta um pequeno bug facilmente detectável pelos usuários. Após identificar e corrigir o problema, procedemos a testar o software de maneiras diversas para garantir que o bug foi solucionado. Em seguida, integramos o código corrigido ao código original (versão 2.0.5), o que resulta na atualização da versão do software para 2.0.6.

É importante observar que alterações significativas no código resultam em uma nova versão do software. Esse procedimento é crucial, pois, caso a nova versão apresente bugs mais graves, temos a capacidade de retroceder para versões anteriores.


## Desenvolvimento em conjunto 
O versionamento de código vai além de permitir o retrocesso a versões anteriores. Ele é extremamente útil no desenvolvimento colaborativo de software, onde dois ou mais desenvolvedores estão envolvidos.

Cada desenvolvedor pode trabalhar em uma versão diferente do código, o que é vantajoso em diversos casos. 
> Por exemplo, um jogo pode estar na versão 1.12.5 e ainda receber correções de bugs para sua versão antiga 1.7.10. 

Além disso, o versionamento possibilita a criação de alterações que outros desenvolvedores podem revisar, comparando as mudanças entre a versão antiga e a mais nova. Isso permite identificar problemas ou sugerir modificações antes da mesclagem (merge).

## Versionamento serve para tudo 
O versionamento não se limita apenas ao código. Ele pode ser aplicado em diversas áreas, incluindo documentos de texto. Utilizar versionamento em documentos garante que todas as alterações sejam rastreadas, permitindo o retorno a versões anteriores e facilitando a colaboração entre várias pessoas. Seja em projetos de software ou em trabalhos acadêmicos, o versionamento oferece um controle eficiente das mudanças e assegura a integridade do conteúdo ao longo do tempo.

___________

# O que é Git? 
Git é uma das ferramentas para versionar seu código, sendo ela a mais utilizada entre todas. 
O Git guarda versões do estado do seu projeto em snapshots (como fotos) e cria referências para acessar essas fotos. Pois não adiantaria nada salvar o estado de y versão se não há uma referencia (um caminho) para acessar ela.

Com o Git, você pode manter um histórico detalhado de todas as alterações feitas no projeto. Isso é essencial para rastrear mudanças, identificar bugs e entender a evolução do código ao longo do tempo. 

O Git armazena o estado do seu projeto em snapshots, que funcionam como fotografias de um momento específico no tempo. Cada snapshot é uma captura completa de todos os arquivos em um dado momento, e cada um deles é referenciado de maneira única por um hash SHA-1. Isso permite que você acesse qualquer versão anterior do seu projeto de forma rápida e precisa.

## Colobaração
O Git foi projetado para suportar o trabalho colaborativo. Ferramentas como GitHub, GitLab e Bitbucket, que são plataformas baseadas no Git, oferecem recursos adicionais como pull requests, code reviews e integração contínua, que facilitam ainda mais a colaboração entre equipes distribuídas.
