# Projeto de Interface Gráfica com Swing, Criptografia e Gráficos

Este projeto foi desenvolvido para demonstrar o uso de interfaces gráficas com **Swing**, criptografia de dados, e criação de gráficos e desenhos. O sistema inclui funcionalidades como leitura de arquivos, criptografia simples de texto, e manipulação gráfica utilizando a biblioteca **STDDraw**. A interface gráfica é composta por **JFrames** e **JInternalFrames**, criando uma aplicação modular e interativa.

## Índice

1. [Sobre](#sobre)
2. [Instalação](#instalação)
3. [Como Usar](#como-usar)
4. [Dependências](#dependências)
5. [Funcionalidades](#funcionalidades)
6. [Tecnologias Utilizadas](#tecnologias-utilizadas)
7. [Contribuição](#contribuição)
8. [Licença](#licença)

## Sobre

Este projeto foi desenvolvido para explorar o uso de **Swing** em Java, apresentando uma interface gráfica rica com funcionalidades de criptografia e gráficos. A aplicação oferece um menu com opções de manipulação de texto e gráficos, além de uma funcionalidade para desenhar formas geométricas, como a bandeira do Brasil, utilizando **STDDraw**.

A interface gráfica é composta por **JFrames** e **JInternalFrames**, proporcionando uma experiência interativa e modular.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/NicolasBorgess/projetoAnalise

## Como Usar

1. Ao iniciar o projeto, você verá um menu principal com as seguintes opções:
   - **Criptografia e Descriptografia**: Ferramentas para trocar letras de palavras com base em um algoritmo simples.
   - **Leitura de Arquivos**: Carregar arquivos Excel para gerar gráficos.
   - **Desenhos Gráficos**: Desenhar formas geométricas, como a bandeira do Brasil, usando a biblioteca STDDraw.
   - **Criação de Gráficos**: Gerar gráficos baseados em dados do Excel ou entradas manuais.

2. Clique em qualquer uma das opções para iniciar a funcionalidade correspondente.


## Dependências

Este projeto usa as seguintes dependências Maven:

- **Apache POI** para ler e manipular arquivos XLS:
  ```xml
  <dependency>
      <groupId>org.apache.poi</groupId>
      <artifactId>poi</artifactId>
      <version>5.2.3</version>
  </dependency>

JFreeChart para criação de gráficos:

xml
Copiar código
<dependency>
    <groupId>jfree</groupId>
    <artifactId>jfreechart</artifactId>
    <version>1.0.13</version>
</dependency>
Log4j para logging:

xml
Copiar código
<dependency>
    <groupId>org.apache.logging.log4j</groupId>
    <artifactId>log4j-core</artifactId>
    <version>2.20.0</version>
</dependency>
STDDraw: Para gráficos e desenhos no programa (necessário baixar o JAR separadamente).

## Funcionalidades

- **Interface Gráfica com Swing**: Interface rica com menus e opções interativas.
- **Criptografia de Texto**: Troca de letras de uma palavra pela letra seguinte no alfabeto.
- **Leitura de Arquivos XLS**: Carregue dados de arquivos Excel para gerar gráficos.
- **Desenho Gráfico**: Ferramenta para desenhar a bandeira do Brasil e outras formas usando STDDraw.
- **Geração de Gráficos**: Criação de gráficos a partir de dados numéricos em arquivos XLS.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **Swing**: Para a construção da interface gráfica.
- **STDDraw**: Para criação de desenhos e gráficos simples.
- **Maven**: Gerenciador de dependências.
- **JFreeChart**: Para criação de gráficos a partir de dados.
- **Apache POI**: Para manipulação de arquivos Excel.

## Contribuição

Se você deseja contribuir para este projeto, siga os seguintes passos:

1. Faça um fork do repositório.
2. Crie uma nova branch para sua contribuição:
   ```bash
   git checkout -b minha-contribuicao


## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.
