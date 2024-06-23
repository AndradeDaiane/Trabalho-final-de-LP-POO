# Sistema de Vendas de Livros em Codigo Java 👩🏻‍💻👩🏻‍💻: 

Este é um projeto de implementação de um sistema de vendas de Livros em Java, com interface gráfica usando Swing. O sistema permite que os usuários visualizem uma vitrine de livros das categorias de livro de Mais Vendidos, Romance, AutoAjuda, Infatis, é os Clássicos da Literatura Brasileira, também adicionem itens ao carrinho, visualizem o carrinho, realizem o pagamento e efetuem o login.

![Concha de Vieira Fotógrafo Portfólio Site](https://github.com/AndradeDaiane/Trabalho-final-de-LP-POO/assets/161532533/a6cd3482-aa7c-4ded-b18f-d2b913ceff70)

## Biblioteca e Versão
- Versão 17
- import javax.swing.*;
  import java.awt.*;
  import java.awt.event.ActionEvent;
  import java.awt.event.ActionListener;
  import java.util.Map;

## Utilização do Sistema 💻:

### Tela de Vitrine de Livros 📚:

- Exibe uma grade de livros disponíveis para venda, sendo eles da categorias de livro de Mais Vendidos, Romance, AutoAjuda, Infatis, é os Clássicos da Literatura Brasileira.
- Cada produto é representado por uma botão, imagem, é nome.
- Ao clicar em cada Livro, abrir uma tela, no qual irá conter os detalhes, como Autor, Ano de Edição, Quantidade, Preço, Sinopse do Livro, botão adionar ao carrinho e comprar agora.
- Na tala de Vitrine também, irá conter mais dois botões que são o de Login/Usuario é Carrinho.

### Tela de Login 👤🔐:
- Permite ao usuário fazer um cadastro ou acessar o sistema;
- Opção para recuperação de senha.

### Adicionar o Livro ao Carrinho de Compra 📖➕:

- Os usuários podem selecionar produtos na vitrine ao clicar no Livro e abri a tela de Detalhe, no qual irá aparecer o botão adicionar no Carrinho.
- Eles podem escolher a quatidade conforme estoque pré estabelecido. Lembrando que se escolher uma quantidade maior do que está em estoque, irá aparecer uma mensagem informando que pode adionar de x a x qunatidade.

### Tela do Carrinho de Compra da Livraria 🛒📚:

- Exibe todos os Livros atualmente no carrinho, incluindo nome, preço, quantidade, subtotal de cada livro, Frete/taxa de Entrega, é valor Total.
- Permite que os usuários visualizem o total do carrinho incluindo o frete no qual e um valor Fixo para todas as regiões.
- Oferece opções para esvaziar o carrinho ou Realizar o pagamento.

### Tela Realizar Pagamento 💳💶:

- Ao prosseguir para o pagamento, atraves da tela de detalhes no botão "Comprar agora", ou após ter adicionadno os livros ao carrinho na tela de carrinho, no botão "Realizar pagamento", ao clicar nestes botões iáta abrir uma nova tela que e de Forma de pagamento, no qual irá aparecer forma de pagamento "Pagamento Pix", Pagamento Cartão de Debito", Pagamento Cartão de Credito", e Pagamento Boleto", escolher a forma que deseja pagar, ao esolher será redirecionados para uma tela de pagamento onde podem inserir suas informações de pagamento.
- Após o pagamento ser concluído com sucesso, uma mensagem de confirmação é exibida, junto o prazo de entrega do Livro.

## Funcionamento do Sistema Criado da Livraria Santos 💻:

- Foi criada várias classes Java que se comunicam para fornecer funcionalidades específicas para o funcinamento do sistema.
- As classes principais incluem `TelaPrincipal`, `TelaCarrinho`, `TelaPagamentoFrame`, `TelaLoginFrame`, `TeladeCadastro`, `CarrinhodeCompra`, `Cliente`, `Entrega`, `Estoque`,`FormadePagamento`, `Fornecedor`, `Funcionario`,`ItemCarrinho`, `Livro`, `Pagamento`, `Pedido`, e `Pessoa`.
- Foi utilizado no código o pacote `javax.swing`, `java.awt`, e `java.util.Map`  para criar a interface gráfica.
- As interações do usuário são tratadas por meio de `ActionListeners` associados a botões e outros componentes de interface.

## Vídeo do Sistema da Livraria Santos 🎥

https://github.com/AndradeDaiane/Trabalho-final-de-LP-POO/assets/161532533/0d0917d7-7063-4094-9f61-bc1024708391

## Diagrama de Classes 📊

![LivrariaS](https://github.com/AndradeDaiane/Trabalho-final-de-LP-POO/assets/161532533/8d546d2c-8f3f-416a-9350-9d46f2bcd492)

## Como Usar o Site ▶️:

1. Intale o programa java Intellij IDEA.
1. Certifique-se de baixando também o JDK na versão 17 (Java Development Kit).
2. Baixe este repositório do meu GitHub.
3. Importe o projeto.
4. Compile o código-fonte.
5. Execute a classe `TelaPrincipal` para iniciar o sistema.
6. Faça login com as credenciais ou crie uma cadastro.
7. Explore a vitrine de livros, adicione itens ao carrinho, realize o pagamento. 

## Creditos

Este sistema mostrar a implementação de um condigo em java de vendas de livro simples, com uma interface gráfica intuitiva e funcionalidades essenciais para uma demostração de sistema de vendas via site e compra agradável.

Autor
Daiane Dos Santos Andrade.

https://www.linkedin.com/in/daiane-dos-santos-17732183/


