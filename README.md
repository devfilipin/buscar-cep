# Busca CEP

## Descrição

O projeto "Buscar CEP" é uma aplicação Java que permite a busca de endereços a partir de um Código de Endereçamento Postal (CEP) utilizando uma API pública. O objetivo é facilitar a obtenção de informações detalhadas de endereços de maneira rápida e eficiente.

## Funcionalidades

- Busca de endereço completo através de um CEP.
- Validação do formato do CEP.
- Exibição de informações detalhadas do endereço, como rua, bairro, cidade e estado.
- Interface gráfica desenvolvida com Swing.

## Tecnologias Utilizadas

- Linguagem de Programação: Java
- Biblioteca para interface gráfica: Swing
- API de busca de CEP: [República Virtual] (http://cep.republicavirtual.com.br)

## Como Utilizar

### Pré-requisitos

- Java JDK 8 ou superior

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/devfilipin/buscar-cep.git

2. Acesse o diretório do projeto:
   ```bash
   cd buscar-cep
   
3. Compile o código:
   ```bash
   javac -d bin -sourcepath src src/cep/Cep.java src/cep/Sobre.java

4. Exceute a operação:
   ```bash
   java -cp bin cep.Cep
