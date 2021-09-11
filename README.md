# Digital Innovation One - Prática .NET

## Criando uma API REST Simples com .NET Core

- _Para praticar e fixar os conceitos de como criar uma API REST a partir de um projeto pronto!_
- _Nessa fiz um passo a passo de como fazer nessa live_
- _Aberto a sugestões para melhorar o conceito!_

### Adicionando Projeto DIO.Series.Console

* Com uma solução já aberto em DIO.Series.
* Vamos clicar com o botão direito do mouse em cima da solução DIO.Series
* Adicionar novo projeto e escolher Aplicativo do Console -> próximo -> nome do projeto `DIO.Series.Console` -> criar
* Dentro da solução DIO.Series copiar todo o código de `Program.cs` e colar em `Program.cs` 
do projeto DIO.Series.Console

### Adicionando Referência de Projeto

* Agora dentro da solução DIO.Series.Console botão da direita em `Dependências` -> 
`Adicionar Referência de Projeto` selecionar DIO.Series 
* Na prática isso quer dizer que DIO.Series.Console vai ter como dependência DIO.Series, 
pegando a classe Program e isolando para um projeto só do meu console e tudo que tem como 
regra de negócio trazendo isso como uma referência, assim qualquer alteração no código vai ter efeito tanto no console
como no `Web API`para uma melhor manutenção no código!

## Adicionando using

* Colocar using DIO.Series; -> em `namespace DIO.Series.Console` -> vai apresentar um erro em todas 
as referências de `console.algumaCoisa` -> adicione `System.` em todos os `console.algumaCoisa`
* Agora apague o `Program.cs` do projeto DIO.Series

## Definindo Projeto de Inicialização

* Se o Projeto DIO.Series estiver em negrito, mudar para DIO.Series.Console em -> botão da direita em DIO.Series.Console
-> definir como `Projeto de Inicialização`.
* Se ao rodar o código ou `F5`der erro é porque tem que mudar o projeto DIO.Series em uma biblioteca ->
botão da direita em DIO.Series -> Propriedades -> Aplicativo -> Tipo de Saída -> e mudar para `Biblioteca de Classes`

## Agora sim Criando uma API REST

* Em solução DIO.Series -> botão da direita -> adicionar -> novo Projeto -> escolher `API Web do ASP.NET Core` ->
em `Nome do Projeto` colocar DIO.Series.Web -> próximo -> manter o mesmo `.NET Core 3.1` -> Criar








[Slides](dio-dotnet-poo-lab-2.pdf)

## Contato

Eliézer Zarpelão

Linkedin:  [br.linkedin.com/in/eliezerzarpelao](http://br.linkedin.com/in/eliezerzarpelao)

WebSite:  [eliezerzarpelao.eti.br](https://eliezerzarpelao.eti.br)

Instagram:  [instagram.com/eliezerzarpelao](https://instagram.com/eliezerzarpelao)

YouTube:  [youtube.com/channel/UC47RD-s-U6fpKTY0soIUn6g](https://www.youtube.com/channel/UC47RD-s-U6fpKTY0soIUn6g/featured?view_as=subscriber)

Twitter:  [@eliezerzarpelao](https://twitter.com/eliezerzarpelao)

Github:  [github.com/elizarp](https://github.com/elizarp)
