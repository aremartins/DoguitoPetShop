# DoguitoPetShop
Projeto Criado durante curso Validação de Formulários com JavaScript da Alura

<h2> Página de criação de contas</h2>
<img src="https://github.com/aremartins/DoguitoPetShop/blob/main/assets/img/Doguito%20Petshop%20_%20Criar%20conta.gif?raw=true" /></br>
<h2> Página de cadastro de produtos</h2>
<img src="https://github.com/aremartins/DoguitoPetShop/blob/main/assets/img/Doguito%20Petshop%20_%20Cadastro%20de%20produto.gif?raw=true" /></br>

<h3>Conceitos utilizados no projeto</h3>

<p>
    Além das maneiras de validar o formulário pelo HTML através do required , 
    nesse projeto utilizei uma <strong>regex</strong> no atributo pattern dos inputs para fazer uma val
    idação mais fina no campo senha por exemplo, que requere parâmetros específicos para ser validada
    (como quantidade mínima de caracteres e tipos de caracteres válidos). 
</p>  
<p>
  Foi criada uma função de validação de dados bem genérica, que inclusive poderá ser reaproveitada em outros projetos, para facilitar a reutilização foi utilizado <strong>data atributtes</strong>. Essa função retorna mensagens de erro quando os campos estão errados ou simplesmente não foram preenchidos.

</p>  
<p>
  Para o CPF, como a API da receita federal não é pública, foi utilizado, além da função replace para aceitar separadores eventualmente digitados no input, também uma fórmula matemática para validar se a estrutura digitada do CPF está válida.

</p>  
<p>
  Para o CEP, foi utilizada uma regex para validar a estrutura digitada e a <strong>API do via CEP</strong> para preencher os campos de endereço automaticamente.

</p>  
<p>
  No formulário de cadastro  de produtos, <strong>reutilizei a função de validação</strong> para o campo nome do produto,  e no campo de preço foi utilizada a <strong>máscara monetária simple mask money</strong> seguindo as instruções do Github do criador da máscara(que inclusive é brasileiro), <a href="https://github.com/codermarcos/simple-mask-money">codermarcos</a>.

</p> 
