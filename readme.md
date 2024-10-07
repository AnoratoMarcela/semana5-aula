## Semana 5 

<img src="https://github.com/user-attachments/assets/7cfd5a5e-017a-4d99-a7c5-ec87989c879a" alt="Post Instagram Pagamento Pix Desconto Simples Azul" width="300">

Como cliente em potencial que deseja realizar compras online, gostaria de simular um carrinho de compras onde posso adicionar produtos, visualizar uma lista detalhada dos itens selecionados, calcular o subtotal de cada produto e ver o valor total da compra. Dessa forma, posso tomar decisões de compra mais informadas e organizar melhor meu orçamento antes de finalizar a transação.


## 🎯 Objetivos de Aprendizagem

### JavaScript:
- Uso de `alert()` para exibir mensagens para o usuário.
- Manipulação de entradas com `prompt()` para receber dados do usuário.
- Uso de variáveis e constantes para armazenar e manipular dados.
- Realizar cálculos básicos, como somar o subtotal dos produtos e o valor total da compra.

## ✅ Critérios de Aceitação
- **Adicionar produtos ao carrinho**: O cliente pode adicionar produtos ao carrinho informando o nome, preço e quantidade de cada item usando o `prompt()`.
- **Visualizar produtos no carrinho**: O cliente pode visualizar os produtos adicionados, incluindo nome, preço unitário, quantidade e o subtotal de cada item usando o `alert()`.
- **Calcular o valor total da compra**: O cliente pode visualizar o valor total da compra, calculado somando os subtotais de todos os itens no carrinho, também utilizando o `alert()`.
- **Trabalhar com objetos e arrays**: Armazenar os produtos como objetos dentro de um array para melhor organização.

## 💡 Dica
Usar objetos no JavaScript ajuda a estruturar melhor os dados do produto (nome, preço, quantidade, subtotal). Além disso, armazenar os objetos em um array permite uma fácil manipulação e visualização dos itens do carrinho.

### Git e GitHub:
- Uso de comandos do Git: `git add`, `git commit`, `git pull`, `git push`.
- Gerenciamento de repositórios no GitHub (clone e fork).


## 🛠 Instruções para Trabalhar em Dupla e Versionar o Projeto

### 1. Fork do Repositório
   - Um "fork" é uma cópia de um repositório que fica no seu perfil GitHub. Você faz um fork para ter uma versão própria do projeto na qual você pode trabalhar. Isso permite que você modifique e experimente o código sem afetar o repositório original.
 
#### Como forkar?

