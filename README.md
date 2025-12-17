# Simulações do Modelo SIS em Redes Complexas

Este repositório contém um Jupyter Notebook desenvolvido para a disciplina de Ciência de Redes. O projeto foca na simulação computacional da propagação de doenças utilizando o modelo SIS em diferentes topologias de rede.

O projeto está estruturado em três análises principais:

1.  **Redes Aleatórias (Erdős-Rényi):**
    * Geração de grafos com $N=10^4$ e $\langle k \rangle = 20$.
    * Simulação da dinâmica SIS para cenários: Endêmico ($R_0 > 1$), Crítico ($R_0 = 1$) e Extinção ($R_0 < 1$).
    * Validação dos resultados simulados frente à teoria de campo médio ($i^* = 1 - 1/R_0$).

2.  **Redes Livres de Escala (Scale-Free):**
    * Geração de redes via *Configuration Model* com expoente $\gamma = 2.5$.
    * Análise do impacto da heterogeneidade (Hubs) na sustentação da epidemia e na ausência de limiar epidêmico prático.

3.  **Estratégias de Imunização:**
    * Implementação e comparação de curvas de prevalência sob três estratégias de remoção de nós:
        * **Aleatória:** Remoção uniforme de vértices.
        * **Hubs:** Remoção baseada em centralidade de grau (target high-degree).
        * **Vizinhos (Acquaintance):** Seleção estocástica de vizinhos de nós aleatórios.


## Autores

* Gustavo Bianchi da Silva
* Guilherme Carvalho Cunha
* Luiz Felipe de Abreu Marciano
