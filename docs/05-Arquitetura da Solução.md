# Arquitetura da Solução

Neste ponto abordaremos os detalhes técnicos da solução criada pela equipe, tratando dos componentes que fazem parte da solução e do ambiente de hospedagem.

## Diagrama de componentes

O diagrama a seguir mostra a modelagem física do relacionamento entre os componentes da solução:

Exemplo: 

Os componentes que fazem parte da solução são apresentados na Figura 01.

![Diagrama de Componentes](/docs/img/arquitetura_solucao.png)
<center>Figura 01 - Arquitetura da Solução</center>

A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema. 
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - Armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON.
 - **Hospedagem** - Local na Internet onde as páginas são mantidas e acessadas pelo navegador.

## Tecnologias Utilizadas

- Linguagens utlizadas para desenvolver o projeto: HTML, CSS, JavaScript
- IDEs de desenvolvimento: Visual Studio Code
- Plataforma para hospedagem do site: Heroku
- Plataforma para hospedagem dos arquivos: GitHub
- Ferramenta de versionamento: Git
- Ferramenta para a criação de logo e imagens: Canva
- Ferramenta para crição de template: Figma

## Hospedagem

Utilizamos a plataforma GitHub Pages como ambiente de hospedagem do site do projeto. A publicação é feita através de comandos via git para o repositório que se encontra no endereço: 
<a href="https://icei-puc-minas-pmv-ads.github.io/sus_online/">SUS Online</a>
