1. Como você definiria o aprendizado de máquina?  
   R: O aprendizado de máquina é a ciência da programação de computadores na qual os possibilita aprender sem termos necessariamente que programá-los. Outra definição é: a capacidade que os computadores têm de aprender com conjuntos de treinamento dados pelo programador e desenvolver alguma tarefa específica.

2. Você consegue apontar quatro tipos de problemas que se destacam?  
   R: 1º. Problemas que exigem ajustes cuidadosos e/ou grande quantidade de linhas de regras para as se chegar a uma solução plausível;  
      2º. Problemas muito complexos para os quais não existe solução algoritmizada conhecida pelo método de programação tradicional (o próprio progrador codando);  
      3º. Problemas que existem um algorítmo adaptável a novos ambientes. Os sistemas de aprendizado de máquina podem se adaptar a novos e diferentes dados;  
      4º. Problemas em que é requerido entendimento de problemas complexos e grandes quantidades de dados.

3. O que é um conjunto de treinamento rotulado?  
   R: É um conjunto de treinamento que contém a solução desejada pelo programador em sua composição.

4. Quais são as duas tarefas supervisionadas mais comuns?  
   R: 1º. Regressão linear;  
      2º. Regressão logística;   
      3º. K-ésimo vizinho mais próximo;  
      4º. Redes neurais.

5. Você consegue citar quatro tarefas comuns não supervisionadas?  
   R: 1º. Clusterização;  
      2º. Detecção de anomalias e de novidades;  
      3º. Visualização e redução da dimensionalidade;  
      4º. Aprendizado de regras por associação.

6. Qual tipo de algoritmo de aprendizado de máquina você usaria para possibilitar que um robô andasse por aí em lugares inexplorados?  
   R: Aprendizado por reforço.

7. Que tipo de algoritmo você utilizaria a fim de segmentar seus clientes em diversos grupos?  
   R: Um algoritmo de Clusterização

8. Você acha que o problema da detecção de spam tem a ver com o aprendizado supervisionado ou não supervisionado?  
   R: Tem a ver com o aprendizado supervisionado, pois se faz necessária a solução desejada (rótulo) no conjunto de treinamento.

9. O que é um sistema de aprendizado online?   
   R: É um sistema de aprendizado que aprende instântaneamente com novas instâncias de treinamento a medida que entram.

10. O que é o aprendizado out-of-core?  
   R: É quando os algoritmos de aprendizado online são usados para treinar sistemas com um grandes conjuntos de treinamento (que não cabem na memória do computador). 

11. Qual tipo de algoritmo de aprendizado depende de uma medida de similaridade para efetuar predições?  
   R: Os algoritmos de aprendizado baseado em instância.

12. Qual a diferença entre um parâmetro de modelo e o hiperparâmetro do algoritmo de aprendizado?  
   R: Um parâmetro pode ter seus valores alterados ao longo da execução do algoritmo de AM, já o hiperparâmetro tem seu valor definido anteriormente a execução do algoritmo e permanece imutável.

13. Para que servem os algoritmos de aprendizado baseados em modelos? Qual é a estratégia mais comum que eles utilizam para serem bem-sucedidos? Como eles fazem predições?  
   R: Para, assim como o modelo baseado em instâncias, fazer generalizações de novos casos, porém esse agrupa um conjunto de de dados de treinamento e a partir desse agrupamento um modelo para fazer predições é criado. Definir uma função utilidade (função avaliação) que calcula quanto um modelo é bom ou definir uma função custo que calcula quanto um modelo é ruim. A partir de um modelo criado com base nos dados do conjunto de treinamento que visa generalizar novos casos.

14. Você pode mencionar quatro dos principais desafios do aprendizado de máquina?  
   R: 1º. Quantidade insuficiente de dados de treinamento;  
      2º. Dados de treinamento não representativos;  
      3º. Dados de baixa qualidade;  
      4º. Sobreajuste dos dados de treinamento.

15. Caso o modelo tenha um bom desempenho nos dados de treinamento, mas a generalização deixa a desejar em instâncias novas, o que está acontecendo? Você pode exemplificar três possíveis soluções?

16. O que é um conjunto de testes e por que você o utilizaria?  
   R: Um conjunto de testes é uma parte do conjunto total dos dados que é usado para verificar a eficiência do sistema de aprendizado treinado pelo conjunto de treinamento e também verificar se o mesmo está generalizando bem (se possui uma baixa taxa sobre o erro de generalização). Utilizaria para verificar quão eficiente meu sistema de aprendizado está generalizando com base no conjunto de treinamento usado.

17. Qual é o propósito de um conjunto de validação?  
   R: É uma parte separada do conjunto de treinamento que tem como função diminuir o campo que o conjunto de treinamento separado irá ter ao ser usado com diferentes modelos que por sua vez possuem diferentes hiperparâmetros.

18. O que é um train-dev set, quando é necessário e como usá-lo?  
   R: Separação de dados da internet em um conjunto restrito (conjunto de desenvolvimento de treinamento). Após o sistema ser treinado sem o train-dev set, podemos utilizar este para utilizar como um "conjunto de teste" e verificar a eficiência do nosso sistema.

19. O que pode sair de errado se você ajustar os hiperparâmetros utilizando o conjunto de testes?  
   R: A taxa de erros de generalização pode disparar devido a baixa quantidade de exemplos a serem trabalhados.