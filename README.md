# Análise Geoespacial do E-Commerce Brasileiro

---


A Olist lançou um conjunto de dados com 100 mil pedidos feitos entre 2016 e 2018. Cada pedido tem algumas informações sobre o cliente e contém os três primeiros dígitos do CEP do cliente. A Olist também lançou um banco de dados de geolocalização que possui 323k coordenadas de latitude/longitude relacionadas aos três primeiros dígitos de cada código postal.

## O CEP brasileiro
Um CEP brasileiro significa Código de Endereçamento Postal e contém 8 dígitos. Introduzido em 1972 como uma sequência de cinco dígitos, foi expandido para oito dígitos em 1992 para permitir uma localização mais precisa. O formato padrão é "nnnnn-nnn" (os cinco dígitos originais, um hífen e os novos três dígitos).

CEP: 12.345-678

A maioria das cidades com população em torno de 100.000 habitantes tem um CEP atribuído a todos os locais públicos e a alguns espaços privados de alta ocupação, como grandes edifícios comerciais e grandes condomínios residenciais. As cidades pequenas recebem um código geral de 5 dígitos seguido pelo sufixo -000.

* primeira parte é composta por 5 dígitos que representam Região, Sub-região, Setor, Subsetor e Divisor de Subsetor.
* a segunda parte contém 3 dígitos, separados por um hífen da primeira, e representa os Identificadores de Distribuição.

Mais informações sobre o funcionamento do CEP podem ser encontradas no [site dos Correios.](https://buscacepinter.correios.com.br/app/endereco/index.php)


**Vamos olhar para o conjunto de dados de geolocalização fornecido pelo Olist e tentar entender como o CEP funciona geograficamente.**

# Exemplo de gráfico gerado neste projeto
## Gráfico de distribuiçao de receitas pelo Brasil

![image](https://user-images.githubusercontent.com/89540415/190684502-816838e5-dce7-49bd-9337-451be1cc8509.png)

Trabalho em progresso...

* Quais categorias são mais vendidas.
* Qual forma de pagamento foi escolhida.
* Quantas parcelas.
* Análise específica no estado de Goiás e no DF.
* Análise em cidades específicas, como São Paulo, Porto Alegre, Curitiba, Fortaleza, Bahia, Brasília, Goiânia.
