# Projeto Técnicas de Programação I - Vem Ser Tech Ada & Ifood

### Integrantes do Grupo
- [Gustavo Amorim](https://github.com/gustavoaamorim)
- [João Victor Lemos](https://github.com/victorlemos1)
- [Maressa Silva](https://github.com/maressakaren)
- [Mariana Franz](https://github.com/framzz)
- [Wellington Lopes](https://github.com/Wellington-lopes)

### Objetivo
Este projeto tem como objetivo colocar em prática os conhecimentos adquiridos durante o módulo de Técnicas de Programação I da formação Vem Ser Tech | Dados.

Para isso deve-se realiza o tratamento de dados e criação de uma rota otimizada de entregas de material didático em escolas da cidade do Rio de Janeiro.

**Acesse o notebook do projeto [clicando aqui](graphs\rota.png).**

### Contexto do Problema
Você trabalha em uma consultoria de dados que foi contratada para realizar a distribuição de materiais didáticos nas escolas da cidade do Rio de Janeiro. Sua missão é realizar tratamentos nos dados de acordo com as normas de padrão definidas pelo cliente e encontrar qual a melhor rota que um caminhão deve realizar para entregar os materiais didáticos de forma a otimizar o seu percurso.

### Sobre os Dados
Para esse projeto você recebeu três arquivos:
- escolas.csv: contém os dados das escolas
- subprefeituras.csv: contém dados de quais bairros pertem a cada subprefeitura
- material_didatico.csv: contém a quantidade de material didático que cada escola deve receber

Como padrão dos dados, considere:
- nome das colunas em snake_case
- strings não devem conter acentos
- todas as strings devem estar em maiúsculo
- padronização do nome dos logradouros sem abreviação (Ex: R. deve estar como Rua)
- latitude e longitude devem conter apenas 5 casas decimais
- os ids da escola devem todos ser strings com 3 caracteres (Ex: '024')

### Entregas Esperadas
Como produto final, você deve entregar:
- um arquivo csv no as linhas já estarão ordenas de acordo com a rota a ser seguida. Além disso, os dados devem estar no padrão especificado abaixo e contendo as seguintes colunas: id da escola, nome da escola, tipo da escola (EM, CIEP ou colégio), logradouro da entrega, número, bairro, subprefeitura, latitude, longitude e quantidade de material didático que deve ser entregue. O logradouro da escola deve estar em uma coluna diferente do número;
- um arquivo csv com a quantidade total de material escolar por subprefeitura para que sejam contabilizados os custos por subprefeitura

### Desafio
Entregar um plot com a representação da melhor rota que você encontrou, por exemplo:
<img src="rota.png"  width="70%" height="40%">

### Bibliotecas Python Utilizadas
Para este projeto foram utilizadas as seguintes bibliotecas Python:
- Pandas
- Numpy
- Math
- Unidecode
- Matplotlib
- Plotly
- Folium