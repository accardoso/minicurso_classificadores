# Minicurso Classificadores

Este repositório contém os Jupyter Notebooks utilizados para ministrar o ***Minicurso Construindo Classificadores***.

![Anúncio Minicurso](https://raw.githubusercontent.com/accardoso/minicurso_classificadores/master/img/MC_Classificadores_Anuncio.gif)

## Objetivos

Este minicurso visa ser uma **introdução ao *machine learning* para programadores**, possibilitando que tenham as bases para se aprofundarem, lerem códigos da área e pesquisarem dúvidas na internet de forma independente.

###### *Nota sobre o estilo do código*:

Cientista de Dados e programadores Python podem perceber que **utilizei uma gama de estilos e recursos** da linguagem e bibliotecas.  Por exemplo: as muitas maneiras de formatar uma *string* para impressão incluindo o valor de uma variável.

**Isto foi feito de forma intencional para facilitar a leitura de outros materiais**. Portanto, procurei apresentar e disponibilizar para consulta diversas maneiras que um comando pode ser escrito.

Entretanto, **sugiro manter um padrão** ao escreverem seus códigos, de preferência o mesmo de seu time e/ou da comunidade.

## Ementa

Cada notebook contém a parte prática de uma lição do minicurso:

- **Lição 0**: Antes mesmo da primeira lição, vamos ao que interessa! Construiremos e entenderemos os principais algoritmos de classificação. Também passaremos por uma visão geral do que é inteligência artificial, aprendizado de máquina, seus tipos (supervisionado, não supervisionado, etc.) e tarefas (classificação, regressão, agrupamento, etc.).

- **Lição 1**: Nesta primeira lição é apresentado como construir um classificador utilizando uma metodologia básica (conhecer os dados, treinar e testar).

- **Lição 2**: Vamos evoluir a metodologia, aprendendo a repartir melhor os dados, e a realizar a validação, avaliação e comparação de nossos classificadores.

- **Lição 3**: Nesta lição o objetivo e ver como podemos otimizar (*tunar*) os parâmetros de forma automática e como fica o processo de treinamento, validação e teste do classificador.

- **Lição 4**: Criaremos um pipeline de algoritmos de IA para juntos solucionaram o problema. Em específico aplicaremos uma redução de dimensionalidade seguida pelo classificador.

- **Lição 5 - Extra**: Como extra criaremos uma solução de inteligência artificial para classificação de texto.

*Observação: Os notebooks não contém todo o conteúdo, a maior parte das explicações foram realizadas no quadro branco. Eles foram planejados para a parte prática e como material de consulta e treino. Entretanto, você pode utiliza-los como um roteiro de estudos (lembre-se a internet tem muito material bom nesta área, e as documentações também são ótimas).*

### Datasets Utilizados:

- *Lição 1 a 4*: [Reconhecimento de Dígitos Escritos a Mão](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html#sklearn.datasets.load_digits)

- *Lição 5 - Extra*: [Identificação de E-mails que são Spam e Não Spam (Ham)](http://www.esp.uem.es/jmgomez/smsspamcorpus/)

### Sugestão de Cronograma

- *Aula 1*: Lição 0 e 1

- *Aula 2*: Lição 2 a 4 / 5

Considerando aulas de 2h.

### Pré-requisitos

- Programação em qualquer linguagem.

- Conta no Google Drive se for utilizar o Google Colaboratory, ou Ambiente instalado com Python 3.7 e dependências.

## Executando

### Google Drive
Minha sugestão principal é executar os notebooks inicialmente no próprio Google Drive utilizando o [Colaboratory](https://colab.research.google.com).

Para isto, basta:
1. Ter uma conta no Google
2. Acessar o link: https://colab.research.google.com
3. Siga para a aba *GitHub*, *Google Drive* ou *Upload* e adicione o notebook ao seu Colaboratory.

![Enviando notebook para Colab](https://raw.githubusercontent.com/accardoso/minicurso_classificadores/master/img/colab.gif)

#### Dicas de utilização do Colaboratory

1. Caso esteja utilizando um notebook compartilhado contigo, sugiro copia-lo antes para o seu Drive (*File > Save a copy in ..*), assim evita que alterar o notebook original (caso tenha autorização para tanto), ou perde-lo se o dono altera-lo ou remove-lo.

3. Também sugiro executar o notebook em modo *Playground* evitando alterações acidentais enquanto realiza seus experimentos e aprendizados.

*Notas*: Algumas funcionalidades necessitam de adaptações para funcionar no Colab. São elas:

- Alguns gráficos podem aparecer em preto e branco (escala de cinza).

- Leitura de arquivos na *Lição 5 - Extra*.

- Escrita de arquivo na *Lição 0*, entretanto nesta lição, coloquei o resultado para sair em tela.

### Própria Máquina

Os notebooks também podem ser executados diretamente na própria máquina (local ou servidor) sem a necessidade de um serviço como o Colaboratory. Neste caso é necessário ter o Python e as dependências instaladas.

Para iniciantes em Ciências de Dados e Inteligência Artificial a distribuição mais sugerida é a Anaconda ou a MiniConda. A primeira é completa e já vem com todas os principais pacotes da área, mas eu prefiro a segunda, pois tem só o essencial e me permite adicionar apenas o que preciso. Também, se pode utilizar a distribuição padrão Python.

De qualquer forma, a versão utilizada do Python foi a *3.7*. E sugiro fortemente que crie um novo ambiente, *environment* (Conda, Pipenv, Virtualenv, etc.).

#### Arquivos de requisitos

Para seu maior aprendizado tente levantar o ambiente e instalar as dependências informadas no notebook por conta própria. Mas se preferir dentro de um anaconda prompt execute o arquivo setup.bat.
