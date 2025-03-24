# Simulated Annealing(SA):
- Inspirado na termodinâmica  
- Começa com uma solução inicial  
- Avalia o custo (ou energia) da solução  
- Gera uma solução vizinha  
- Decide se aceita a nova solução  
- Reduz gradualmente a temperatura  
- Repete o processo até um critério de parada  
- Retorna a melhor solução encontrada  

---

# Obijetivo:
Nesse projeto tento solucionar um problema real de algumas faculdade em relação ao laboratorio de informatica utilizando SA
objetivos:
-  Diminuir a demanda desnecessaria organizando as materias por prioridades
-  O código aloca disciplinas nos laboratórios disponíveis considerando suas restrições
-  O algoritmo busca alocar disciplinas de maior prioridade antes das outras
-  Evita horarios vagos focando ao maximo utilizar os laboratorios de alguma forma 
-  Busca encontrar uma melhor combinação de alocação para minimizar o "custo" (que, neste caso, representa a soma das prioridades das disciplinas)
-  Explora diferentes possibilidades de alocação para tentar encontrar uma solução melhor

---

# Comportamento:
-  Gera uma solução inicial  
Classifica as disciplinas e faz uma alocação inicial simples nos laboratórios
-  Calcula o custo da solução  
O custo é baseado na soma das prioridades das disciplinas alocadas
- Explora vizinhos (possíveis soluções alternativas)  
- Decide se aceita uma nova solução  
Se a nova soluçao tiver menor custo aceita automaticamente
Se a solução for pior pode aceitá-la com uma certa probabilidade para evitar ficar preso em um resultado ruim
- Reduz a temperatura gradualmente (Simulated Annealing)  
A ideia é permitir mudanças no início e depois se tornar mais seletivo, refinando a solução
- Exibe a tabela final com a melhor alocação encontrada  

---

# Resultado:
- Todos os horários dos laboratórios devem estar preenchidos
- Disciplinas de maior prioridade são alocadas primeiro
- A solução final é otimizada para minimizar o "custo" baseado nas prioridades  
