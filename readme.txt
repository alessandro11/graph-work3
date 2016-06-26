Trabalho de Algoritmos e Teoria dos Grafos (ci065)
Professor: Renato Carmo
Alunos: Alessandro Elias, Ruanito D. Santos
Email: ae11@c3sl.ufpr.br, rds11@inf.ufpr.br

Na função emparelhamento_maximo() não verificamos se é ou não bipartido, pois
segundo a definição se não for bipartido o comportamento é indefinido.

Fizemos vários testes com o valgrid, não há memory leak, porém se passar para
o valgrid verbosidade, ele apresenta erros que não conseguimos encontrá-los, por tanto
não foram corrigidos, com tudo em todos os nossos testes não afeta a acuracia 
para encontrar o emparelhamento máximo.