# Projeto: Armazenamento de Nome e Experiência de um Herói

Este projeto consiste em criar um programa capaz de armazenar o nome e a quantidade de experiência (XP), bem como de observar as diferenças de Xp, e o grau de "heroísmo" de um herói fictício. Ainda, é possível visualizar e atualizar essas informações.

## Funcionalidades

- Adicionar um herói: permite adicionar o nome e a quantidade de XP de um herói ao banco de dados;
- Visualizar heróis: mostra uma lista com todos os heróis cadastrados, exibindo seus nomes e quantidades de XP;
- Atualizar XP: permite editar a quantidade de XP de um herói específico;

## Tecnologias Utilizadas

- Java: linguagem de programação utilizada para desenvolver o programa;
- 
## Configuração

Certifique-se de possuir o Java Development Kit (JDK) instalado em sua máquina. Além disso, é necessário incluir o driver JDBC do SQLite em seu projeto. Siga as instruções abaixo:

1. Baixe o driver JDBC SQLite em [https://bitbucket.org/xerial/sqlite-jdbc/downloads/](https://bitbucket.org/xerial/sqlite-jdbc/downloads/);
2. Adicione o arquivo `sqlite-jdbc-x.x.x.jar` aos recursos do seu projeto;
3. Configure o classpath do seu projeto para incluir o driver JDBC;

## Como Executar o Programa

1. Clone este repositório em sua máquina:

```
git clone https://github.com/Karlosclaro/Desafio_Felip-o_Heroi
```

2. Navegue até o diretório do projeto:

```
cd nome-do-repositorio
```

3. Compile e execute o programa:

```
javac Main.java
java Main
```

4. Siga as instruções exibidas no terminal para utilizar as funcionalidades do programa.

## Exemplos de Uso

- Ao abrir o programa, será exibido um menu com as opções disponíveis. Você poderá escolher entre inserir um novo herói, visualizar os heróis cadastrados ou atualizar a XP de um herói específico;
- No momento de inserir um novo herói, você deverá fornecer o nome e a quantidade de XP desse herói;
- Ao visualizar os heróis cadastrados, você verá uma lista com os nomes e as quantidades de XP de cada um;
- Ao atualizar a XP de um herói, escolha o herói desejado e informe a nova quantidade de XP.

## Contribuições

Contribuições são sempre bem-vindas! Se você tiver sugestões de melhorias, correções de bugs, ou qualquer outra funcionalidade interessante, fique à vontade para fazer um fork do projeto e abrir uma pull request.

## Autor

Carlos Klaro <karlos@8b3v8r.onmicrosoft.com>

## Licença

[MIT License](https://opensource.org/licenses/MIT)
