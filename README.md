# Quem é o protagonista de Game of Thrones?

Os roteiros das 8 temporadas foram convertidos em um grafo de co-ocorrências com `networkx`: cada personagem é um nó e cada vez que dois personagens aparecem na mesma cena, uma aresta os conecta. Métricas de centralidade — grau, autovetor e proximidade — identificam os nós mais influentes da rede. O algoritmo Girvan-Newman detecta as comunidades narrativas da série.
