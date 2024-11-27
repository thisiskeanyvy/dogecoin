<h1 align="center">
Dogecoin Core [DOGE, Ð]  
<br/><br/>
<img src="https://static.tumblr.com/ppdj5y9/Ae9mxmxtp/300coin.png" alt="Dogecoin" width="300"/>
</h1>


<div align="center">

[![DogecoinBadge](https://img.shields.io/badge/Doge-Coin-yellow.svg)](https://dogecoin.com)
[![MuchWow](https://img.shields.io/badge/Much-Wow-yellow.svg)](https://dogecoin.com)

</div>

Dogecoin é uma criptomoeda voltada para a comunidade inspirada num meme Shiba Inu. O software Dogecoin Core permite que qualquer pessoa opere um nó nas redes blockchain Dogecoin e usa o método de hash Scrypt para Prova de Trabalho. É adaptado do Bitcoin Core e outras criptomoedas.

Para mais informações acerca das taxas de transação utilizadas na rede Dogecoin, por favor clica aqui:
[taxas recomendadas](doc/fee-recommendation.md).

**Website:** [dogecoin.com](https://dogecoin.com)

## Utilização 💻

Para começares a tua jornada com o Dogecoin Core, ve o [manual de instalação](INSTALL.md) e o [guia para iniciantes](doc/getting-started.md).

A API JSON-RPC incluida no Dogecoin Core é auto documentada e pode ser vista com o comando `dogecoin-cli help`, mais informações detalhadas sobre cada comando podem ser encontradas utilizando `dogecoin-cli help <command>`. Alternativamente, veja a [documentação do Bitcoin Core](https://developer.bitcoin.org/reference/rpc/) - que implementa um protocolo similar - para conseguir uma versão navegável.

### Quais as portas

O Dogecoin Core utiliza por padrão a porta `22556` para comunicação em rede
ponto-a-ponto que é necessária para sincronizar a blockchain da "rede principal",
(mainnet), e se manter atualizadas de novas transações e blocos. Adicionalmente a
porta JSONRPC pode ser aberta que por defeito é `22555` para a rede principal.
É fortemente recomendado a não expor as portas RPC publicamente na internet.

|  Função  | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   22556 |   44556 |   18444 |
| RPC      |   22555 |   44555 |   18332 |

## Desenvolvimento continuo - Plano Lua 🌒

O Dogecoin Core é um programa de código aberto gerido pela comunidade. O processo de desenvolvimento é aberto e visivel publicamente; qualquer um pode ver, discutir e trabalhar no programa.

Recursos principais de Desenvolvimento:

* [Projetos do Github](https://github.com/dogecoin/dogecoin/projects) é utilizado para conduzir trabalhos planeados ou que estejam em desenvolvimento para as próximas atualizações.
* [Discussão do Github](https://github.com/dogecoin/dogecoin/discussions) é usado para discutir sobre as funcionalidades, planeadas ou não, relacionadas ao desenvolvimento do programa Dogecoin Core, os protocolos adjacentes e o criptoativo DOGE.
* [Dogecoindev subreddit](https://www.reddit.com/r/dogecoindev/)

### Estratégia das Versões
Os numeros de compilação seguem a seguinte semantica:  ```major.minor.patch```

### Ramificações
Este repositório possui 3 principais ramificações (branchs), são estas:

- **master:** Estável, contém a ultima versão da ultima atualização principal *major.minor*.
- **maintenance:** Estável, contém a ultima versão de atualizações anteriores, que ainda estão em manutenção. Formato: ```<version>-maint```
- **development:** Instável, contém código novo para atualizações planeadas. Formato: ```<version>-dev```

*As ramificações Master e Maintenance, são exclusivamente mutáveis por lançamento. Atualizações*
*planeadas terão sempre uma ramificação de desenvolvimento e as solicitações de inclusão deverão ser*
*encaminhadas por meio destas. Ramificações de manutenção existem apenas para **correção de bugs,***
*por favor, encaminhem novos recursos na ramificação de desenvolvimento com a versão mais alta.*

## Contribuindo 🤝

Se encontrastes um bug ou tivestes alguma situação incomum com este programa, por favor informa-nos do ocorrido utilizando o [sistema de problemas (issues)](https://github.com/dogecoin/dogecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Por favor, acede ao [guia de contribuições](CONTRIBUTING.md) para ver como podes participar
no desenvolvimento do Dogecoin Core. Existem alguns [pedidos de ajuda](https://github.com/dogecoin/dogecoin/labels/help%20wanted)
onde os contribuintes terão uma grande importância e apreço. wow.

## Comunidades 🚀🍾

Podes te juntar à comunidade em diferentes redes sociais.
Para veres o que está a acontecer, encontrar novas pessoas e discutir, receber o ultimo meme, aprender sobre
Dogecoin, dar e receber ajuda e partilhares o teu projeto.

Aqui estão alguns lugares para visitares:

* [Dogecoin subreddit](https://www.reddit.com/r/dogecoin/)
* [Dogeducation subreddit](https://www.reddit.com/r/dogeducation/)
* [Discord](https://discord.gg/dogecoin)
* [Dogecoin Twitter](https://twitter.com/dogecoin)

## Perguntas frequentes ❓

Tens alguma questão relacionada com o Dogecoin? Talvez já haja uma resposta, disponivel no
[FAQ](doc/FAQ.md) ou na
[seção Q&A](https://github.com/dogecoin/dogecoin/discussions/categories/q-a)
do nosso quadro de discussão!

## Licenças ⚖️
Dogecoin Core é disponibilizada sob os termos de uso da licença MIT. Vê,
[COPYING](COPYING) para mais informações ou
[opensource.org](https://opensource.org/licenses/MIT)
