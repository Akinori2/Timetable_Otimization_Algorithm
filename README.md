## Simulated Annealing (SA)

- Inspired by thermodynamics  
- Starts with an initial solution  
- Evaluates the cost (or energy) of the solution  
- Generates a neighboring solution  
- Decides whether to accept the new solution  
- Gradually reduces the temperature  
- Repeats the process until a stopping criterion is met  
- Returns the best solution found  

---  

## Objective  
This project aims to solve a real-world issue faced by some universities regarding the allocation of computer labs using SA.    
- Reduce unnecessary demand by prioritizing course allocations  
- Allocate courses to available labs while considering constraints  
- Assign higher-priority courses before lower-priority ones  
- Minimize idle time, ensuring maximum lab utilization  
- Find an optimal allocation that minimizes the "cost" (defined as the sum of course priorities)  
- Explore different allocation possibilities to find better solutions  

---  

## Behavior  

- **Generates an initial solution**  
  - Sorts courses by priority and assigns them to labs using a simple initial allocation  
- **Calculates the solution cost**  
  - The cost is based on the sum of priorities of the allocated courses  
- **Explores neighboring solutions (alternative allocations)**  
- **Decides whether to accept a new solution**  
  - If the new solution has a lower cost, it is automatically accepted  
  - If the new solution is worse, it may still be accepted with a certain probability to avoid getting stuck in local optima  
- **Gradually reduces the temperature (Simulated Annealing)**  
  - Initially allows more changes and gradually becomes more selective to refine the solution  
- **Displays the final schedule with the best-found allocation**  

---  

## Results  

- All lab time slots are fully utilized  
- Higher-priority courses are allocated first  
- The final solution is optimized to minimize the "cost" based on course priorities 