Como fazer um  fork: [https://github.com/campinho-digital/Como-fazer-um-Fork](https://github.com/campinho-digital/Como-fazer-um-Fork)  


### 2. Após o Fork

- Clonar o Repositório Forkado
  
Abra o terminal ou o Git Bash em seu computador.


### Clone o repositório forkado para o seu computador com o seguinte comando:

~~~javascript
git clone seu_repositorio
~~~


### Navegue até a pasta do repositório clonado:

~~~javascript
cd seu_repositorio
~~~

#### ⚠️ Atenção 

Quando você clona um repositório, o Git cria uma nova pasta no seu sistema contendo todos os arquivos e a estrutura do projeto. Para trabalhar com esse projeto (editar arquivos, rodar scripts, instalar dependências, etc.), você precisa estar dentro dessa pasta. Se não navegar para essa pasta, você estará em uma localização diferente no seu sistema e os comandos que tentar rodar (como npm install ou git) não funcionarão corretamente, pois eles precisam ser executados no diretório correto.


### 3. Instalar Dependências
Se o projeto utiliza npm, você deve instalar as dependências:

~~~javascript
npm install

~~~

#### ⚠️ Atenção 
Se o projeto utiliza o Node.js e tem um arquivo `package.json`, você precisa rodar `npm install` para instalar todas as bibliotecas e dependências que o projeto necessita para funcionar. Sem isso, o projeto pode não rodar corretamente.


## :thinking: Cuidado com os dados...
No JavaScript, ao capturar entradas de dados do usuário, o `prompt()` retorna os valores sempre como **strings** (texto). Isso significa que, mesmo que o usuário digite um número, ele será tratado como uma string pelo programa. 

No entanto, para realizar **operações matemáticas** (como somas, subtrações ou divisões), você precisa trabalhar com **números** (inteiros ou decimais). Tentar realizar operações matemáticas com strings pode gerar resultados inesperados ou erros.

#### O JavaScript nativamente oferece funções de conversão de dados como parseInt() e parseFloat() para converter strings em números:

Por exemplo:
~~~javascript
// Exemplo de captura de produtos
const nomeProduto = prompt('Digite o nome do produto:');
const precoProduto = parseFloat(prompt('Digite o preço do produto:'));
const quantidadeProduto = parseInt(prompt('Digite a quantidade do produto:'));

// Lógica para calcular o subtotal e exibir com alert()

~~~

### 4. Rodando o projeto

- Vá até a pasta do projeto no terminal ou prompt de comando.
- Digite o seguinte comando no terminal
  
~~~javascript
npm start
~~~

- Isso irá rodar o comando `"start": "lite-server"` que está configurado no package.json. O `lite-server` vai automaticamente:

- Criar um servidor local.
- Abrir o seu navegador padrão.
- Carregar o arquivo index.html do seu projeto.



### 5. Desenvolvendo o código no o arquivo index.js
Abra seu editor de código preferido (por exemplo, Visual Studio Code). No editor, abra o arquivo `index.js` que está no repositório.

Neste desafio, você utilizará o `prompt()` para capturar os dados dos produtos (nome, preço e quantidade) e o `alert()` para exibir o subtotal e o total da compra. Abaixo está um exemplo básico de como capturar as entradas do usuário:

~~~javascript
// Exemplo de captura de produtos
const nomeProduto = prompt('Digite o nome do produto:');
const precoProduto = parseFloat(prompt('Digite o preço do produto:'));
const quantidadeProduto = parseInt(prompt('Digite a quantidade do produto:'));

// Lógica para calcular o subtotal e exibir com alert()


~~~

### 6. Versionamento com Git
Depois de implementada a solução e adicionar comentários ao código, você precisa versionar essas alterações usando o Git.

Quando você estiver trabalhando em dupla, é fundamental usar o Git para controlar as versões do projeto de forma organizada e eficiente. Isso ajuda a evitar conflitos de código e facilita a colaboração. 

#### ⚠️ Atenção 

O uso de branches é uma prática recomendada para manter o fluxo de trabalho limpo, permitindo que cada pessoa trabalhe em partes diferentes do código sem interferir no trabalho do outro.

### 7. Enviar o Repositório para o Moodle

Você deve enviar o link do repositório com as questões respondidas para o Moodle, para que o instrutor possa revisar o seu trabalho. O link do GitHub facilita o acesso ao código e também permite que o instrutor veja todo o histórico de commits (versões anteriores do código), o que é útil para acompanhar seu progresso.


#### Links
[Constantes](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/const)

[Sintaxe e tipos](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Grammar_and_types)

[Diferenças de var const e let](https://www.alura.com.br/artigos/entenda-diferenca-entre-var-let-e-const-no-javascript)

[Convertendo String para Inteiro](https://www.alura.com.br/artigos/convertendo-string-para-numero-em-javascript)

[If and Else](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/if...else)


### 🎯  Hacker Edition:

Esta seção é apenas para quem quer um desafio a mais e deseja explorar conceitos mais avançados. Não é obrigatório, mas pode ser uma excelente oportunidade para desenvolver suas habilidades de programação, especialmente com testes automatizados.

Se você se sente confortável com o que já foi implementado no carrinho de compras e quer ir além, você será desafiado a implementar testes automáticos para garantir que todas as funcionalidades funcionem conforme o esperado. Isso irá fortalecer sua capacidade de escrever código mais robusto e confiável.

- Implementar testes para cada funcionalidade principal do carrinho de compras (adicionar, visualizar e calcular total).
- Usar Testes Unitários para verificar se as funções estão retornando os valores esperados.
- Utilizar uma biblioteca de testes como Jest (ou outra de sua escolha) para criar e rodar os testes.

## **Boa sorte e bom código!** 🚀📘

