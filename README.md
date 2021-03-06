#Comparação de Abordagens Serial e Paralela em GPU, e Branch-and Bound Aplicado ao Problema das p-medianas
Este trabalho trata do problema das p-medianas. Nele foram implementadas três abordagem diferentes para encontrar as soluções das instâncias deste problema, todas implementadas usando a linguagem C++. A primeira abordagem foi um método serial que verifica todas as possíveis soluções da instância. O segundo método foi uma implementação em paralelo, através da plataforma CUDA, que também explora todas as possíveis soluções das instâncias do problema. Na terceira abordagem, o problema foi modelado em programação linear, e foi usada uma conhecida implementação do método Branch-and-Bound, o Cplex, para calcular as instâncias. Os resultados mostram que a implementação paralela obteve um speed-up de 35.297x em relação a implementação em serial. No entanto, a abordagem usando o Cplex foi a que teve o melhor desempenho dentre as estratégias avaliadas.

Mais informações podem ser obtidas através da Wiki, neste link: 
    https://github.com/waglds/P-Medianas/wiki


<a href="https://codeclimate.com/github/waglds/P-Medianas"><img src="https://codeclimate.com/github/waglds/P-Medianas/badges/gpa.svg" /></a>
