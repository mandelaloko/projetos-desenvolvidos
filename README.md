# Sites:

## WordPress + Woo + ACF + Feito do Zero

Esse projeto têm uma sacada bem legal, eu utilizei o cadastro de produtos do Woo para fazer a gestão dos carros cadastrados, via actions do Woo eu fiz todo o controle de cadastro e gestão de Pagamento. 

O site contá com vários de serviços que notificam o cliente quando alguém manda mensagem ou um determinado carro é postado na plataforma, eu deixo um cron rodando toda madrugada fazendo esse controle.

Site: https://webclassicos.com.br


## WordPress + Woo + Sensei + ACF + Feito do Zero

O projeto conta com uma integração do Sensei com o Salesforce, a integração foi feita via SOAP.

Quando um pedido é feito ele é enviado ao SalesForce como uma oportunidade e quando o pedido é atualizado o mesmo também é atualizado no SalesForce, para fazer esse controle eu utilizei o WebHook do Woo.

O Sensei foi modificado para as necessidades do cliente, exemplo: O site conta com venda de cursos onlines e presenciais, ou seja, o curso presencial precisa de um controle de presença dos alunos, esse controle de presença foi feito e pensado com as action do Sensei, outro detalhe, como é um site de Cursos para Pós Graduação, os alunos devem subir o documento que comprovem que ele está apto a fazer o curso, esse controle de liberação dos alunos foi feito com a customização do Sensei.

Site: https://www.equalisveterinaria.com.br/


### Outros:

## WordPress + ACF + Feito do Zero
http://vivorio.com.br/

## WordPress + Woo + ACF + Feito do Zero
https://www.flowtraining.com.br/

## WordPress + ACF + Feito do Zero
https://duomoeducacao.com.br/

## WordPress + ACF + Feito do Zero
https://www.andinaseguros.com.br/

## WordPress + ACF + Feito do Zero
http://montrelux.com.br/

# Aplicativos:

## React Native + Firebase + API Pagar.me
O aplicativo é um Ifood interno para restaurantes, conta com um leitor de QrCode para saber qual é a mesa do usuário.
Além desse aplicativo têm mais duas aplicações, 1 aplicativo para o garçom e 1 aplicação web responsável pela cozinha e administração geral do estabelecimento.
Esse projeto foi o primeiro que eu tive o contato com o React Native e Firebase, foi no ano de 2016.
Como o Firebase é um banco NOSql eu tive que pensar de um outro modo, pois eu estava fazendo dele um banco com relacionamento comum, foi ai que eu começei a estudar o padrão de Multi Path firebase, que é genial.

https://play.google.com/store/apps/details?id=com.garcomappbrasil


## React Native + API feita com Symfony + API Pagar.me
O aplicativo é uma vitrine dos produtos da empresa Benext, nele a vendedora faz o pedido para o cliente.
A vendedora ganha uma % em cima da venda dos produtos, nesse processo foi utilizado o Split Payment do Pagar.me, que por sinal é maravilhoso. A comunicação com o Pagar.me foi feita com o Symfony como uma camada entre o Pagar.me e o Aplicativo.
https://play.google.com/store/apps/details?id=br.com.benext


# Linguagens e Ferramentas

* Pré-processador SASS com Gulp
* CSS3
* JavaScript
* jQuery
* HTML5
* Bootstrap 3,4
* PHP OO adaptado com actions no WordPress
* Controle de filters/actions no WordPress
* React + Redux + Hooks
* ESLint
* Git Flow
* Bitbucket
* PHP OO
* Symfony 4 no formato API
* Silex no formato API
* Silex com MVC, template engine Twig
* Animação com Google Web Designer

