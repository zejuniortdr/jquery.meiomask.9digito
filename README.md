jquery.meiomask.9digito
==========

Adaptação do plugin jquery.meio.mask para celulares com 9º dígito no Brasil. Atualmente DDD contemplados com o 9º dígito:
- SP (11 ao 19)
- RJ (21,22 e 24)
- ES (27 e 28)

Requisitos
--------------
- JQuery


Instalação
--------------

- Clone este repositório para junto dos plugins do seu projeto
- Adicone os arquivos no seu template html (após a inclusaão do jQuery) que fará uso das máscaras, adequando os caminhos conforme necessário:
	<script src="<JS_PLUGINS_PATH>/meio-mask/jquery.meio.mask.min.js"></script>
    <script src="<JS_PLUGINS_PATH>/meio-mask/meio-mask-init.js"></script>

Ou inclua o caminho direto para estes arquivos:

<script src="https://raw.githubusercontent.com/zejuniortdr/jquery.meiomask.9digito/master/jquery.meio.mask.min.js"></script>
<script src="https://raw.githubusercontent.com/zejuniortdr/jquery.meiomask.9digito/master/meio-mask-init.js"></script>


Uso
--------------
Nos htmls que precisar das máscaras nos inputs, adicione o atributo ***alt="NOME_DA_MASCARA"**, conforme os exemplos abaixo:

- ***phone*** : (99) 9999-9999
- ***phone-us*** :  (999) 9999-9999
- ***cpf*** :  999.999.999-99
- ***cnpj*** :  99.999.999/9999-99
- ***date*** :  39/19/9999
- ***date-us*** :  19/39/9999
- ***cep*** :  99999-999
- ***time*** :  29:69
- ***cc*** :  9999 9999 9999 9999
- ***integer*** :  999.999.999.999
- ***decimal*** :  99,999.999.999.999
- ***decimal-us*** :  99.999,999,999,999
- ***signed-decimal*** :  99,999.999.999.999
- ***signed-decimal-us*** :  99,999.999.999.999
- ***msk*** : 999-999
- ***other_msk*** : 6666
- ***another_one*** : 7777 , type:reverse
- ***dose*** : 99
- ***termina_em*** : 39/19/9999, autoTab:false
- ***phone_9digito*** : (99) 99999-9999
- ***inteiros*** :  999999999999


Também é possível a criação de novas máscaras como visto no arquivo ***meio-mask-init.js***, com opções de valores padrões, entrada reversa, controle de tabulação, entre outras opções.
